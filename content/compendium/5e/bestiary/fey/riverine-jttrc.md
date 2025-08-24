---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/jttrc
- 5e/monster/cr/12
- 5e/monster/size/large
- 5e/monster/type/fey
aliases:
- Riverine
---
# Riverine
*Source: Journeys through the Radiant Citadel p. 133*  

More than mere waterway guardians, riverines are embodiments of particular rivers. These spirits of nature take shape to defend their waters and interact with those who travel along their currents. From the waist up, riverines have skin the color of the waters they protect but are otherwise humanlike in appearance. From the waist down, they can manifest either humanlike legs or churning gouts of water. A riverine's personality reflects the nature of the river it arises from—some are lethargic while others are wild and reckless.

## A Riverine's Lair

Some riverines enjoy reverence akin to worship. Their likenesses are cast as statues and housed in temples, and worshipers act as agents between the river spirits and the people who revere them. These temples often become the home of the riverine itself, serving as its lair, though other nexuses of power along the river's path—such as its source or a significant waterfall—can also be used as lairs by a riverine.

A riverine encountered in its lair has a challenge rating of 13 (10,000 XP).

## Statblock

```ad-statblock
title: Riverine
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/JttRC/Riverine.webp#token)
*Large fey, Any alignment*

- **Armor Class** 14
- **Hit Points** 204 (`24d10 + 72`)
- **Speed** 30 ft., swim 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|19 (+4)|17 (+3)|12 (+1)|16 (+3)|21 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +5, Wisdom +7, Charisma +9
- **Skills** [Insight](rules/5e/skills.md#Insight) +7, [Nature](rules/5e/skills.md#Nature) +5, [Perception](rules/5e/skills.md#Perception) +7
- **Senses** blindsight 60 ft., passive Perception 17
- **Damage Resistances** acid, fire
- **Languages** Aquan, Common, Sylvan
- **Challenge** 12

## Traits

***Amphibious.*** The riverine can breathe air and water.

***Legendary Resistance (3/Day).*** If the riverine fails a saving throw, it can choose to succeed instead.

## Actions

***Multiattack.*** The riverine makes two Flood Strike attacks.

***Flood Strike.*** *Melee Weapon Attack:* `dice:1d20+9|noform|noparens|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:2d8+5|noform|noparens|avg|text(14)` (`2d8 + 5`) bludgeoning damage plus `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) cold damage.

***Spellcasting.*** The riverine casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 17):

**At will:** [control water](compendium/5e/spells/control-water.md), [fog cloud](compendium/5e/spells/fog-cloud.md)

**1/day:** [greater restoration](compendium/5e/spells/greater-restoration.md)

## Bonus Actions

***Whirlpool Step.*** The riverine magically teleports to an unoccupied space it can see within 30 feet of itself. Both the space it leaves and its destination must be in or on the surface of water.

## Legendary Actions

***Whirlpool Rush.*** The riverine uses its Whirlpool Step. Immediately after it teleports, each creature within 5 feet of the riverine's destination space takes `dice:1d10|noform|noparens|avg|text(5)` (`d10`) cold damage.

***Raging Deluge (Costs 2 Actions).*** The riverine unleashes a torrent of river water in a 30-foot line that is 5 feet wide. Each creature in that area must make a DC 17 Dexterity saving throw. On a failed save, a creature takes `dice:2d10|noform|noparens|avg|text(11)` (`2d10`) bludgeoning damage and is knocked [prone](rules/5e/conditions.md#Prone). On a successful save, a creature takes half as much damage and isn't knocked [prone](rules/5e/conditions.md#Prone).

![Riverine](compendium/5e/bestiary/legendary-group/riverine-jttrc.md)
```
^statblock