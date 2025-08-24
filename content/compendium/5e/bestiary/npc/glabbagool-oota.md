---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/oota
- 5e/monster/cr/2
- 5e/monster/size/large
- 5e/monster/type/ooze
aliases:
- Glabbagool
---
# Glabbagool
*Source: Out of the Abyss p. 35*  

Juiblex's arrival in the Underdark has granted Glabbagool sentience and awareness. The ooze is genuinely curious about other creatures and wants to learn more about the world. It defends itself if attacked, but doesn't otherwise try to harm the characters, instead asking who they are, where they come from, and why they have come to the temple.

```ad-statblock
title: Glabbagool
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/OotA/Glabbagool.webp#token)
*Large ooze, Unaligned*

- **Armor Class** 6
- **Hit Points** 84 (`8d10 + 40`)
- **Speed** 15 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)| 3 (-4)|20 (+5)|10 (+0)| 6 (-2)| 1 (-5)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 60 ft. (blind beyond this radius), passive Perception 8
- **Condition Immunities** [blinded](rules/5e/conditions.md#Blinded), [charmed](rules/5e/conditions.md#Charmed), [deafened](rules/5e/conditions.md#Deafened), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [prone](rules/5e/conditions.md#Prone)
- **Languages** telepathy 60 ft.
- **Challenge** 2

## Traits

***Ooze Cube.*** Glabbagool takes up its entire space. Other creatures can enter the space, but a creature that does so is subjected to Glabbagool's Engulf and has disadvantage on the saving throw.

Creatures inside Glabbagool can be seen but have total cover.

A creature within 5 feet of Glabbagool can take an action to pull a creature or object out of Glabbagool. Doing so requires a successful DC 12 Strength check, and the creature making the attempt takes `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) acid damage.

Glabbagool can hold only one Large creature or up to four Medium or smaller creatures inside it at a time.

***Transparent.*** Even when Glabbagool is in plain sight, it takes a successful DC 15 Wisdom ([Perception](rules/5e/skills.md#Perception)) check to spot a cube that has neither moved nor attacked. A creature that tries to enter Glabbagool's space while unaware of Glabbagool is [surprised](rules/5e/conditions.md#Surprised) by Glabbagool.

## Actions

***Pseudopod.*** *Melee Weapon Attack:* `dice:1d20+4|noform|noparens|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) acid damage.

***Engulf.*** Glabbagool moves up to its speed. While doing so, it can enter Large or smaller creatures' spaces. Whenever Glabbagool enters a creature's space, the creature must make a DC 12 Dexterity saving throw.

On a successful save, the creature can choose to be pushed 5 feet back or to the side of Glabbagool. A creature that chooses not to be pushed suffers the consequences of a failed saving throw.

On a failed save, Glabbagool enters the creature's space, and the creature takes `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) acid damage and is engulfed. The engulfed creature can't breathe, is [restrained](rules/5e/conditions.md#Restrained), and takes `dice:6d6|noform|noparens|avg|text(21)` (`6d6`) acid damage at the start of each of Glabbagool's turns. When Glabbagool moves, the engulfed creature moves with it.

An engulfed creature can try to escape by taking an action to make a DC 12 Strength check. On a success, the creature escapes and enters a space of its choice within 5 feet of Glabbagool.
```
^statblock