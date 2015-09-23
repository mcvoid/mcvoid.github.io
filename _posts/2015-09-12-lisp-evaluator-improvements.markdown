---
layout: post
title:  "Let's Build Lisp, Part 2: Expanding the Lisp Evaluator"
date:   2015-09-12 10:25:00
---
In the previous article, I described the very basics of function application in
a Lisp evaluator. The result is an extremely simple function which takes a form,
and spits out another form, though if it's passed a list, it evaluates the first
item in the list, treats it like a function, and applies the function to the
rest of the arguments.

    function first(list) { return list[0]; }
    function rest(list) { return list.slice(1); }
    function evaluate(form) {
      if (form instanceof Array) {
        var func = evaluate(form[0]);
        return func.apply(form.slice(1));
      }
      return form;
    }

But why does it need to recursively evaluate the first argument? Two reasons:
1. The first argument might in turn be another list, in which case it's another
function call which should return a function, or
2. The first argument is a symbol which needs to be resolved.

## Symbols
So symbols are names you attach to values. In that sense, they are just strings.
They are one half of what makes a binding, which is what a variable is: a
symbol-value pair. These bindings are stored in a symbol table, or an
environment. To add a binding to an environment, just add a name to the table
and give it a value. This can be done with any associative array, though
JavaScript objects are especially well suited for this task for reasons we'll
get to later.

Enough exposition, let's define a symbol.

    function Symbol(name) {
      this.val = name;
    }

Why didn't we just use a string? Two reasons, really. First, we might want to
have string literals in the language at some point (technically, we already do,
as they pass through the evaluator and come out as strings) and we'd like to use
JavaScript string literals to internally represent them. After all, that's a
data type we don't have to implement or debug and comes with a slew of utilities.
Secondly, we need a way to distinguish them from other types, so making a
constructor allows us to use the `instanceof` operator to tell easily.

Now it's time to modify the evaluator to check if somethings a symbol and
perform a lookup. I'd normally start with the unit tests, but for now let's look
at the code, and see what happens.

    function evaluate(form) {
      if (form instanceof Symbol) {
        var environment = ???
        var key = form.val;
        return environment[key];
      }
      if (form instanceof Array) {
        var func = evaluate(first(form));
        return func.apply(rest(form);
      }
      return form;
    }

Wait, where does the environment come from? Where do you store it? Is it a
global variable? Actually, I lied to you about the evaluator. It's not a
function that takes a form and returns another form. It's a function that takes
an environment and a form to produce that form. Whatever invokes `evaluate` passes
in the environment they want to use. This is great for unit testing, because we
can define our own environments that don't have to include everything in the
language: just the parts we want to test. Here's the test for the new
evaluator.

    it("Evaluation of symbols", function() {
      var env = {
        a: 5
      };
      var a = new Symbol("a");
      var b = new Symbol("b");
      expect(evaluate(env, a)).toEqual(5);
      expect(evaluate(env, b)).toEqual([]);
      expect(evaluate({}, a)).toEqual([]);
      expect(evaluate({}, [])).toEqual([]);
    });

So we want a symbol to return the value, but why return an array literal when
there's no match? And what's up with that last line? In Lisp, the null value,
called nil, is usually represented by an empty list, so we need to take that
into account both for inputs and outputs.

    function evaluate(environment, form) {
      if (form instanceof Symbol) {
        var key = form.val;
        if (key === undefined) { return []; }
        return environment[key];
      }
      if (form instanceof Array) {
        if (form.length === 0) { return []; }
        var func = evaluate(first(form));
        return func.apply(rest(form);
      }
      return form;
    }

And that's it! next time I'll get into scopes.
