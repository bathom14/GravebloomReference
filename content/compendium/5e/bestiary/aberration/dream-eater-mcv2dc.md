---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mcv2dc
- 5e/monster/cr/7
- 5e/monster/size/medium
- 5e/monster/type/aberration
aliases:
- Dream Eater
---
# Dream Eater
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 3*  

Originating from the dream-warped elven realm of Silvanesti, dream eaters are violent manifestations of nightmares and subconscious terrors. The true appearance of a dream eater is obscured, as the dream eater twists its hazy form into surreal illusions of its foes' greatest fears. However, all dream eaters share one thing: a gaping, always-smiling mouth, which it reveals before engulfing its prey in a phantasmagorical nightmare.

The key to defeating a dream eater lies not in brute force but in the ability to pierce its illusions and wrest others from its terrors. As such, bards and other persuasive adventurers find themselves uniquely poised to confront a hungering dream eater.

```ad-statblock
title: Dream Eater
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MCV2DC/Dream%20Eater.webp#token)
*Medium aberration, typically  Chaotic Evil*

- **Armor Class** 15
- **Hit Points** 77 (`14d8 + 14`)
- **Speed** 0 ft., fly 50 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|20 (+5)|13 (+1)|12 (+1)|16 (+3)|21 (+5)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** blindsight 120 ft. (blind beyond this radius), passive Perception 13
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** psychic
- **Condition Immunities** [blinded](rules/5e/conditions.md#Blinded), [charmed](rules/5e/conditions.md#Charmed), [frightened](rules/5e/conditions.md#Frightened), [grappled](rules/5e/conditions.md#Grappled), [paralyzed](rules/5e/conditions.md#Paralyzed), [petrified](rules/5e/conditions.md#Petrified), [restrained](rules/5e/conditions.md#Restrained)
- **Languages** Deep Speech, telepathy 120 ft.
- **Challenge** 7

## Traits

***Ghastly Visions.*** Each creature that starts its turn within 30 feet of the dream eater must make a DC 16 Wisdom saving throw. On a failed save, the creature is [frightened](rules/5e/conditions.md#Frightened) of the dream eater until the start of the creature's next turn. If a creature's saving throw is successful, the creature is immune to this dream eater's Ghastly Visions trait for the next 24 hours.

***Incorporeal Movement.*** The dream eater can move through other creatures and objects as if they were difficult terrain. It takes `dice:1d10|noform|noparens|avg|text(5)` (`d10`) force damage if it ends its turn inside an object.

***Magic Resistance.*** The dream eater has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The dream eater makes two Ensnaring Shriek attacks.

***Ensnaring Shriek.*** *Melee  or Ranged Spell Attack:* `dice:1d20+8|noform|noparens|text(+8)` to hit, reach 15 ft. or range 60 ft., one target. *Hit:* `dice:2d6+5|noform|noparens|avg|text(12)` (`2d6 + 5`) psychic damage, and if the target is a Medium or smaller creature, the target must succeed on a DC 16 Charisma saving throw or be pulled up to 15 feet toward the dream eater.

## Bonus Actions

***Engulfing Nightmare.*** The dream eater targets one creature within 5 feet of itself. The target must succeed on a DC 16 Wisdom saving throw or be engulfed by the dream eater, as the dream eater envelops the creature in a miasma of its worst fears.

When the dream eater engulfs a target, the dream eater enters its space, and the target immediately takes `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) psychic damage. An engulfed target is [restrained](rules/5e/conditions.md#Restrained) and [blinded](rules/5e/conditions.md#Blinded), and it takes an additional `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) psychic damage at the start of each of the dream eater's turns. When the dream eater moves, the engulfed target moves with it.

The dream eater can have only one target engulfed at a time. An engulfed target escapes at the start of its turn by making a DC 16 Wisdom saving throw. On a successful save, the target escapes; the target is no longer engulfed, and it enters a space of its choice within 5 feet of the dream eater. A creature within 15 feet of the dream eater also can use its action to attempt to free an engulfed target. Doing so requires the creature to use its action to make a DC 16 Charisma ([Persuasion](rules/5e/skills.md#Persuasion)) check to convince the engulfed target the nightmare isn't real, with the target escaping on a success. The creature making the check takes `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) psychic damage, regardless of the check's success or failure, as its mind brushes against the nightmare.
```
^statblock