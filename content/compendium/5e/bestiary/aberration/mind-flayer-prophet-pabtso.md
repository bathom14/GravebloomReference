---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/pabtso
- 5e/monster/cr/8
- 5e/monster/size/medium
- 5e/monster/type/aberration
aliases:
- Mind Flayer Prophet
---
# Mind Flayer Prophet
*Source: Phandelver and Below: The Shattered Obelisk p. 210*  

Some mind flayers dedicate their lives to channeling abstruse truths from beyond reality. This insight gives them preternatural senses and allows them to focus their innate psionic power.

## Mind Flayers

Mind flayers, also known as illithids, feast on the brains of Humanoids across the multiverse. They are distinguished by their purple-toned skin and octopus-like heads, from which extend writhing tentacles.

## Statblock

```ad-statblock
title: Mind Flayer Prophet
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PaBTSO/Mind%20Flayer%20Prophet.webp#token)
*Medium aberration, typically  Lawful Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 97 (`15d8 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|14 (+2)|20 (+5)|17 (+3)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +8, Wisdom +6, Charisma +6
- **Skills** [Arcana](rules/5e/skills.md#Arcana) +8, [Insight](rules/5e/skills.md#Insight) +6, [Perception](rules/5e/skills.md#Perception) +6, [Stealth](rules/5e/skills.md#Stealth) +5
- **Senses** darkvision 120 ft., passive Perception 16
- **Languages** Deep Speech, telepathy 120 ft., Undercommon
- **Challenge** 8

## Traits

***Awareness.*** The mind flayer has advantage on initiative rolls and can't be surprised as long as it doesn't have the [incapacitated](rules/5e/conditions.md#Incapacitated) condition.

***Magic Resistance.*** The mind flayer has advantage on saving throws against spells and other magical effects.

## Actions

***Tentacles.*** *Melee Weapon Attack:* `dice:1d20+8|noform|noparens|text(+8)` to hit, reach 5 ft., one creature. *Hit:* `dice:2d10+5|noform|noparens|avg|text(16)` (`2d10 + 5`) psychic damage. If the target is Medium or smaller, it has the [grappled](rules/5e/conditions.md#Grappled) condition (escape DC 16) and must succeed on a DC 16 Intelligence saving throw or have the [stunned](rules/5e/conditions.md#Stunned) condition until the grapple ends.

***Extract Brain.*** *Melee Weapon Attack:* `dice:1d20+8|noform|noparens|text(+8)` to hit, reach 5 ft., one Humanoid [grappled](rules/5e/conditions.md#Grappled) by the mind flayer. *Hit:* `dice:10d10|noform|noparens|avg|text(55)` (`10d10`) piercing damage. If this damage reduces the target to 0 hit points, the mind flayer kills it by extracting and devouring its brain.

***Mind Whip (Recharge 5-6).*** The mind flayer lashes out with psychic energy, targeting up to two creatures it can see within 60 feet of itself. Each target must succeed on a DC 16 Intelligence saving throw or take `dice:4d8+5|noform|noparens|avg|text(23)` (`4d8 + 5`) psychic damage and have the [stunned](rules/5e/conditions.md#Stunned) condition for 1 minute. A [stunned](rules/5e/conditions.md#Stunned) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Spellcasting (Psionics).*** The mind flayer casts one of the following spells, requiring no spell components and using Intelligence as the spellcasting ability (spell save DC 16):

**At will:** [detect magic](compendium/5e/spells/detect-magic.md), [detect thoughts](compendium/5e/spells/detect-thoughts.md), [levitate](compendium/5e/spells/levitate.md)

**1/day each:** [dominate monster](compendium/5e/spells/dominate-monster.md), [plane shift](compendium/5e/spells/plane-shift.md) (self only), [true seeing](compendium/5e/spells/true-seeing.md)
```
^statblock