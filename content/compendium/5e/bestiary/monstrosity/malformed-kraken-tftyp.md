---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/tftyp
- 5e/monster/cr/10
- 5e/monster/size/huge
- 5e/monster/type/monstrosity
aliases:
- Malformed Kraken
---
# Malformed Kraken
*Source: Tales from the Yawning Portal p. 239*  

The Doomvault (Dead in Thay) contains a number of denizens that don't have all the traits or abilities of normal creatures of their kind. By far the most powerful of these "inferior" creatures is a malformed kraken that is kept in a saltwater pool and is not as large or as durable as a true kraken

```ad-statblock
title: Malformed Kraken
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TftYP/Malformed%20Kraken.webp#token)
*Huge monstrosity, Chaotic Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 172 (`15d12 + 75`)
- **Speed** 20 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)|11 (+0)|20 (+5)|11 (+0)|15 (+2)|15 (+2)|

- **Proficiency Bonus** +4
- **Saving Throws** Strength +11, Constitution +9, Intelligence +4, Wisdom +6, Charisma +6
- **Skills** ⏤
- **Senses** truesight 60 ft., passive Perception 12
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** lightning
- **Condition Immunities** [frightened](rules/5e/conditions.md#Frightened), [paralyzed](rules/5e/conditions.md#Paralyzed)
- **Languages** understands Common but can't speak, telepathy 60 ft.
- **Challenge** 10

## Traits

***Amphibious.*** The kraken can breathe air and water.

***Siege Monster.*** The kraken deals double damage to objects and structures.

## Actions

***Multiattack.*** The kraken makes three tentacle attacks. One of them can be replaced with a bite attack, and any of them can be replaced with Fling.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+11|noform|noparens|text(+11)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+7|noform|noparens|avg|text(16)` (`2d8 + 7`) piercing damage.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+11|noform|noparens|text(+11)` to hit, reach 20 ft., one target. *Hit:* `dice:2d6+7|noform|noparens|avg|text(14)` (`2d6 + 7`) bludgeoning damage, and the target is [grappled](rules/5e/conditions.md#Grappled) (escape DC 16). Until this grapple ends, the target is [restrained](rules/5e/conditions.md#Restrained). The kraken has ten tentacles, each of which can grapple one target.

***Fling.*** One Medium or smaller object held or creature [grappled](rules/5e/conditions.md#Grappled) by the kraken's tentacles is thrown up to 60 feet in a random direction and knocked [prone](rules/5e/conditions.md#Prone). If a thrown target strikes a solid surface, the target takes `dice:1d6|noform|noparens|avg|text(3)` (`d6`) bludgeoning damage for every 10 feet it was thrown. If the target is thrown at another creature, that creature must succeed on a DC 16 Dexterity saving throw or take the same damage and be knocked [prone](rules/5e/conditions.md#Prone).

***Lightning Storm.*** The kraken creates three bolts of lightning, each of which can strike a target the kraken can see within 150 feet of it. A target must make a DC 16 Dexterity saving throw, taking `dice:3d10|noform|noparens|avg|text(16)` (`3d10`) lightning damage on a failed save, or half as much damage on a successful one.
```
^statblock