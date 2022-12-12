---
layout: page
title:  "Player Guide"
version:  "1.0"
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

#### Strength

The power a character can generate. This score affects 
tasks that involve pushing, pulling, lifting, bending, and 
climbing.

Strength also affects melee attack rolls and damage.

#### Dexterity

A character's agility, equilibrium, and coordination. This 
score affects dodging, catching, tumbling, aiming, and 
balancing.

Dexterity also affects ranged attack rolls.

#### Constitution

A character's health and resilience. This score affects 
feats of endurance and warding off threats to their 
physicality.

Constitution also affects total hit points.

#### Intelligence

The information retention, logic and pattern recognition 
faculties of a character. This score affects knowledge, 
ability to reason.

Intelligence also affects arcane spellcasting ability.

#### Wisdom

A character's perceptiveness and ability to distinguish 
subtleties. This score affects perception and insight.

Wisdom also affects divine spellcasting ability.

#### Charisma

A character's force of personality and leadership ability. 
This score affects a character's ability to perform, lie 
convincingly, and conduct diplomacy.

Charisma also affects the number of followers a character 
can attract and maintain.

### Ability Checks

In order to determine success for failiure for any action, 
the Game Master (GM) will prompt a player to make an abliity check vs a 
Difficulty Class (DC). The formula to determine success is as 
follows:

```
1d20 + revelant ability bonus >= difficulty class
```

The GM determines which ablilty is relevant to the check.

### Proficiency

Proficiency is an indicator of whether a character has 
training or competence in a particular activity. Ability 
checks done for activities in which a character is 
procifient have the character's proficiency bonus to the 
roll result.

```
1d20 + revelant ability bonus + proficiency bonus >= difficulty class
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

Movement can happen at any time during the turn. So a character may move 30' before an action, or after an action, or even in the middle of an action. For example, a character with extra attacks may break up an attacks so that they move in between each attack.



### Actions
An action is the main thing the character does over the course of the round. Consult the table below for the mechanic that resolves the action.



##### Table 1: Actions

| Action         | Effect                                              |
|:---------------|:----------------------------------------------------|
| Attack         | Make a single attack roll                           |
| Dash           | Add 30' to movement budget                         |
| Cast a Spell   | See spell description                               |
| Disengage      | Movement doesn’t provoke opportunity attacks for the rest of the turn | 
| Dodge          | Attacks against you have disadvantage               |
| Help           | Give one ally advantage on one roll this round      |
| Use an Object  | The object is interacted with                       |
| Other          | GM's discretion                                     |



### Attack Rolls
Attacking is the core action of combat. It consists of two parts: the attack roll and the damage roll. The attack action allows only one attack roll unless otherwise specified.

To make an attack roll, roll an ability check against the target's armor class. Which ability is rolled depends on the type of attack. Consult the table below to determine the type of check needed. If you are using a weapon to attack, you may do so with proficiency if you are proficient in that weapon. Magic users are always proficient with spell attacks.

If a weapon attack is successful, roll the damage die indicated in Table 24. If the weapon is not ranged, you may add your Strength bonus to the damage. Ranged weapons and spells do not get added damage from ability scores unless otherwise noted.




##### Table 2: Attack Rolls

| Attack               | Check                               | Result                 |
|:---------------------|:------------------------------------|:-----------------------|
| Melee Attack         | Strength vs AC                      | Weapon dmg + Str bonus |
| Unarmed Attack       | Strength vs AC                      | 1d4 + Str bonus        |
| Thrown Weapon        | Dexterity vs AC                     | Weapon dmg + Str bonus |
| Ranged Attack        | Dexterity vs AC                     | Weapon dmg             |
| Arcane Spell Attack  | Intelligence vs AC with proficiency | Spell effect succeeds  |
| Divine Spell Attack  | Widsom vs AC with proficiency       | Spell effect succeeds  |



### Critical Hits and Misses
If an attack roll is a *natural 20*, (the literal number on the die is 20, before factoring in bonuses), you have scored a critical hit. Critical hits automatically hit, even if the roll result doesn't meet the armor class. In addition, a minor benefit occurs. Usually the result is that you roll double the normal dice for damage before factoring in bonuses. But the player may opt for a different effect at the GM's discretion, as appropriate for the situation. For example, the creature is knocked prone, or drops their weapon, or an ally turns up just in time to help out, or maybe the creature was already standing precariously at the edge of the cliff and a critical hit sends them over the edge.

Conversely, if the attack roll is a *natural 1*, the attack automatically misses. However, the player may choose to succeed anyway, in which case the GM introduces a minor detriment to the character. It may be that their weapon gets stuck and they lose use of it while the opponent is still standing, or the ground gives way and they fall into a fall cavern, or their nemesis just managed to track them down and now have two situations to deal with.




### Distance and Range
Distances can be long, short, touch, and self. Touch means roughly within arm's reach. Short range is within a stone's throw. Long range is about as far as an arrow can reach. 



### Spell Attacks

To affect an unwilling touch target with a spell (such as with inflict wounds) requires a spell attack. Ranged spell effects against a single unwilling creature with no saving throw specified are also spell attacks.



### Movement

Movement works like money. Each round every character has a budget of 30' of movement to spend. Actions like dash increase the budget. Normally 5' of movement moves your character 5' of distance. In some circumstances, the cost may be more.

In rough terrain, the cost to move 5' of distance is 10' of movement. The following are possible examples of rough terrain, but the decision as to the cost of movement is determined by the GM.

* Soft sand
* Deep mud
* Knee-high water
* Blizzard-level winds
* Slippery ice
* Going up a somewhat steep incline
* Climbing with a rope
* Crawling
* Swimming




### Reactions

Every character gets one reaction per round. These are things which can happen outside of a character's normal turn. A reaction can only happen on a particular trigger. The reaction happens before the triggering action can take effect.

The following are examples of reactions. Every character has an opportunity attack as a reaction. Other reactions come from class traits and memorized spells.



##### Table 3: Example Reactions

| Reaction           | Trigger                        | Effect  |
|:-------------------|:-------------------------------|:--------|
| Opportunity Attack | Opponent within 5' moves away  | An extra attack can be made before they move |
| Set                | Opponent charges the character | An extra attack can be made before the charge takes effect
| Shield             | Opponent makes a successful attack or casts Magic Missile targeting the character | AC + 5, Magic missiles are blocked |
| Lay on Hands       | Anything                       | Spend healing dice



### Saving Throws

Saves are ability checks used to avoid effects. These are made the same as any attack roll or skill check is made, with proficiency being determined by the class. Success results in that particular negative effect being avoided entirely, unless the effect's description says otherwise.



### Special Effects and Conditions

Combat is complex, and any number of things can happen in the heat of battle that can help or hurt your chances of winning. In lieu of a comprehensive set of conditions, such judgements are left to the GM to be applied on a situational basis. The effect most of these should have is advantage or disadvantage.



##### Table 4: Example Conditions 

| Situation              | Effect        |
|:-----------------------|:--------------|
| Having the high ground | Advantage on attacks on opponents, disadvantage on opponents' attacks |
| Blinded                | Disadvantage on attacks on opponents, advantage on opponents' attacks |
| Darkness               | Disadvantage on all attacks in the area                               |
| Prone                  | Opponents' melee attacks have advantage, opponents' ranged attacks have disadvantage |
| Called shot            | Disadvantage on shot, in exchange for an agreed-upon condition for one round |
| Flanked                | Opponents attacks have advantage    |
| Behind cover           | Opponents attacks have disadvantage |
| unconscious            | Opponents attacks have advantage    |



### Exhaustion
Extreme heat or cold without proper preparation, 24 hours without sleep, a day without water, or three days without eating result in a level of exhaustion. Each level of exhaustion results in a cumulative  -2 penalty to all rolls and 5' fewer movement budget avalable. Seven cumulative levels of exhaustion results in death. A full day's rest cures one level of exhaustion.



### Death and Dying
When a character drops to 0HP, they are unconscious and dying. If the character is healed at any point before death, they are cured of the dying condition and are no longer unconscious.

When the character first enters the dying condition, they must make a constitution saving throw DC 10. They must repeat the throw every minute afterward or anytime they take damage in the dying condition. Upon the accumulation of three failed saves since the last time the character took a full day of rest, the character is dead.


# Character Creation

Creating a character should be quick and easy. As a result 
there is not a large catalague of skills and subclasses 
and subraces to choose from. Those more specific 
archetypes and be achieved by reskinning existing classes 
and backgrounds.


## Roll Ability Scores

### Rolling Method

#### 3d6 Shared Array

Roll 3d6 six times to generate six numbers. Everyone at 
the table takes the same six numbers and each allocates 
the numbers to different abilities any way they choose.

This method insures that even if there are some very high 
or very low scores rolled, it won't be too debilitating to 
a single player as every character will have a similarly 
low or high ability.

### Abilty Descriptions
Abilities are the scores used to determine how well a 
character can naturally do different tasks.


##### Table 5: Abilities

| Abilty       | Used for                             |
|:------------:|:-------------------------------------|
| Strength     | Melee attacks, feats of might        |
| Dexterity    | Ranged attacks, agile maneuvers      |
| Constitution | Bonus HP, Endurance, death save      |
| Intelligence | Arcane magic, knowledge              |
| Wisdom       | Divine magic, awareness              |
| Charisma     | Followers, persuasion                |


### Ability Bonuses
Abilities determine bonuses to roll ability checks.


##### Table 6: Ability Bonuses

| Score  | Bonus  |
|:------:|:------:|
| 3-6    | -2     |
| 6-7    | -1     |
| 8-13   | +0     |
| 14-15  | +1     |
| 16-17  | +2     |
| 18-20  | +3     |


## Choose Background
Backgrounds determine the skills and tool proficiencies 
and increase two abilities to increase by 1 to indicate 
prior training.


##### Table 7: Example Backgrounds

| Background | +1 to    | Potential Skills               |
|:----------:|:---------|:-----------------------------|
| Noble      | Int, Cha | Diplomacy, deception         |
| Soldier    | Str, Con | Athletics, survival          |
| Acolyte    | Wis, Cha | Religion, medicine           |
| Scholar    | Int, Wis | Arcana, history              |
| Hermit     | Con, Wis | Survival, nature             |
| Pastoral   | Con, Cha | Animal handling,  survival   |
| Scoundrel  | Dex, Cha | Stealth, sleight of hand     |
| Enforcer   | Str, Dex | Intimidation, perception     |
| Performer  | Dex, Cha | Performance, acrobatics      |
| Trade      | any two  | Dependent on the trade       |



## Choose Class
Classes determine the character archetype.



##### Table 8: Class List

| Class      | Specialty                         |
|:-----------|:----------------------------------|
| Cleric     | Divine magic, turn undead         |
| Dwarf      | Combat, Divine magic              |
| Elf        | Two weapon fighting, arcane magic |
| Jack       | Jack of all trades                |
| Mage       | Arcane magic, ritual casting      |
| Thief      | Backstab, skills                  |
| Warrior    | Combat, weapon mastery            |


## Choose Equipment

Each character starts with one light weapon, One tool 
relevant to their background, and 3d6 x 10 gp.

They can buy armor, shields, stronger weapons, and other 
sundries and adventuring gear from the equipment list 
before starting on their first adventure.

## Choose Spells
Spellcasters select 2 spells for their initial spellbook, if  they have spellcasting ability at first level. Spells are listed in Table 33 for arcane spellcasters and Table 34 for divine spellcasters.

## Calculate Starting Numbers
Now that the main choices have been made, there's just a 
few more things which need to be filled out before you're 
ready to go.


##### Table 9: Starting Numbers

| Number            | Formula                                      |
|:-----------------:|:---------------------------------------------|
| Proficiency bonus | +2                                           |
| Hit Points        | 4 + Hit die + Con modifier                   |
| AC                | Armor AC *or* 10 + Dex modifier if unarmored |
| Initiative        | Dex Modifier                                 |
 

And that's it. Happy adventuring!

# Higher levels

As time goes on and your character plies their adventuring 
craft and practice the tasks of dungeoneering and combat 
and questing, they are bound to eventually get better at 
what they do. As they do, they will gain class levels and 
grow more powerful as their influence spreads.

### How to Level Up

All that's needed to level up is to adjust a few vital 
statistics.

#### Hit Points

Each time you gain a level, you gain 1 additional Hit Die. 
Roll that Hit Die, add your Constitution modifier to the 
roll, and add the total (minimum of 1) to your hit point 
maximum.

For example, a Fighter with a Constitution score of 14 (+1 
bonus) will see their Hit Points increase by 1d10 + 1 each 
level.

#### Proficiency Bonus

Your proficiency bonus increases by 1 for every four levels 
gained. So it starts as +2, increases to +3 upon reaching 
level 5, increases to +4 upon reaching level 9, +5 at level 
13 and so on.

#### Spell Slots

The spell slots for a spellcaster are updated according to 
the chart in their class description.

Spellcasters add 2  spells to their spellbook of a tier for 
which they have  spell slots. They may not add any spells 
not in their respective spell list. If they do not yet any 
any slots upon  leveling, they do not add any spells to 
their book.

A spellcaster may also add any spells from another 
spellbook or scroll to their own book as they find them, 
provided the spells are in the spell list for the class.

### When to Gain Levels

This one is left entirely to the GM. There are as many 
opinions on how to determine this as there are GMs. The 
only rule imposed here, however is to *reward the kind of 
behavior the GM wants to promote*. Here are a few ways 
leveling can be used as a reward to promote a particular 
play style.

Something to consider is changing the leveling method mid-
campaign. This can be a very effective tool for keeping the 
campaing exciting as characters grow out of different play 
styles. A good point to change up progression is when the 
tier of play shifts.

For example, maybe low levels are about getting loot from 
dungeons, so using gold for experience is appropriate. 
Later when the PCs gain a stronghold, they may level as 
certain objectives are achieved. At that point, they 
determine the direction of their domain and are dealing 
with the consequences of their decisions, so the GM may set 
objectives based on what the players' long term goals 
should be, and level the PCs as reward for chasing those 
objectives.


##### Table 10: Leveling Methods

| Method                               | Style Encouraged      |
|:------------------------------------:|:----------------------|
| 1 XP per gold piece                  | Dungeon looting       |
| XP per monster slain                 | Combat-focused        |
| Milestones reached                   | Story-focused         |
| Areas discovered                     | Exploration-focused   |
| Office vacancy/combat for leadership |Social power structures|
| Player-set objectives                | Self-determination    |
| XP per session                       | Attendance prioritized|


### Tiers of Play

As characters gain in power, they seek challenges of 
greater power while their presence invites greater 
conflict. In other words, the world should react to the 
change of the balance in power that higher-level PCs will 
bring. Doing so changes the focus of play to something 
greater in scope. These changing foci are called *tiers of 
play*. When the tier changes is determined by the GM in 
response to player actions.

#### Tier 1: Local Threats

PCs tend to start out exploring a local area, fighting 
monsters that pose local threats. The blacksmith's daughter 
is missing. There's a nearby cult. Here the rewards tend to 
be gaining combat power and wealth.

#### Tier 2: Regional Politics

At some point the PCs tend to have amassed enough power 
that they find themselves, willingly or not, more 
responsible for the local area against larger regional 
threats. At this point it's usually not a single monster as 
much as it is organizations.

Ususally it is appropriate for the PCs to gain a stronghold 
and start to attract followers.

#### Tier 3: Kingdoms and Warfare

At this tier, the adventurers cannot be easily challenged 
by any single person or monster, but are dealing with some of 
the campaign setting's central tensions which prop up the 
world's power structures. The threats at this stage 
are to entire countries or even the world, and can involve 
leading armies in massive struggles.

#### Tier 4: Transcendence

This tier is when the focus of the players is on their 
legacy. They will meet with the proxies and avatars of 
deities directly. PCs will seek immortality either 
figuratively or literally, possibly seeking godhood.

The challenges in this tier have to do with the great 
cosmic conflicts and interplanar creatures.

# Backgrounds
Characters weren't born as adventurers. They grew up in an 
area, in a certain niche of a certain society. They 
learned the in's and out's of the business of those around 
them. They learned the trades of the adults around them. 
They exercised their bodies and minds to perform certain 
tasks. They got proficient in certain types of work. They 
developed different outlooks.

Backgrounds are meant as an abstraction to cover all of 
the experience of growing up, all the way up to picking up 
your adventuring gear. Where you come from and how you 
were raised gives each character advantages in different 
situations, and nobody ends up perfectly well-rounded.

Each character picks or develops their own background on 
character creation. It should be something clear enough 
that the one-word name of the background should give 
people a good idea of what kind of activities your 
character my might expected to excel at.

### Where's the Skills?

Individual skills are not included in this game, to be 
replaced by a general sense of what people with your 
background might do often. When an ability check happens, 
the GM can indicate whether your background may allow you 
to add your proficiency bonus to the roll.

While the GM is expected to maintain a list of each 
character's backgrounds, feel free to ask (not argue!) if 
this is a task which resembles something you have 
experience with. For example, someone raised as a farrier 
(one who makes and fits horseshoes) would reasonably be 
expected to be proficient in both smithing and animal 
handling, along with knowledge tangential to both fields, 
while a carpenter would be procifient in woodworking, 
nature where it concerns the forest and trees, some 
structural engineering learned when making houses, some 
knowledge of the law concerning housing, residency, 
building codes, and so on.

This way of handling proficiency has several advantages:
1. When it comes to decide which character should perform 
a task, volunteering because you "worked with animals all 
the time growing up" is less immersion-breaking than doing 
it because you "have a +5 to animal handling".
1. The list of skills is flexible to fit any genre. Maybe 
a world had sci-fi or modern elements: instead of adding 
skills, you can flexibly determine proficiency easily on a 
case-by-case basis, without having to add skills relvant 
to that society like "hacking". Also, as a GM you don't 
have to worry about diluting the skill point value by 
making skills too granular.
1. It saves character sheet space significantly and can 
speed up play by not having to look up numbers.
1. Encourages creative play, so you don't feel limited to 
only doing actions that are part of a list.
1. You can fit all the things a character can do well 
inside a list.

### Making a Background

A list of example backgrounds is included in **Table 3: 
Backgrounds**, but you are not limited to just those 
options. The sky is the limit, subject to GM discretion, 
of course. You just need a few things to make your own 
background:

1. A name that is identifiable enough to give another 
person a reasonable idea of what skills you might possess 
just from that one word.
1. Two ability scores that would be developed by such an 
envrionment to reflect the years of physical and mental 
conditioning involved in that background.
1. A reason why someone in that profession would adopt the 
high-risk, high-reward, "adrenaline junky" lifestyle of an 
adventurer.
1. GM buy-in. Make sure the GM understands what's involved 
in growing up in this background, and agrees to the 
ability bonuses.

# Classes

A character's class is the archetype that they embody. In this game, classes exist to give characters mechanical abilities. In other words, while backgrounds define who they are, classes define what they can do.



##### Table 11: Quick Summary of CLasses

| Class   | Hit Die type | Weapons & Armor                                             | Saves    |
|:-------:|:------------:|:------------------------------------------------------------|:---------|
| Cleric  | d8           | Clubs, maces, and all armor and shields                     | Wis, Cha |
| Dwarf   | d8           | All melee weapons, all armor and shields                    | Con, Wis |
| Elf     | d6           | Swords, bows, light weapons, light armor                    | Str, Int |
| Jack    | d6           | All one-handed weapons, crossbows, light weapons and armors | Dex, Con | 
| Mage    | d4           | Daggers and staves                                          | Int, Wis |
| Thief   | d6           | Crossbows, light weapons and armors                         | Dex, Cha |
| Warrior | d10          | Any & all                                                   | Str, Dex |



### Hit Dice
Hit dice describe three intertwined concepts.
#### Hit Points
Hit dice describe how many dice you should have rolled to determine your total hit points. So if you have 5d6 and upon level up you now have 6d6, your hit point total increases by 1d6 + your Con bonus (minimum 1).
#### Power level and Spell Resilience
Many spells affects a certain number of hit dice of creatures. Use the hit dice listed in the class table to determine whether or not it affects you.
#### Healing While Resting
When resting for 8 hours, the hit dice indicate how many hit points are gained over the course of rest. For example, if you have 5d6 hit points and you rest, you heal for 5d6 + Con bonus hit points.



### Racial Archetypes

Three of the classes: Dwarf and Elf, are representative of three idiosyncratic martial traditions of these three cultures. Namely, elven bladesingers and dwarven warpriests. Each of these is a blend of other class abilities, along with some unique traits of their own.

Don't read the racial martial archetypes as being strictly limited to those races. The whole point is to be light on the rules, and allow variety through GM discretion and reskinning. So if you want, say, a human bard who can fight and sing and use some magic, take the Elf class, give them a human musical background, and you'll be set.



### Reskinning

Many of the classes in other games are not present here. That's because it's highly encouraged to take one of the seven base classes and to "reskin" the class by changing the flavor text, giving alternate explanations to how and why certain class traits work, and make cosmetic changes to the traits themselves to emulate other character archetypes out there.

Below is a list of suggestions as starting points or even drop-in replacements for some classes you may be looking for:



##### Table 12: Class Equivalents

| Archetype        | Class   |
|:-----------------|:--------|
| Arcane Trickster | Jack    |
| Assassin         | Thief   |
| Barbarian        | Warrior |
| Bard             | Jack    |
| Battle Master    | Dwarf   |
| Druid            | Cleric  |
| Monk / Mystic    | Warrior |
| Paladin          | Dwarf   |
| Psion / Adept    | Mage    |
| Ranger           | Elf     |
| Sorcerer         | Mage    |
| Shaman           | Cleric  |
| Warlock          | Mage    |


### Multi-classing

A class is chosen at character creation, and as the character gains levels, the classes may offer new things to do. For simplicity's sake, a character may not change levels, but there are certain classes, namely the various racial martial archetypes, which effectively function as multi-class options, as they borrow abilities from two other classes.


## Cleric


The cleric is a holy servant, on a mission. Clerics cast divine magic, largely dealing with healing, protection, and channeling holy light to cast out the legions of the dead. Whether acting as an agent of a religious order, or travelling in search of enlightenment or penance, or simply filling a percieved need, clerics strive to boost others and to drive off the effects of evil magics wherever they go.


### Cleric Traits


##### Table 13: Cleric Traits

|                          |                                          |
|:-------------------------|:-----------------------------------------|
| Hit dice                 | 1d8                                      |
| Starting Hit Points      | 4 + 1d8 + Con Bonus                      |
| Armor & Weapons          | Clubs, maces, and all armor and shields  |
| Saving Throw Proficiency | Wisdom, Charisma                         |
| Spell Save DC            | 8 + Proficiency bonus + Wis Bonus        |
| Turn Undead              | Turn away undead within 30'              |
| Divine Casting           | Memorize 1 spell per slot                |
| Scroll Use               | Can cast scrolls from their spell list   |
| Smite                    | +1d8 to damage on attack action          |
| Destroy Undead           | Low-HD undead destroyed on turn          |



#### Trait: Turn Undead

As an action, a cleric may rebuke any undead creatures in a 30' radius. Any affected undead creatures must make a wisdom save or the must flee and cannot move closer to the cleric. The DC for the save is 10 + the cleric's charisma bonus. The DC increases by 1 upon gaining 3rd level, and again on levels 5, 7, 10, and 13.



#### Trait: Divine Spellcasting

Beginning at 2nd level, a cleric can cast divine spells. Each day the cleric can memorize a number of spells equal to the number of spell slots for that tier, from the entire divine spell list.



#### Trait: Scroll Use

A cleric can cast a divine spell from a scroll without memorizing the spell or expending a spell slot. Doing so destroys the scroll. The mage must make an wisdom check with proficiency against a DC 10 + spell tier. Failing causes the casting to fail. If the spell is of the level the cleric can memorize and cast normally, the check automatically succeeds.




#### Trait: Smite

Beginning at 4th level, a cleric can channel divine power into a single attack roll per turn, granting 1d8 additional damage on a hit. An extra 1d8 of damage is gained at 8th and 12th level.

##### Table 14: Cleric Abilities by Level and Spell Slots per Tier

| **Level** | Hit Dice | Proficiency Bonus | 1st | 2nd | 3rd | 4th | 5th | 6th | Feature                  |
|:----------|:---------|:------------------|:----|:----|:----|:----|:----|:----|:-------------------------|
| 1         | 1d8      | +2                | -   | -   | -   | -   | -   | -   | Turn Undead DC 10 + Cha  |
| 2         | 2d8      | +2                | 1   | -   | -   | -   | -   | -   | Divine Spellcasting      |
| 3         | 3d8      | +2                | 2   | -   | -   | -   | -   | -   | Turn Undead DC 11 + Cha  |
| 4         | 4d8      | +2                | 2   | 1   | -   | -   | -   | -   | Smite 1d8                |
| 5         | 5d8      | +3                | 2   | 2   | -   | -   | -   | -   | Turn Undead DC 12 + Cha  |
| 6         | 6d8      | +3                | 2   | 2   | 1   | -   | -   | -   | Destroy Undead 1 HD      |
| 7         | 7d8      | +3                | 2   | 2   | 2   | -   | -   | -   | Turn Undead DC 13 + Cha  |
| 8         | 8d8      | +3                | 3   | 2   | 2   | 1   | -   | -   | Smite 2d8                |
| 9         | 9d9      | +4                | 3   | 2   | 2   | 2   | -   | -   | Destroy Undead 2 HD      |
| 10        | 10d8     | +4                | 3   | 3   | 2   | 2   | 1   | -   | Turn Undead DC 14 + Cha  |
| 11        | 10d8+2   | +4                | 3   | 3   | 2   | 2   | 2   | -   | Destroy Undead 4HD       |
| 12        | 10d8+4   | +4                | 4   | 3   | 3   | 2   | 2   | 1   | Smite 3d8                |
| 13        | 10d8+6   | +5                | 4   | 3   | 3   | 2   | 2   | 2   | Turn Undead DC 15 + Cha  |


 
## Dwarf


Dwarven armies have gained their sterling reputation through constant warfare with the 
underground threats, along with their own spin on the cleric specialized for warfare: the 
warpriest. These are pracitioners of prayer and melee combat, and can provide vital support to 
the front lines in ways clerics cannot.

### Dwarf Traits


##### Table 15: Dwarf Traits

|                          |                                                                  |
|:-------------------------|:-----------------------------------------------------------------|
| Hit dice                 | 1d8                                                              |
| Starting Hit Points      | 4 + 1d8 + Con Bonus                                              |
| Armor & Weapons          | All melee weapons, all armor and shields                         |
| Saving Throw Proficiency | Constitution, Wisdom                                             |
| Spell Save DC            | 8 + Proficiency bonus + Wis Bonus                                |
| Lay on Hands             | 1d8/level healing per day                                        |
| Smite                    | +1d8 to damage on attack action                                  |
| Divine Spellcasting      | Memorize 1 spell per slot                                        |
| Inspire Courage          | Allies within radius have advantage on saving throws |
| Combat Maneuver          | Gain a warrior's combat maneuver                                 |



#### Trait: Lay on Hands

Each day, a dwarf has a pool of healing dice equal to their level. As a reaction, they can spend these dice at any time to heal themselves or anyone they can touch within 5'. That character is healed of 1d8 damage per die spent. Any number of dice may be spent per reaction, provided they are still available.




#### Trait: Smite

Beginning at 2nd level, a dwarf can channel divine power into a single attack roll per turn, granting 1d8 additional damage on a hit. An extra 1d8 of damage is gained at 5th, 8th and 11th level.




#### Trait: Divine Spellcasting

Beginning at 2nd level, a dwarf can cast divine spells. Each day the dwarf can memorize a number of spells equal to the number of spell slots for that tier, from the entire divine spell list.




#### Trait: Inspire Courage

Beginning at 4th level, a dwarf can use their action to give allies within a 5' radius advantage on one attack roll and one saving throw until the start of your next turn. This radius increases to 10' at 7th level, and to 15' at 13th level.




#### Trait: Combat Maneuver

Beginning at 6th level, a dwarf can gain a warrior's combat maneuver from Table 22. They may select another combat maneuver to learn at 9th and 11th levels. 

##### Table 16: Dwarf Abilities by Level and Spell Slots per Tier

| **Level** | Hit Dice | Proficiency Bonus | 1st | 2nd | 3rd | 4th | Feature                         |
|:----------|:---------|:------------------|:----|:----|:----|:----|:--------------------------------|
| 1         | 1d8      | +2                | -   | -   | -   | -   | Lay on Hands                    |
| 2         | 2d8      | +2                | -   | -   | -   | -   | Smite 1d8                       |
| 3         | 3d8      | +2                | 1   | -   | -   | -   | Divine Spellcasting             |
| 4         | 4d8      | +2                | 2   | -   | -   | -   | Inspire Courage 5'              |
| 5         | 5d8      | +3                | 2   | -   | -   | -   | Smite 2d8                       |
| 6         | 6d8      | +3                | 2   | 1   | -   | -   | Combat Maneuver                 |
| 7         | 7d8      | +3                | 2   | 2   | -   | -   | Inspire Courage 10'             |
| 8         | 8d8      | +3                | 2   | 2   | -   | -   | Smite 3d8                       |
| 9         | 9d8      | +4                | 2   | 2   | 1   | -   | Additional Combat Maneuver      |
| 10        | 10d8     | +4                | 2   | 2   | 2   | -   |                                 |
| 11        | 10d8+3   | +4                | 2   | 2   | 2   | -   | Smite 4d8                       |
| 12        | 10d8+6   | +4                | 3   | 2   | 2   | 1   | Additional Combat Maneuver      |
| 13        | 10d8+9   | +5                | 3   | 2   | 2   | 2   | Inspire Courage 15'             |



 
## Elf


The elves have developed their own elegant style of combat, dancing gracefully among enemies, twin blades twirling, along with a canny arsenal of acrane magic to augment their combat. The elite among them are given the title of bladesinger.



### Elf Traits


##### Table 17: Elf Traits

|                            |                                          |
|:---------------------------|:-----------------------------------------|
| Hit dice                   | 1d6                                      |
| Starting Hit Points        | 4 + 1d6 + Con Bonus                      |
| Armor & Weapons            | Swords, bows, light weapons, light armor |
| Saving Throw Proficiency   | Constitution, Wisdom                     |
| Spell Save DC              | 8 + Proficiency bonus + Int Bonus        |
| Spellbook                  | 2 spells known, + 1 per level gained     |
| Two Weapon Fighting        | Gain the warrior combat maneuver         |
| Additional Combat Maneuver | Pick another warrior combat maneuver     |
| Weapon Mastery             | Extra die of weapon damage               |



#### Trait: Spellbook

Elves start with a spellbook. That spellbook has 2 spells in it. An elf can learn an effectively infinite number of spells by adding them to the book. Spells can be added by finding other spellbooks and scrolls and adding the spells contained in them to their own spellbook. Doing so from a scroll destroys the scroll.

Spells can be memorized from the spellbook. An elf can memorize 1 spell per half their level + their intelligence bonus each day. These spells are cast using the spell slot.




#### Trait: Two Weapon Fighting

Elves start having learned the warrior's Two weapon fighting combat maneuver. Once per attack action, if holding a light weapon in your off-hand, you may make an additional attack roll with that weapon at disadvantage. You off-hand is the hand not holding the weapon used for the regular attack rolls.




#### Trait: Additional Combat Maneuver

Upon reaching 5th level, an elf can gain a warrior's combat maneuver from Table 22. They may select another combat maneuver to learn at 9th and 13th levels. 




#### Trait: Weapon Mastery

Upon reaching 6th and 10th level, an elf may select one of the following categories of weapon: Swords, spears, clubs, staves, daggers, or bows. Attacks with that weapon do an extra die of damage. For each additional mastery gained, you may select to either gain mastery in a new category of weapon, or to stack the effect on an already mastered category for yet another die of damage.

##### Table 18: Elf Abilities by Level and Spell Slots per Tier

| **Level** | Hit Dice | Proficiency Bonus | 1st | 2nd | 3rd | 4th | Feature                        |
|:----------|:---------|:------------------|:----|:----|:----|:----|:-------------------------------|
| 1         | 1d6      | +2                | 1   | -   | -   | -   | Spellbook, Two Weapon Fighting |
| 2         | 2d6      | +2                | 1   | -   | -   | -   |                                |
| 3         | 3d6      | +2                | 2   | -   | -   | -   |                                |
| 4         | 4d6      | +2                | 2   | -   | -   | -   |                                |
| 5         | 5d6      | +3                | 2   | 1   | -   | -   | Additional Combat Maneuver     |
| 6         | 6d6      | +3                | 2   | 1   | -   | -   | Weapon Mastery                 |
| 7         | 7d6      | +3                | 2   | 2   | -   | -   |                                |
| 8         | 8d6      | +3                | 2   | 2   | -   | -   |                                |
| 9         | 9d6      | +4                | 2   | 2   | 1   | -   | Additional Combat Maneuver     |
| 10        | 10d6     | +4                | 2   | 2   | 1   | -   | Weapon Mastery                 |
| 11        | 10d6+2   | +4                | 2   | 2   | 2   | -   |                                |
| 12        | 10d6+4   | +4                | 3   | 2   | 2   | -   |                                |
| 13        | 10d6+6   | +5                | 3   | 2   | 2   | 1   | Additional Combat Maneuver     |


 
## Jack


We all know that person who can take apart machinery and put it back together, plays multiple musical instruments, binds their own books by hand, and practives multiple martial arts. That person would be a jack.

Jacks are, as their name suggest, jacks of all trades. They are competent fighters, being proficient in many weapons and can wear some armor, they have the skills of a thief, and the spells of a mage. They can do none of these these as well as the specialists can, but Jacks are versatile enough to blend into any party and fill the gaps of any role needed.

### Jack Traits


##### Table 19: Jack Traits

|                          |                                                  |
|:-------------------------|:-------------------------------------------------|
| Hit dice                 | 1d6                                              |
| Starting Hit Points      | 4 + 1d6 + Con Bonus                              |
| Armor & Weapons          | All one-handed weapons, crossbows, light weapons and armors |
| Saving Throw Proficiency | Dexterity, Constitution                          |
| Jack Skills              | Stealth, lockpick tools, perception, climbing, disarming traps, and sleight of hand proficiency  |
| Lucky                    | Reroll 1's on any ability check once             |
| Spellbook                | 2 spells known, + 1 per level gained             |
| Scroll Use               | Can cast scrolls or copy scrolls from their spell list   |
| Deciphering Languages    | Gain proficiency in deciphering languages        |
| Aid                      | Grant advantage to an ally's next roll           |      



#### Trait: Jack Skills
Regardless of background, all jacks are proficient in activities involving stealth, lockpick tools, perception, climbing, disarming traps, and sleight of hand, and rolling for initiative.




#### Trait: Lucky
When you roll a 1 on the d20 for an ability check, you can reroll the die and must use the new roll.



#### Trait: Spellbook

Starting at 2nd level jacks gain a spellbook. That spellbook has 2 spells in it. A jack can learn an effectively infinite number of spells by adding them to the book. Spells can be added by finding other spellbooks and scrolls and adding the spells contained in them to their own spellbook. Doing so from a scroll destroys the scroll.

Spells can be memorized from the spellbook. A jack can memorize 1 spell per level + their intelligence bonus each day. These spells are cast using the spell slot.



#### Trait: Scroll Use

A Jack can cast an arcane spell from a scroll without memorizing the spell or expending a spell slot. Doing so destroys the scroll. The jack must make a charisma check with proficiency against a DC 10 + spell tier. Failing causes the casting to fail. If the spell is of the level the jack can memorize and cast normally, the check automatically succeeds.



#### Trait: Deciphering Languages
At 6th level a jack gains proficiency in deciphering languages.




#### Trait: Aid
At 3rd level, a jack grant advantage to an ally within 30' once per day as a reaction. They can grant aid an additional time per day at 7th level, and again at 11th level.

##### Table 20: Jack Abilities by Level and Spell Slots by Tier

| **Level** | Hit Dice | Proficiency Bonus | 1st | 2nd | 3rd | 4th | Feature               |
|:----------|:---------|:------------------|:----|:----|:----|:----|:----------------------|
| 1         | 1d6      | +2                | -   | -   | -   | -   | Jack Skills, Lucky    | 
| 2         | 2d6      | +2                | 1   | -   | -   | -   | Spellbook, Scroll Use |
| 3         | 3d6      | +2                | 2   | -   | -   | -   | Aid 1x/day            |       
| 4         | 4d6      | +2                | 2   | -   | -   | -   |                       |
| 5         | 5d6      | +3                | 2   | 1   | -   | -   |                       |
| 6         | 6d6      | +3                | 2   | 2   | -   | -   | Deciphering Languages |
| 7         | 7d6      | +3                | 3   | 2   | -   | -   | Aid 2x/day            |
| 8         | 8d6      | +3                | 3   | 2   | 1   | -   |                       |
| 9         | 9d6      | +4                | 3   | 2   | 2   | -   |                       |
| 10        | 10d6     | +4                | 3   | 3   | 2   | -   |                       |
| 11        | 10d6+2   | +4                | 4   | 3   | 2   | 1   | Aid 3x/day            |
| 12        | 10d6+4   | +4                | 4   | 3   | 2   | 2   |                       |
| 13        | 10d6+6   | +5                | 4   | 3   | 3   | 2   |                       |


 
## Mage


Whether learned through dedicated study, or granted by a supernatural entity, or just naturally gifted, a mage is a person who can wield arcane energy. They gather spells in a book, and can use them to cast rituals, or can memorize the spells to cast them in the heat of battle. The variety of spells they can cast is only limited by the extent of arcane knowledge and the size of the book they are willing to lug around.

### Mage Traits


##### Table 21: Mage Traits

|                          |                                       |
|:-------------------------|:--------------------------------------|
| Hit dice                 | 1d4                                   |
| Starting Hit Points      | 4 + 1d4 + Con Bonus                   |
| Armor & Weapons          | Daggers and staves                    |
| Saving Throw Proficiency | Intelligence, Wisdom                  |
| Spell Save DC            | 8 + Proficiency bonus + Int Bonus     |
| Spellbook                | 2 spells known, + 1 per level gained  |
| Ritual Casting           | Cast spells from spellbook for free, but it takes 10 minutes |
| Scroll Use               | Can cast or copy scrolls from their spell list |



#### Trait: Spellbook

Mages start with a spellbook. That spellbook has 2 spells in it. A mage can learn an effectively infinite number of spells by adding them to the book. Spells can be added by finding other spellbooks and scrolls and adding the spells contained in them to their own spellbook. Doing so from a scroll destroys the scroll.

Spells can be memorized from the spellbook. A mage can memorize 1 spell per level + their intelligence bonus each day. These spells are cast using the spell slot.



#### Trait: Ritual Casting

A mage can cast any spell from their spellbook without memorizing it or expending a spell slot by casting it as a ritual. Doing so makes the spell take a minimum of 10 minutes to cast.



#### Trait: Scroll Use

A mage can cast an arcane spell from a scroll without memorizing the spell or expending a spell slot. Doing so destroys the scroll. The mage must make an intelligence check with proficiency against a DC 10 + spell tier. Failing causes the casting to fail. If the spell is of the level the mage can memorize and cast normally, the check automatically succeeds.


##### Table 22: Mage Abilities by Level and Spell Slots by Tier

| **Level** | Hit Dice | Proficiency Bonus | 1st | 2nd | 3rd | 4th | 5th | 6th | 7th | Feature |
|:----------|:---------|:------------------|:----|:----|:----|:----|:----|:----|:----|:--------|
| 1         | 1d4      | +2                | 1   | -   | -   | -   | -   | -   | -   | Spellbook, Ritual Casting, Scroll Use |
| 2         | 2d4      | +2                | 2   | -   | -   | -   | -   | -   | -   ||
| 3         | 3d4      | +2                | 2   | 1   | -   | -   | -   | -   | -   ||       
| 4         | 4d4      | +2                | 2   | 2   | -   | -   | -   | -   | -   ||
| 5         | 5d4      | +3                | 2   | 2   | 1   | -   | -   | -   | -   ||
| 6         | 6d4      | +3                | 2   | 2   | 2   | -   | -   | -   | -   ||
| 7         | 7d4      | +3                | 3   | 2   | 2   | 1   | -   | -   | -   ||
| 8         | 8d4      | +3                | 3   | 2   | 2   | 2   | -   | -   | -   ||
| 9         | 9d4      | +4                | 3   | 3   | 2   | 2   | 1   | -   | -   ||
| 10        | 10d4     | +4                | 3   | 3   | 2   | 2   | 2   | -   | -   ||
| 11        | 10d4+1   | +4                | 4   | 3   | 3   | 2   | 2   | 1   | -   ||
| 12        | 10d4+2   | +4                | 4   | 3   | 3   | 2   | 2   | 2   | -   ||
| 13        | 10d4+3   | +5                | 4   | 4   | 3   | 3   | 2   | 2   | 1   ||



 
## Thief


A thief is an expert treasure hunter, well versed in the trade 
of dungeoneering. Thieves specialize in evading detection, 
getting into protected areas, and taking advantage of surprise. 
This includes escavators, cutthroats, monster hunters, and cat 
burglars. Basically anyone with devious insight and deft skill 
can fill the role of the thief.

### Thief Traits


##### Table 23: Thief Traits

|                          |                                     |
|:-------------------------|:------------------------------------|
| Hit dice                 | 1d6                                 |
| Starting Hit Points      | 4 + 1d6 + Con Bonus                 |
| Armor & Weapons          | Crossbows, light weapons and armors |
| Saving Throw Proficiency | Dexterity, Charisma                 |
| Backstab                 | 2d6 + 1d6 every third level bonus damage when you have advantage |
| Thief Skills             | Stealth, lockpick tools, perception, climbing, disarming traps, and sleight of hand proficiency |
| Skill Mastery            | Double proficiency bonus in a selected thief skill |
| Deciphering Languages    | Gain proficiency in deciphering languages     |
| Scroll Use               | Cast scroll with a Cha check DC 10+spell tier |



#### Trait: Backstab
When a thief either attacks on an initiative round, or attacks with advantage, they add 2d6 to their damage roll. The damage increases by an additional 1d6 for every third level gained.



#### Trait: Thief Skills
Regardless of background, all thieves are proficient in activities involving stealth, lockpick tools, perception, climbing, disarming traps, and sleight of hand, and rolling for initiative.



#### Trait: Skill Mastery
For each four levels gained, you may select one thief skill to gain expertise in. The proficiency bonus is applied twice to ability rolls for that activity. You may only select a particular skill for expertise once: expertise cannot apply to the same skill multiple times.



#### Trait: Deciphering Languages
At 6th level a thief gains proficiency in deciphering languages and may gain skill mastery in it at later levels.



#### Trait: Scroll Use
At 8th Level a Thief can attempt to cast scrolls of spells as an action. To do so requires a Charisma check DC 10 + tier of the spell. At 10th level they are proficient in scroll use and so may apply their proficiency bonus to the check.

##### Table 24: Thief Abilities by Level

| **Level** | Hit Dice | Proficiency Bonus | Feature                    |
|:----------|:---------|:------------------|:---------------------------|
|1          | 1d6      | +2                | Backstab 2d6, Thief Skills | 
|2          | 2d6      | +2                |                            |
|3          | 3d6      | +2                |                            |
|4          | 4d6      | +2                | Backstab 3d6               | 
|5          | 5d6      | +3                | Skill mastery              |
|6          | 6d6      | +3                | Deciphering Languages      |
|7          | 7d6      | +3                | Backstab 4d6               | 
|8          | 8d6      | +3                | Scroll Use                 |
|9          | 9d6      | +4                | Skill mastery              |
|10         | 10d6     | +4                | Backstab 5d6               | 
|11         | 10d6+2   | +4                | Scroll Use Proficiency     |
|12         | 10d6+4   | +4                |                            |
|13         | 10d6+6   | +5                | Backstab 6d6, Skill Mastery|


 
## Warrior

A warrior is a person who fights professionally, usually as part of a 
career track that involves gaining knighthood and feudal lordship 
through service in combat.
 This includes sellswords, squires, soldiers, barbarians, and 
tournament fighters.

### Warrior Traits


##### Table 25: Warrior Traits

|                          |                                           |
|:-------------------------|:------------------------------------------|
| Hit dice                 | 1d10                                      |
| Starting Hit Points      | 4 + 1d10 + Con Bonus                      |
| Armor & Weapons          | All armor, weapons, and shields           |
| Saving Throw Proficiency | Strength, Deterity                        |
| Combat Maneuver          | 2 at 1st level, +1 every 3rd level gained |
| Weapon Mastery           | Extra die of weapon damage                |



#### Trait: Combat Maneuvers

A warrior starts having learned two different combat 
manuevers. For every three levels gained, you may 
select one more combat maneuver to learn. Each maneuver 
may only be learned once, except for Extra Attack, 
which may be learned multiple times. Each maneuver may 
only be activated once per turn. For example, you may 
not use Charge on multiple attacks in a round.



#### Trait: Weapon Mastery

For every four levels gained, you may select one of the following categories of weapon: Swords, spears, clubs, staves, daggers, or bows. Attacks with that weapon do an extra die of damage. For each additional mastery gained, you may select to either gain mastery in a new category of weapon, or to stack the effect on an already mastered category for yet another die of damage.



##### Table 26: Combat Maneuvers

| Maneuver           | Description |
|:-------------------|:------------|
| Charge             | Once per Attack action, if you used your full movement to approach an enemy, your next attack roll has advantage. |
| Set                | When an enemy uses full movement to attack, you may use a rection to strike first with advantage before the enemy attack. |
| Extra Attack       | Using your action to attack involves an extra attack roll. This may be taken more than once, with each time giving an additional attack roll. |
| Smash              | Once per attack action, you may elect for your next attack roll to have disadvantage, and you may apply your strength score (note: not strength bonus, the *strength score*) to the damage roll in addition to any normal strength and magic bonuses. |
| Parry              | You may forgo one attack roll on your turn to automatically cause the next enemy attack roll targeting you to miss. The effect lasts until the start of your next turn. If you have extra attacks, you may forgo additional attack rolls to cause more enemy attack rolls to miss.  |
| Disarm              | Once per attack action, you may elect for your next attack roll against a weapon-weilding opponent to have disadvantage, and  on a successful hit, the opponent takes no damage from the attack, but instead drops their weapon.  
| Two weapon fighting | Once per attack action, if holding a light weapon in your off-hand, you may make an additional attack roll with that weapon at disadvantage. You off-hand is the hand not holding the weapon used for the regular attack rolls.

##### Table 27: Warrior Abilities by Level

| **Level** | Hit Dice | Proficiency Bonus | Feature                    |
|:----------|:---------|:------------------|:---------------------------|
|1          | 1d10     | +2                | 2 Combat Maneuvers         | 
|2          | 2d10     | +2                |                            |
|3          | 3d10     | +2                |                            |
|4          | 4d10     | +2                | Additional combat maneuver |
|5          | 5d10     | +3                | Weapon Mastery             |
|6          | 6d10     | +3                |                            |
|7          | 7d10     | +3                | Additional combat maneuver |
|8          | 8d10     | +3                |                            |
|9          | 9d10     | +4                | Weapon Mastery             |
|10         | 10d10    | +4                | Additional combat maneuver |
|11         | 10d10+3  | +4                |                            |
|12         | 10d10+6  | +4                |                            |
|13         | 10d10+9  | +5                | Additional combat maneuver, Weapon Mastery |

# Equipment

##### Table 28: Weapons

|              | Cost | Damage | Type                      | Range |
|:-------------|:-----|:-------|:--------------------------|:------|
| Dagger       | 3    | 1d4    | Light, thrown             | Short |
| Hand Axe     | 3    | 1d4    | Light, thrown             | Short |
| Mace         | 5    | 1d6    | Club, light               |       |
| Staff        | 5    | 1d6    | Club, two-handed          |       |
| Sword        | 10   | 1d6    |                           |       |
| Battle Axe   | 7    | 1d6    |                           |       |
| Morning Star | 6    | 1d6    | Club                      |       |
| Flail        | 8    | 1d8    | Club, two-handed          |       |
| Spear        | 1    | 1d4    | Light, thrown             | Short |
| Polearm      | 7    | 1d6    |                           |       |
| Halberd      | 7    | 1d8    | Two-handed                |       |
| Claymore     | 15   | 1d8    | Two-handed                |       |
| Lance        | 4    | 1d10   | Mounted only              |       |
| Pike         | 5    | 1d6    | Thrown                    | Short |
| Short Bow    | 25   | 1d6    | Light, ranged, two-handed | Long  | 
| Composite Bow| 50   | 1d8    | Ranged, two-handed        | Long  | 
| Hand Crossbow| 50   | 1d4    | Ranged                    | Short |
|Light Crossbow| 15   | 1d6    | Light, ranged, two-handed | Short | 
|Heavy Crossbow| 25   | 1d8    | Ranged, two-handed        | Long  |


##### Table 29: Ammunition

|                       | Cost |
|:----------------------|:-----|
| Quiver of 20 Arrows   | 10   |
| Case with 30 Quarrels | 10   |
| 20 Arrows/30 Quarrels | 5    |
| Silver Tipped Arrow   | 5    |


##### Table 30: Armor

|                       | Type  | Cost | AC             |
|:----------------------|:------|:-----|:---------------|
| Leather Armor         | Light | 15   | 12 + Dex Bonus |
| Chain-type Mail       |       | 30   | 14 + Dex Bonus |
| Plate Mail            |       | 50   | 16             |
| Helmet                | Light | 10   | 11 + Dex Bonus |
| Shield                |       | 10   | +2             |
| Barding (Horse Armor) |       | 150  | 14             |


##### Table 31: Transport

|                       | Cost   |
|:----------------------|:-------|
| Mule                  | 20     |
| Draft Horse           | 30     |
| Light Horse           | 40     |
| Warhorse, Medium      | 100    |
| Warhorse, Heavy       | 200    |
| Saddle                | 25     |
| Saddle Bags           | 10     |
| Cart                  | 100    |
| Wagon                 | 200    |
| Raft                  | 40     |
| Small Boat            | 100    |
| Small Merchant Ship   | 5,000  |
| Large Merchant Ship   | 20,000 |
| Small Galley          | 10,000 |
| Large Galley          | 30,000 |


##### Table 32: Sundries

|                             | Cost |
|:----------------------------|:-----|
| 50’ of Rope                 | 1    |
| 10’ Pole                    | 1    |
| 12 Iron Spikes              | 1    |
| Small Sack                  | 1    |
| Large Sack                  | 2    |
| Leather Back Pack           | 5    |
| Water/Wine Skin             | 1    |
| 6 Torches                   | 1    |
| Lantern                     | 10   |
| Flask of Oil                | 2    |
| 3 Stakes & Mallet           | 3    |
| Steel Mirror                | 5    |
| Silver Mirror, Small        | 15   |
| Wooden Holy Symbol          | 2    | 
| Silver Holy Symbol          | 25   | 
| Holy Water/Vial             | 25   |
| Wolvesbane, bunch           | 10   |
| Belladonna, bunch           | 10   |
| Garlic, bud                 | 5    |
| Wine, quart                 | 1    |
| 1 week rations for 1 person | 5    |



# Magic


##### Table 33: Arcane Spell List


| Tier 1 Spells          | Description |
|:------------------------------|:------------|
| Charm Person                  | Wis save or the target in short range is your friend for 1 hour
| Comprehend Languages          | You can understand and read language within touch that isn't magic or encrypted for 1 hour
| Darkness                      | A small touched object emits darkness in 20' radius for 1 hour 
| Detect Magic                  | See magical auras within short range for 10 minutes 
| Floating Disc                 | Summon a 3' disk that holds 500lbs for 1 hour
| Identify                      | Learn one property of a touched magic item
| Light                         | A small touched object glows in 20' radius for 1 hour
| Magic Missile                 | Missile auto-hits targets for 1d4+1 damage, +2 missiles per 5 caster levels
| Prestidigitation              | Throw your voice, make lights, and other theatrical effects for 1 hour
| Protection from Evil and Good | Supernatural creatures can't charm, frighten, possess target, have disadvantage vs touched target
| Shield                        | Reaction, you have +4 AC, blocks magic missiles
| Sleep                         | 4d8 HP of short range monsters go to sleep



| Tier 2 Spells | Description |
|:---------------------|:------------|
| Arcane Lock          | Any touched lock or door can't be opened except by caster, forever until dispelled |
| Continual Flame      | Create a harmless, cold flame that lasts until dispelled |
| Detect Evil and Good | Know whether supernatural creatures or objects are in short range for 10 minutes |
| See Invisibility     | See invisible things in short range |
| Entangle             | Control all ropes within short range to untie, loop, unloop, coil, uncoil, or tie up people, Str save escapes |
| Detect Thoughts      | Detect surface thoughts of one person in short range for 1 min |
| Invisibility         | One touched target can't be seen for 1 min or until they attack or cast a spell |
| Knock                | One touched locked object or magical lock is no longer locked |
| Levitate             | One touched target can lift straight up in the air 20'/round for 6 rounds + 1/lvl, carrying up to 200lbs |
| Locate Object        | Know where one specific object is within short range |
| Mirror Image         | Make 1d4 body doubles surrounding you who take your place when attacked and disappear after being hit |
| Web                  | Spray webs in 10' area that blocks movement. Caught creatures must make a Str save to break free | 


##### Table 33: Arcane Spell List (Cont'd)



| Tier 3 Spells | Description |
|:---------------------|:------------|
| Clairvoyance         | See through eyes of any short range creature for 1 min, may change creatures each round |
| Dispel Magic         | Int check DC 8+spell level to destroy 20' radius spell effect |
| Fireball             | 20'radius must dex save or take 1d6/level damage, half damage if successful |
| Fly                  | For 1d6+1/level rounds touched target can fly with 120' fly speed |
| Haste                | Creatures in 30' radius move double speed and take two actions a round for 3 rounds |
| Hold person          | Up to 4 humanoids within 120' must Wis save or be paralyzed |
| Darkvision           | Touch target sees short range in the dark for 1 day |
| Greater Invisibility | 10' radius of people can't be seen until they leave the area of effect, attack, or cast a spell |
| Lightning Bolt       | Make 60' line of lightning, Dex save or 1d6 damage/level, half damage on success |
| Greater Protection from Evil and Good |  Protection from Evil and Good in 10' radius |
| Water Breathing      | Touched target can breathe underwater for 1 day |



| Tier 4 Spells | Description |
|:---------------------|:------------|
| Arcane Eye           | Make a floating eyeball for 1 hour you can see through |
| Bestow Curse         | Touched target must Cha Save or get one category of rolls at disadvantage (caster's choice) | 
| Confusion            | Make 30' radius area of confusion, creatures within cannot tell friend from foe |
| Dimension Door       | Short range target must Dex save or be transported up to 360' away |
| Plant Growth         | Enlarge 3000' sq of plants to block passage |
| Hallucinatory Terrain| 240' radius of land becomes an illusory terrain feature until touched or dispelled |
| Ice Storm            | Creatures in a 20' radius dex save or take 1d8 damage, half on Dex save |
| Polymorph            | Change yourself into the form of a creature weaker than you for 1 hour |
| Remove Curse         | Touched target is cured of the effects of Bestow Curse |
| Wall of Fire         | Make a 1200' sq wall of fire, touch causes 1d6 damage, Con save to pass through |
| Wall of Ice          | Make a 1200' sq wall of icy blast, touch causes 1d6 damage, Con save to pass through | 


##### Table 33: Arcane Spell List (Cont'd)



| Tier 5 Spells | Description |
|:---------------------|:------------|
| Animate Dead         | Create 1HD/level of 1HD skeletons or 3HD zombies in short range |
| Cloudkill            | Create 20' radius cloud for 10 min, each round creatures inside Con save or 5d6 damage, half on success |
| Conjure Elemental    | Summon an elemental, concentrate to maintain control or to dismiss |
| Contact Other Plane  | Once a month, ask an immortal any question, each question Int save vs DC 5 or go insane |
| Transmute Mud and Stone| Liquefy 3000' sq of mud or turn same amount of mud to stone for 3d6 days |
| Feeblemind           | Target must Int save or have intelligence reduced to 1, may retry save each month |
| Hold Monster         | Up to 4 living creatures in 60' radius must Wis save or be paralyzed |
| Magic Jar            | Put your soul in a vessel to "soul swap" and possess person within 120' on a failed Cha save |
| Passwall             | Put a 10' deep hole in stone short range for 30 min |
| Telekinesis          | Move 20lbs/level 20'/round for 6 rounds |
| Teleport             | Travel any destination in the same plane, if unfamiliar, Int Save DC 10 or land 1d10x10' away |
| Wall of stone        | Create 500' sq, 2' thick stone wall until dispelled or broken, toppling inflicts 10d10 dmg



| Tier 6 Spells | Description |
|:---------------------|:------------|
| Antimagic Field      | Barrier around self negates all magic |
| Circle of Death      | 4d8 HD of creatures within 60' radius die, lowest HD creatures first |
| Disintegrate         | A creature or nonmagical item is destroyed |
| Geas | Short range target must Wis save or be forced to do a task, 1 level of exhaustion/week not doing said task, *or* remove a geas |
| Control Water        | Raise or lower 10,000' sq of water to half or double depth |
| Move Earth           | Make a 240' hole by moving earth up to 360' away over the course of an hour |
| Project Image        | Make an illusionary double of yourself you can cast spells from, but disappears when touched |
| Reincarnate          | Bring an ally within touch back to life in a new body of a random species |
| Flesh to Stone       | Target must Con save or become petrified *or* restore a petrified target to normal |
| Control Weather      | Make weather in the local area become rain, snow, fog, clear, high winds, or tornado while concentrating |


| Tier 7 Spells   | Description |
|:-----------------------|:------------|
| Delayed Blast Fireball | Create a small throwable gem that becomes a fireball between 1 and 60 rounds later, determined by the caster |
| Legend Lore            | Know a brief description about any person, place, or object |
| Power Word Stun        | Creature within 120ft with less than 70 HP is stunned and must Str save each round or stay stunned |
| Reverse Gravity        | Everything inside a 30' cube falls up |
| Instant Summons        | One familiar nonliving object weighing up to 50lbs from your home appears in your hand |
| Arcane Sword           | A glowing magical sword appears to attack enemies with caster's spell attack for 1d10 dmg for 1 round / level |
| Greater Teleport       | A touched nonliving object up to 50lbs teleports per the teleport spell |



##### Table 34: Divine Spell List



| Tier 1 Spells          | Description |
|:------------------------------|:------------|
| Cure Wounds                   | Touched creature is cured 1d6+1 HP *or* is healed from paralysis 
| Darkness                      | A small touched object emits darkness in 20' radius for 1 hour 
| Detect Evil and Good | Know whether supernatural creatures or objects are within 30' for 10 minutes
| Detect Magic                  | See short range magical auras for 10 minutes 
| Faerie Fire                   | Attacks against a short range creature / 5 caster levels get advantage for 1 round / caster level
| Inflict Wounds                | Touched creature takes 1d6+1 damage
| Light                         | A small touched object glows in 20' radius for 1 hour
| Protection from Energy        | Short range allies take half damage from one of acid, cold, fire, lightning, or thunder
| Protection from Evil and Good | Supernatural creatures can't charm, frighten, possess touched target, and have disadvantage vs touched target
| Purify Food and Drink         | Food and drinks for a dozen people are no longer poisoned

| Tier 2 Spells | Description |
|:---------------------|:------------|
| Bane                 | Short range creatures in a 20' radius get -1d4 to rolls for 1 hour
| Bless                | Short range creatures in a 20' radius get +1d4 to rolls for 1 hour
| Detect Evil and Good | Know whether supernatural creatures or objects are in short range for 10 min
| Find Traps           | See mechanical and magical traps glow blue for 10 min
| Heat Metal           | 1 short range held metal item per level does 1d4 damage each round for 6 rounds
| Hold person          | Up to 4 humanoids must Wis save or be paralyzed
| Silence              | A 30' radius is silent for 1 hour, target must Dex save or the effect will follow them
| Soeak with Animals   | You can have an intelligible conversation with one short range animal for 1 hour




| Tier 3 Spells | Description |
|:---------------------|:------------|
| Bestow Curse         | Touched target must Cha Save or get one category of rolls at disadvantage (caster's choice) 
| Blindness/Deafness   | Touched creature is either cured of or struck with either blindness or deafness for 1 minute
| Lesser Restoration   | Cure one nonmagical disease or poison from touched target
| Locate Object        | Know where one specific object is within short range
| Remove Curse         | Touched target is cured of the effects of Bestow Curse
| Shillelagh           | Make a touched weapon magical with +1d6 damage for 10 min
| Speak with the Dead  | One dead creature must answer three questions::::::

| Tier 4 Spells    | Description |
|:------------------------|:------------|
| Animate Dead            | create 1HD/level of 1HD skeletons or 3HD zombies in short range
| Dispel Magic         | Int check DC 8+spell level to destroy 20' radius spell effect
| Create or Destroy Water | Create for destroy 50 gallons of water
| Greater Cure Wounds     | Touched creature is cured 2d6+2 HP
| Greater Inflict Wounds  | Touched creature is damaged for 2d6+2 HP
| Greater Protection from Evil and Good | Protection from Evil and Good in a 10' radius
| Speak with Plants       | Have an intelligible telepathic conversation with plants, and they can do minor favors if able


##### Table 34: Divine Spell List (Cont'd)




| Tier 5 Spells  | Description |
|:----------------------|:------------|
| Commune               | Directly speak to your deity  and get direct answers to three questions once per month
| Create Food and Water | Make enough food to feed 12 people
| Dispel Evil and Good  | In short range, break charms, fear, possession, supernatural creatures have disadvantage, or spell attack vs supernatural creature is dismissed to their home plane
|Finger of Death        | A creature in short range must Con save or die
| Geas | Target within 30' must Wis save or be forced to a task, 1 level of exhaustion/week not doing said task, *or* remove a geas
| Insect Plague         | Summon a 30' radius swarm of insects which obscure vision and drive off low level creatures for 1 day
| Raise Dead            | Bring to life a humanoid dead for 1 day / caster level
| Superior Cure Wouds   | Touched creature is cured 3d6+3 HP
| Superior Inflict Wouds   | Touched creature is cured for 3d6+3 HP



| Tier 6 Spells | Description |
|:---------------------|:------------|
| Animate Objects      | 400lbs of objects in short range can move and are under control of the caster
| Anitlife Shell       | All life is pushed out and prevented from entering short range around you for conentration for 1 hour
| Find the Path        | For 1 hour / caster level see the path leading to a specific location
| Word of Recall       | Teleport yourself to your permanent home or sanctuary

# Open Game License

###### DESIGNATION OF PRODUCT IDENTITY

All artwork, logos, and presentation are product identity.
The names “ADHD Basic”
are product identity. All text in the following sections is
product identity: (none).

###### DESIGNATION OF OPEN GAME CONTENT

All text and tables not declared as product identity are Open
Game Content.

###### OPEN GAME LICENSE Version 1.0a
```
The following text is the property of Wizards of the Coast, Inc and is Copyright
2000 Wizards of the Coast, Inc (“Wizards”) All Rights Reserved

1 Definitions: (a)”Contributors” means the copyright and/or trademark owners who
have contributed Open Game Content; (b)”Derivative Material” means copyrighted
material including derivative works and translations (including into other computer
languages), potation, modification, correction, addition, extension, upgrade, im-
provement, compilation, abridgment or other form in which an existing work may
be recast, transformed or adapted; (c) “Distribute” means to reproduce, license, rent,
lease, sell, broadcast, publicly display, transmit or otherwise distribute; (d)”Open
Game Content” means the game mechanic and includes the methods, procedures,
processes and routines to the extent such content does not embody the Product
Identity and is an enhancement over the prior art and any additional content clearly
identified as Open Game Content by the Contributor, and means any work covered
by this License, including translations and derivative works under copyright law,
but specifically excludes Product Identity (e) “Product Identity” means product and
product line names, logos and identifying marks including trade dress; artefacts;
creatures characters; stories, storylines, plots, thematic elements, dialogue, inci-
dents, language, artwork, symbols, designs, depictions, likenesses, formats, poses,
concepts, themes and graphic, photographic and other visual or audio representa-
tions; names and descriptions of characters, spells, enchantments, personalities,
teams, personas, likenesses and special abilities; places, locations, environments,
creatures, equipment, magical or supernatural abilities or effects, logos, symbols,
or graphic designs; and any other trademark or registered trademark clearly identi-
fied as Product identity by the owner of the Product Identity, and which specifically
excludes the Open Game Content; (f) “Trademark” means the logos, names, mark,
sign, motto, designs that are used by a Contributor to identify itself or its products or
the associated products contributed to the Open Game License by the Contributor (g)
“Use”,”Used” or “Using” means to use, Distribute, copy, edit, format, modify, translate
and otherwise create Derivative Material of Open Game Content (h) “You” or “Your”
means the licensee in terms of this agreement

2 The License: This License applies to any Open Game Content that contains a notice
indicating that the Open Game Content may only be Used under and in terms of
this License You must affix such a notice to any Open Game Content that you Use
No terms may be added to or subtracted from this License except as described by
the License itself No other terms or conditions may be applied to any Open Game
Content distributed using this License

3 Offer and Acceptance: By Using the Open Game Content You indicate Your ac-
ceptance of the terms of this License

4 Grant and Consideration: In consideration for agreeing to use this License, the
Contributors grant You a perpetual, worldwide, royalty-free, non-exclusive license
with the exact terms of this License to Use, the Open Game Content

5 Representation of Authority to Contribute: If You are contributing original
material as Open Game Content, You represent that Your Contributions are Your
original creation and/or You have sufficient rights to grant the rights conveyed
by this License

6 Notice of License Copyright: You must update the COPYRIGHT NOTICE portion of
this License to include the exact text of the COPYRIGHT NOTICE of any Open Game
Content You are copying, modifying or distributing, and You must add the title,
the copyright date, and the copyright holder’s name to the COPYRIGHT NOTICE of
any original Open Game Content you Distribute

7 Use of Product Identity: You agree not to Use any Product Identity, including as an
indication as to compatibility, except as expressly licensed in another, independent
Agreement with the owner of each element of that Product Identity You agree
not to indicate compatibility or co-adaptability with any Trademark or Registered
Trademark in conjunction with a work containing Open Game Content except as
expressly licensed in another, independent Agreement with the owner of such
Trademark or Registered Trademark The use of any Product Identity in Open Game
Content does not constitute a challenge to the ownership of that Product Identity
The owner of any Product Identity used in Open Game Content shall retain all
rights, title and interest in and to that Product Identity

8 Identification: If you distribute Open Game Content You must clearly indicate
which portions of the work that you are distributing are Open Game Content
9 Updating the License: Wizards or its designated Agents may publish updated
versions of this License You may use any authorised version of this License to
copy, modify and distribute any Open Game Content originally distributed under
any version of this License

10 Copy of this License: You MUST include a copy of this License with every copy
of the Open Game Content You Distribute
11 Use of Contributor Credits: You may not market or advertise the Open Game
Content using the name of any Contributor unless You have written permission
from the Contributor to do so

12 Inability to Comply: If it is impossible for You to comply with any of the terms of
this License with respect to some or all of the Open Game Content due to statute,
judicial order, or governmental regulation then You may not Use any Open Game
Material so affected

13 Termination: This License will terminate automatically if You fail to comply
with all terms herein and fail to cure such breach within 30 days of becoming
aware of the breach All sublicenses shall survive the termination of this License

14 Reformation: If any provision of this License is held to be unenforceable, such
provision shall be reformed only to the extent necessary to make it enforceable

15 COPYRIGHT NOTICE
Open Game License v 1.0a Copyright 2000, Wizards of the Coast, Inc

System Reference Document 5.1 Copyright 2016,
Wizards of the Coast, Inc.; Authors Mike Mearls,
Jeremy Crawford, Chris Perkins, Rodney Thompson,
Peter Lee, James Wyatt, Robert J. Schwalb, Bruce R.
Cordell, Chris Sims, and Steve Townshend, based on
original material by E. Gary Gygax and Dave Arneson.

ADHD Basic Copyright 2022 Sean Wolcott

END OF LICENSE
```
