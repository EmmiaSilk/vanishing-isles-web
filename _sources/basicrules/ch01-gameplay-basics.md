---
layout: chapter
permalink: /sources/basicrules/gameplay-basics/
title: "Chapter 1: Gameplay Basics"

book: basicrules
pagetype: chapter
chapter: 01
---

## Common Stats
{:id="core-stats"}

The following common statistics apply to every player character in the game.
Each of these stats also have the potential to be modified by magical bonuses
or penalties, or by class-specific features.

### Combat Attributes
{:id="combat-attributes"}

A character’s core combat attributes are a set of values from which nearly all
other combat stats are derived. They are determined during character creation,
and can be permanently improved when reaching certain level thresholds. They
can may be temporarily improved using certain abilities.

A commoner’s combat attributes average out to +0, and a heroic character’s
combat attributes average out to +2 or +3.

Combat attributes can be damaged by certain kinds of attacks. When this happens,
the relevant attribute takes a penalty of -1 point for every 2 points of damage
taken to the attribute. If a core combat attribute is reduced to -5, it becomes
unusable, and the character ceases to be a player character until the stat
recovers.

*(For example, if the Accuracy stat takes 3 points  of damage, the attribute
takes a -1 penalty. If the attribute takes 4 points of damage, the attribute
takes a -2 penalty, and so on. If a player’s base Agility stat is +3 and they
take 16 points of Agility damage, their effective Agility stat is reduced to
-5 and the stat becomes unusable until they recover.)*

A character in the Vanishing Isles has the following core combat attributes:

* The **Accuracy** stat (Acu) is used in calculating Attack rolls.
* The **Might** stat (Mit) is used in calculating damage for weapon attacks and
in Fortitude saving throws.
* The **Affinity** stat (Afn) is used in calculating damage for magical
attacks, in Will saving throws, and in calculating the Special Guard stat.
* The **Agility** stat (Agi) is used in Reflex saving throws and the Physical
Guard stat.
* The **Vitality** stat (Vit) is used in calculating your hit point maximum and
in hit die rolls.
* The **Proficiency** stat (Prf) is used in calculating your Skill Point
maximum and in Initiative rolls.

### Hit Points
{:id="hit-points"}

A character's will to fight is measured by their **Hit Points**. Your hit
points start at your **Hit Point Maximum** and cannot be increased beyond it.
Your Hit Point Maximum is determined by your class and your Vitality stat,
increasing every level.

Your current Hit Points are reduced when you take damage and increase when you
are healed. They cannot be reduced lower than 0. A character with 0 hit points
is defeated.
(See the "[Defeated](/sources/basicrules/appendix-a-conditions/#defeated)"
condition in Appendix A). A player whose heroic character is defeated can still
help their allies in certain ways.
(See the "[Defeated Heroes](/sources/basicrules/combat/#defeated-heroes)"
section in chapter 5).

Some effects give a character hit points on top of their current hit points,
called **Temporary Hit Points** (or THP). They are treated like normal hit
points, but are tracked separately. A character can only have temporary hit
points from one source at a time, and if they gain them from another source,
they can choose which source to use. When a character with temporary hit points
takes damage, they first take damage to the their temporary hit points, and any
excess carries over to your main hit points.

A character at half their hit point maximum or lower is considered to be
"Bloodied". Some effects trigger when a character becomes bloodied for the
first time in a battle.

### Hit Dice
{:id="hit-dice"}

A character's **Hit Dice** represent a character's ability to recover damage
outside of battle. You can roll hit dice during short rests to restore your
hit points, and you regain some of your hit dice during long rests.
(See the "[Resting](/sources/basicrules/adventure-exploration/#resting)"
section in Chapter 4). They may also be spent as a resource for certain
abilities. A creature can have a number of hit dice up to their
**Hit Dice Maximum**.

### Attack Stats
{:id="attack-stats"}

Attack stats are used as a bonus to attack rolls. Having a high attack stat
makes you more likely to hit with an attack.
(See the "[Making an Attack](/sources/basicrules/combat/#making-an-attack)"
section in Chapter 5 for more information about how to use attack rolls).

A  character in the Vanishing Isles has two basic attack stats:
* The **Weapon Attack** bonus is used when attacking with a weapon, such as a
sword, bow, or spear.
* The **Magic Attack** bonus is used when attacking with a spell or magical
focus, such as firebolt or primal claws.

Attack Rolls are d20 rolls derived from the following modifiers:
* **Attribute Modifier** - Gained from the Accuracy combat attribute.
* **Class Attack Bonus** - Determined by your Weapon Base Attack or Spell Base
Attack bonus, which increases as you gain class levels.  
<!-- TODO: Should consecutive attack penalty be written differently? -->
* **Consecutive Attack Penalty** - Attacks after the first one made in a round
become less accurate, receiving a -5 penalty to the second attack roll and -10
to the third.

### Guard Stats
{:id="guard-stats"}

Guard stats are used as DCs for opponents' attack rolls. Having a high Guard
stat means being less likely to be hit by attacks.

Every character in the Vanishing Isles has two basic guard stats:

* The **Physical Guard** stat is derived from Agility, and is primarily used
when defending against physical attacks, such as those made with weapons.
* The **Special Guard** stat is derived from Affinity, and is used when
defending against magical attacks such as those made with spells or foci.  

Each guard stats start at 10, and is raised and lowered by various modifiers,
the values of which are different between guard stats:

* **Attribute Modifier** - Gained from a combat attribute (Agility or
Affinity). May be limited by the **Attribute Limit** from armor or other
effects.
* **Armor Bonus** - Gained from wearing armor.
* **Shield Modifier** - Gained from equipping a shield.
* **Natural Bonuses** - Some characters have natural defenses that improve
their guard against some or all attacks.

### Saving Throws
{:id="saving-throws"}

Saving Throw modifiers (also known as Save Modifiers) are used in calculating
the result for saving throws. Having a high Save Modifier means being more
likely to reduce or nullify detrimental effects.

There are three main kinds of saving throws:

* **Fortitude** saves represent your ability to endure powerful threats such as
sickness, pain, and poison. You add your Might stat to Fortitude saving throws.
* **Reflex** saves represent your ability to evade threats such as a volley of
arrows, scythe traps, and fireballs. You add your Agility stat to Reflex saving
throws.
* **Will** saves represent your ability to resist mind-altering affects such as
charms, mind-reading, or sleep spells. You add your Affinity stat to Will
saves.

A Saving Throw is a d20 roll made against a **Save Difficulty Class (DC)**.
The modifier for the roll is derived from two major sources, the values of
which are different between saves:
* **Attribute Modifier** - Derived from a combat attribute (Might, Agility, or
Affinity).
* **Class Bonus** - Determined by the totals on your class chart, which
increase as you level up.

### Movement
{:id="movement"}

Your Movement stats are used in combat do determine how far you can move by
taking the Move action. A high Movement stat means being able to quickly move a
long distance. Movement is usually measured in feet. Most player characters
have a base land speed of 30 feet.

Information on movement in combat is found in
[Chapter 5: Combat](/sources/basicrules/combat/#movement).

### Initiative Bonus
{:id="initiative"}

Your **Initiative** bonus affects how early you take your turn in combat. It is
derived from your Agility stat.

Information on the Initiative system is found in
[Chapter 5: Combat](/sources/basicrules/combat/#initiative).

### Skills and Ranks
{:id="skills"}
As you level up, you gain **Skill Points**, which can be invested as
**Skill Ranks** into any skill. You can only have a number of skill ranks
invested in a skill up to their total level. The ranks invested in a skill are
added to that skill's rolls.

A list of skills and how they are used can be found in
[Chapter 3: Skills](/sources/basicrules/skills/).

A **Skill Roll** is a d20 roll made against a **Difficulty Class (DC)**.
The modifier for the roll is the number of ranks invested into the skill.  

### Class Levels
{:id="class"}
Your classes give you benefits depending on your class levels. A heroic
character has levels in their Background Class and their Hero Class. Gaining
levels in a class allow you to gain features and bonuses to certain
stats. The sum of your background Class levels is your **Background Level**,
whereas the sum of your Hero Class levels is your **Hero Level**.  

For each level you gain in a class, you gain the following stats. The bonuses
from a new level are added the total from previous levels in the same class.
(For example, 3 levels in a class with a d6 hit die and 2 levels in a class
with a d8 hit die result in a hit dice total of 3d6+2d8).
* **Hit Die Maximum** - Most class provide 1 hit die per level.
* **Hit Points** - Base amount gained per level is the average value of the
hit die (rounded up). Most hero classes also add the character's Vitality stat
each level.
* **Skill Points** - Base amount gained per level is specific to the class.
Most hero classes also add the character's Proficiency stat each level.

Additionally, as your level in a class increases, the following stat bonuses
may change depending on your class chart. These bonuses for each class are
added together to make that stat's **Class Bonus**.
* **Base Attack Bonuses** - Weapon Base Attack and Spell Base Attack bonuses.
* **Save Bonuses** - Fortitude, Reflex, and Will save bonuses.
