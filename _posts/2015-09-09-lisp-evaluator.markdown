---
layout: post
title:  "Let's B uild Lisp, Part 1: The Lisp Evaluator"
date:   2015-09-09 23:41:00
---
So I made a [programming language](http://mcvoid.github.io/voidlisp). It wasn't
a particularly sophisticated one - in fact it's one of the simplest possible
ones - but now that I figured it out I can pass on the knowledge. To pass on the
knowledge I will be demonstrating the key components in JavaScript, with each
step of the process I took in just enough detail that an interested party could
do the same in their favorite language.

This is for all the people who are unsatisfied with other explanations on how to
build a programming language.

The part of making programming languages that gets the most attention is the
parser. That's because it's the first step in the pipeline, and compilers and
interpreters work very much like pipelines. I don't like that approach. I have
had aborted attempts to make languages in the past and they failed because I
fleshed out the language in terms of grammar but made clumsy attempts to
properly process the generated abstract syntax tree. Rather, I want to start by
making a solid, complete evaluator, then build the environment and built-in
operations, then building a parser last.

## The Evaluator
In this case it's an interpreter that is being built, but the evaluator is
actually neutral on the interpreted/compiled spectrum. It's basically just an
AST processor, and any compilation or interpretation will be handled by the
objects in the environment that it calls.

But we don't need nor necessarily want to think about it in these terms. Let's
just make a function called `evaluate` that processes data like Lisp does. First
let's make some tests to demonstrate what the function should do. These are in
jasmine, but use whatever you want. Unit tests are great at staying focused on
what the results should be rather than what instructions we should write.

    describe("Evaluator tests", function() {
      it("Evaluate primitives" function() {
        expect(evaluate(true)).toEqual(true);
        expect(evaluate(false)).toEqual(false);
        expect(evaluate(5)).toEqual(5);
      });
      // more tests later
    });

So the first thing we need the evaluator to do is to return a primitive value if
it receives that value in. In this case, any data input to the evaluator is
going to be called a form. (That's just something I'm calling it, not a proper
term.) A simple identity function solves this handily.

    function evaluate(form) {
      return form;
    }

Now it is time to give the evaluator a special ability: function application.
For my purposes, I'm going to just hijack JavaScript's function application
mechanism, `Function.prototype`'s `apply()` method and use JavaScript functions
to represent Lisp functions. If you make this in an object-oriented language
like Java, it would be best to make use of the Command pattern. You can look to
Clojure's `IFn` interface for inspiration.

In Lisp, when a list is evaluated, it evaluates the first item in the list, and
tries to use the result as a function and applies the function to the rest of
the list. We can just use arrays as lists. So here's the tests that demonstrate
function application.

    it("function application", function() {
      var func = function(a, b) { return a + b; };
      expect(evaluate([func, 3, 5])).toEqual(8);
      func = function(x) { return !x; }
      expect(evaluate([func, true])).toEqual(false);
      var sideEffect = false;
      func = function() {
        sideEffect = true;
      }
      evaluate([func])
      expect(sideEffect).toEqual(true);
    });

Once again the solution is fairly trivial, but I'm going to start adding some
helper functions that might come in handy later.

    function first(list) { return list[0]; }
    function rest(list) { return list.slice(1); }
    function evaluate(form) {
      if (form instanceof Array) {
        var func = evaluate(first(form));
        return func.apply(rest(form));
      }
      return form;
    }

Now we have something that can execute functions. Not too shabby for like 6 or
so lines. But there's a lot more than that to do, which will be covered later.
