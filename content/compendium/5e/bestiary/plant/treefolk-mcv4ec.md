---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mcv4ec
- 5e/monster/cr/11
- 5e/monster/size/large
- 5e/monster/type/plant/druid
aliases:
- Treefolk
---
# Treefolk
*Source: Monstrous Compendium Volume 3: 4: Eldraine Creatures*  

The wise and ancient treefolk thrive in the depths of Eldraine's forested wilds. Though many treefolk rival members of the high fae in age, they rarely interfere with the goings-on of the faerie court. Instead, treefolk serve as guardians and shepherds of their wild groves, dispensing wisdom and blessings to travelers who wander under their branches.

> [!quote] A quote from Borogrove, Tuinvale treefolk  
> 
> Right now, you are a feeble stick, but I will help you grow some rings.


```ad-statblock
title: Treefolk
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV4EC/Treefolk.webp#token)
*Large plant (druid), Any alignment*

- **Armor Class** 17 (natural armor)
- **Hit Points** 171 (`18d10 + 72`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|12 (+1)|18 (+4)|10 (+0)|20 (+5)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Intelligence +4, Wisdom +9
- **Skills** [Insight](rules/5e/skills.md#Insight) +9, [Nature](rules/5e/skills.md#Nature) +8, [Perception](rules/5e/skills.md#Perception) +9
- **Senses** blindsight 30 ft., passive Perception 19
- **Damage Vulnerabilities** fire
- **Damage Resistances** bludgeoning, piercing
- **Languages** Common, Druidic, Sylvan
- **Challenge** 11

## Traits

***Plant Camouflage.*** The treefolk has advantage on Dexterity ([Stealth](rules/5e/skills.md#Stealth)) checks it makes in forest terrain.

***Tree Stride.*** Once on each of its turns, the treefolk can use 10 feet of its movement to step magically into one living tree within 5 feet of itself and emerge from a second living tree within 60 feet of itself that it can see, appearing in an unoccupied space within 5 feet of the second tree. Both trees must be at least as large as the treefolk.

## Actions

***Multiattack.*** The treefolk makes two Crushing Vine attacks, two Nightshade Bolt attacks, or one of each.

***Crushing Vine.*** *Melee Weapon Attack:* `dice:1d20+10|noform|noparens|text(+10)` to hit, reach 10 ft., one target. *Hit:* `dice:3d12+6|noform|noparens|avg|text(25)` (`3d12 + 6`) bludgeoning damage. If the target is a creature, it has the [grappled](rules/5e/conditions.md#Grappled) condition (escape DC 18). While [grappled](rules/5e/conditions.md#Grappled), the creature also has the [restrained](rules/5e/conditions.md#Restrained) condition. The treefolk can grapple up to six creatures this way.

***Nightshade Bolt.*** *Ranged Spell Attack:* `dice:1d20+9|noform|noparens|text(+9)` to hit, range 60 ft., one target. *Hit:* `dice:6d10|noform|noparens|avg|text(33)` (`6d10`) poison damage.

***Spellcasting.*** The treefolk casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 17):

**At will:** [detect poison and disease](compendium/5e/spells/detect-poison-and-disease.md), [druidcraft](compendium/5e/spells/druidcraft.md)

**2/day each:** [enlarge/reduce](compendium/5e/spells/enlarge-reduce.md), [speak with plants](compendium/5e/spells/speak-with-plants.md)

**1/day:** [commune with nature](compendium/5e/spells/commune-with-nature.md) (as an action)

## Bonus Actions

***Oaken Boon.*** The treefolk blesses one creature other than itself that it can see within 60 feet of itself with the might and wisdom of the forest. While blessed in this way, a creature can use the treefolk's Tree Stride trait and gains `dice:2d4|noform|noparens|avg|text(5)` (`2d4`) temporary hit points at the start of each of its turns. This blessing lasts for 1 minute, until the treefolk has the [incapacitated](rules/5e/conditions.md#Incapacitated) condition, or until the treefolk uses this bonus action again.
```
^statblock