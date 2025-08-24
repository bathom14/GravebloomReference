---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/ggr
- 5e/monster/cr/5
- 5e/monster/size/medium
- 5e/monster/type/humanoid/any-race
aliases:
- Galvanic Blastseeker
---
# Galvanic Blastseeker
*Source: Guildmasters' Guide to Ravnica p. 243*  

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```ad-statblock
title: Galvanic Blastseeker
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Galvanic%20Blastseeker.webp#token)
*Medium humanoid (any race), Chaotic Neutral*

- **Armor Class** 13
- **Hit Points** 52 (`8d8 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|17 (+3)|14 (+2)|19 (+4)|10 (+0)|13 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +6
- **Skills** [Acrobatics](rules/5e/skills.md#Acrobatics) +6, [Arcana](rules/5e/skills.md#Arcana) +7, [Perception](rules/5e/skills.md#Perception) +3
- **Senses** passive Perception 13
- **Damage Resistances** lightning, thunder
- **Languages** Common and Primordial, plus any one language
- **Challenge** 5

## Traits

***Innate Spellcasting.*** The blastseeker's innate spellcasting ability is Intelligence (spell save DC 15, `dice:1d20+7|noform|noparens|text(+7)` to hit with spell attacks). The blastseeker can innately cast the following spells, requiring no components other than its Izzet gear, which doesn't function for others:

**3/day each:** [levitate](compendium/5e/spells/levitate.md), [lightning bolt](compendium/5e/spells/lightning-bolt.md), [thunderwave](compendium/5e/spells/thunderwave.md)

**1/day:** [stoneskin](compendium/5e/spells/stoneskin.md)

***Galvanic Overcast (Recharge 5-6).*** When the blastseeker casts [lightning bolt](compendium/5e/spells/lightning-bolt.md) or thunderwave, it can roll a die. On an odd number, the blastseeker takes `dice:2d8|noform|noparens|avg|text(9)` (`2d8`) force damage. On an even number, the spell also deals `dice:2d8|noform|noparens|avg|text(9)` (`2d8`) lightning damage to each target that fails its saving throw.

***Heart of the Storm.*** When the blastseeker casts [lightning bolt](compendium/5e/spells/lightning-bolt.md) or thunderwave, all other creatures within 10 feet of the blastseeker each take 3 lightning damage.

***Gust-Propelled Leap.*** The blastseeker can use a bonus action to fly up to 10 feet without provoking opportunity attacks.

## Actions

***Spear.*** *Melee  or Ranged Weapon Attack:* `dice:1d20+3|noform|noparens|text(+3)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d6|noform|noparens|avg|text(3)` (`d6`) piercing damage, or `dice:1d8|noform|noparens|avg|text(4)` (`d8`) piercing damage if used with two hands to make a melee attack.
```
^statblock