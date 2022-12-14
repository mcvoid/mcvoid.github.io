---
title: "Core Rules"
weight: -1
---

# Abilities

Abilities are the main way characters interact with the 
world. Almost every action a character can take which can 
possibly end in failure involves using an ability. These 
abilities are described by scores, describing how good or 
bad a character is at doing certain tasks, and their 
corresponding bonuses, describing how die rolls are 
modified.

### Ability Descriptions

Characters are described by six abilities: strength, 
dexterity, constitution, intelligence, wisdom, and 
charisma.

##### Table 0: Abilities
Ability      | Describes | Used for | Affects | Saves against
:------------|:----------|:---------|:--------|:--------------
Strength     | the power you can generate | Pushing, pulling, lifting, bending climbing | melee attack rolls | entanglement and restrainment
Dexterity    | agility, equilibrium, and coordination | dodging, catching, tumbling, aiming, balancing | armor class, ranged attack rolls | traps, area of effect spells
Constitution | health and resilience | feats of endurance and warding off threats to their physicality | total hit points | poison, petrification, death
Intelligence | information retention, logic and pattern recognition faculties | knowledge, ability to reason | arcane spellcasting ability | insanity, psychic attacks
Wisdom       | perceptiveness and ability to distinguish subtleties | perception and insight | divine spellcasting ability | charms and illusions
Charisma     | force of personality and leadership ability | performance, diplomacy, deception | thief's scroll use, followers | possession and curses

### Ability Checks

In order to determine success for failiure for any action, 
the Game Master (GM) will prompt a player to make an abliity check vs a 
Difficulty Class (DC). The formula to determine success is as 
follows:

```
1d20 + ability bonus >= DC
```

The GM determines which ablilty is relevant to the check.

### Proficiency

Proficiency is an indicator of whether a character has 
training or competence in a particular activity. Ability 
checks done for activities in which a character is 
procifient have the character's proficiency bonus to the 
roll result.

```
1d20 + ability bonus + proficiency bonus >= DC
```

The GM determines whether a roll is with proficiency or 
not.

### Advantage and Disadvantage

Sometimes circumstances make a feat easier or harder to 
accomplish than it needs to be. In such a case, a roll can 
be done with advantage or disadvantage. For example, trying 
to shoot an arrow at someone who is invisible would be 
harder for the person doing the shooting. Meanshile, the 
invisible person whould have an easier time attacker their 
opponent.

When the situation favors the initiator of the action, they 
roll with advantage. To roll with advantage, instead of 
taking a single d20 roll, they roll twice and take the 
higher of the two rolls.

Similarly when the situation disfavors the initiator, they 
roll with disadvantage. To  roll with disadvantage, 
instead of taking a single d20 roll, they roll twice and 
take the lower of the two rolls.

There is no such thing as "double" or "triple" advantage. 
Compounding effects cannot bestow extra dice to be rolled 
as part of advantage. If two compounding factors 
simultaneously impart both advantage or disadvantage, the 
roll is made with a  straight d20 roll, no matter how many 
effects are in favor or against.

For example, if a character is both invisible and has the 
high ground is trying to shoot an enemy with a bow, but 
their target is lying prone, there are two factors which 
may impart advantage and one effect which may impart 
disadvantage. In this case, the attack roll is rolled 
normally, as the advantage and disadvantage cancel each 
other out.

# Combat

### Time and Combat Rounds
Time flows in two different ways, depending on whether or not combat has started. Outside of combat, actions typically take one minute, ten minutes, or an hour. 

Inside combat, action is faster-paced and many things happen at once. Combat happens as a series of rounds. Each round is 6 seconds long, so 10 rounds happens over the course of 1 minute.

### Order of Combat

The order of combat is side-based. So the opponents all have a turn at once, then the players all have a turn at once, deciding amongst themselves the order they act.

When combat starts, the players roll initiative. Initiative is a Dexterity check DC 10. If the opponents are not aware of the party *and* the party is actively trying to ambush the opponents, initiative is rolled with advantage. Conversely, if the party is *not* aware of the opponents and the opponents are actively trying to ambush the party, initiative is rolled with disadvantage.

Characters who passed their initiative go first. After the initiative winners have their turn, the opponents' regular turn begins and the combat proceeds with the normal order of combat.

### On Your Turn

Players on their turn have two main actions:
* Their character can take an action.
* Their character can spend their movement budget.

Movement can happen at any time during the turn. So a character may move 30' before an action, or after an action, or even in the middle of an action. For example, a character with extra attacks may break up an attack so that they move in between each attack.

### Actions
An action is the main thing the character does over the course of the round. Consult the table below for the mechanic that resolves the action.

##### Table 1: Actions

 Action         | Effect                       
:---------------|:-----------------------------
 Attack         | Make a single attack roll    
 Dash           | Add 30' to movement budget  
 Cast a Spell   | See spell description 
 Disengage      | Movement doesn’t provoke opportunity attacks for the rest of the turn 
 Dodge          | Attacks against you have disadvantage
 Help           | Give one ally advantage on one roll this round 
 Use an Object  | The object is interacted with 
 Other          | GM's discretion 

### Attack Rolls
Attacking is the core action of combat. It consists of two parts: the attack roll and the damage roll. The attack action allows only one attack roll unless otherwise specified.

To make an attack roll, roll an ability check against the target's armor class. Which ability is rolled depends on the type of attack. Consult the table below to determine the type of check needed. If you are using a weapon to attack, you may do so with proficiency if you are proficient in that weapon. Magic users are always proficient with spell attacks.

If a weapon attack is successful, roll the damage die indicated in Table 24. If the weapon is not ranged, you may add your Strength bonus to the damage. Ranged weapons and spells do not get added damage from ability scores unless otherwise noted.

##### Table 2: Attack Rolls

 Attack               | Check        | Result                 
:---------------------|:-------------|:-----------------------
 Melee Attack         | Strength     | Weapon dmg + Str bonus 
 Unarmed Attack       | Strength     | 1d4 dmg + Str bonus    
 Thrown Weapon        | Dexterity    | Weapon dmg + Str bonus 
 Ranged Attack        | Dexterity    | Weapon dmg             
 Arcane Spell Attack  | Intelligence | Spell effect succeeds  
 Divine Spell Attack  | Widsom       | Spell effect succeeds  

### Critical Hits and Misses

If an attack roll is a *natural 20*, (the literal number on the die is 20, before factoring in bonuses), you have scored a critical hit. Critical hits automatically hit, even if the roll result doesn't meet the armor class. In addition, a minor benefit occurs. Usually the result is that you roll double the normal dice for damage before factoring in bonuses. But the player may opt for a different effect at the GM's discretion, as appropriate for the situation. For example, the creature is knocked prone, or drops their weapon, or an ally turns up just in time to help out, or maybe the creature was already standing precariously at the edge of the cliff and a critical hit sends them over the edge.

Conversely, if the attack roll is a *natural 1*, the attack automatically misses. However, the player may choose to succeed anyway, in which case the GM introduces a minor detriment to the character. It may be that their weapon gets stuck and they lose use of it while the opponent is still standing, or the ground gives way and they fall into a fall cavern, or their nemesis just managed to track them down and now have two situations to deal with.

### Distance and Range

Distances can be long range, short range, touch, and self.

Self, as one might expect, indicates it can only happen to the caster of that spell. When a spell description mentions "you", it means the caster, so spelss that target "you" are self range.

Touch means roughly within arm's reach. Short range is within a stone's throw. Long range is about as far as an arrow can reach. These are left deliberately vague and flexible. 

Melee weapons (weapons which are not thrown and are not ranged) only attack targets within touch range. The same applies for unarmed attacks. Thrown weapons can only attack targets in short range or closer. Other ranged weapons may attack targets up to the distance indicated as their range in the equipment tables.

A PC *may* use a weapon at a longer range than incidated above. For example, throwing a weapon without the *thrown* property. The GM has discretion on whether it's actually physically possible for the weapon to reach that far. If the target is reachable, the attack is made with disadvantage. For example, it's certainly possible for the bolt of a light crossbow to reach long range, but as it's not designed to shoot so far with accuracy, the attack is made with disadvantage.

### Spell Attacks

To affect an unwilling touch target with a spell (such as with inflict wounds) requires a spell attack. Ranged spell effects against a single unwilling creature with no saving throw specified are also spell attacks. There is no difference to the roll whether the spell target is within touch, short range, or long range as long as the target is within the distance indicated by the spell.

### Movement

Movement works like money. Each round every character has a budget of 30' of movement to spend. Actions like dash increase the budget. Normally 5' of movement moves your character 5' of distance. In some circumstances, the cost may be more.

In rough terrain, the cost to move is doubled. For example, the cost to move 5' of distance is 10' of movement. The following are possible examples of rough terrain, but the decision as to what counts as rough terrain is determined by the GM.

* Soft sand
* Deep mud
* Knee-high water
* Blizzard-level winds
* Slippery ice
* Going up a somewhat steep incline
* Climbing with a rope
* Crawling
* Swimming
* A bridge made of spiderwebs
* A mountain of loose gold coins

### Reactions

Every character gets one reaction per round. These are things which can happen outside of a character's normal turn. A reaction can only happen on a particular trigger. The reaction happens before the triggering action can take effect.

The following are examples of reactions. Every character has an opportunity attack as a reaction. Other reactions come from class traits and memorized spells.

##### Table 3: Example Reactions

 Reaction           | Trigger                                | Effect
:-------------------|:---------------------------------------|:--------
 Opportunity Attack | Opponent within touch range moves away | An extra attack can be made before they move
 Set                | Opponent charges the character         | An extra attack can be made before the charge takes effect
 Shield Spell       | Opponent makes a successful attack     | AC + 5, Magic missiles are blocked
 Lay on Hands       | Anything                               | Spend healing dice

### Opportunity Attacks

If an creature is within touch range of their opponent uses their movement to move outside of touch range, it provokes an opportunity attack by the opponent. The opponent gets a single attack roll on the moving creature before they leave touch range. This is not an Attack action, so multiple attacks are not possible, but other combat maneuvers that only cost an attack roll like Disarm can be used as an opportunity attack.

A creature that uses the Disengage action does not attract oppotunity attacks and can freely move into and out of touch range for the remainder of their turn.

### Saving Throws

Saves are ability checks used to avoid effects. These are made the same as any attack roll or skill check is made, with proficiency being determined by the class. Success results in that particular negative effect being avoided entirely, unless the effect's description says otherwise.

### Special Effects and Conditions

Combat is complex, and any number of things can happen in the heat of battle that can help or hurt your chances of winning. In lieu of a comprehensive set of conditions, such judgements are left to the GM to be applied on a situational basis. The effect most of these should have is advantage or disadvantage. The table below is a small sample of situations where advantage may apply.

##### Table 4: Example Conditions 

| Situation            | Effect        
|:---------------------|:--------------
| Have the high ground | Advantage on attacks on opponents, disadvantage on opponents' attacks
| Blinded              | Disadvantage on attacks on opponents, advantage on opponents' attacks
| Darkness             | Disadvantage on all attacks in the area
| Prone                | Opponents' melee attacks have advantage, opponents' ranged attacks have disadvantage
| Called shot          | Disadvantage on shot, in exchange for an agreed-upon condition for one round
| Flanked              | Opponents attacks have advantage
| Behind cover         | Opponents attacks have disadvantage
| Unconscious          | Opponents attacks have advantage
| Teary-eyed from watching your true love die | Attacks have disadvantage
| Your ally being used as human shield by target | Attacks on target have disadvantage

### Exhaustion

Extreme heat or cold without proper preparation, 24 hours without sleep, a day without water, or three days without eating result in a level of exhaustion. Each level of exhaustion results in a cumulative  -2 penalty to all rolls and 5' fewer movement budget avalable. Seven cumulative levels of exhaustion results in death. A full day's rest cures one level of exhaustion.

### Death and Dying

When a character drops to 0HP, they are unconscious and dying. If the character is healed at any point before death, they are cured of the dying condition and are no longer unconscious.

When the character first enters the dying condition, they must make a constitution saving throw DC 10. They must repeat the throw every minute afterward or anytime they take damage in the dying condition. Upon the accumulation of three failed saves since the last time the character took a full day of rest, the character is dead.

