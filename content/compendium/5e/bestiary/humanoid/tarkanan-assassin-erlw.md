---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/erlw
- 5e/monster/cr/2
- 5e/monster/size/medium
- 5e/monster/type/humanoid/any-race
aliases:
- Tarkanan Assassin
---
# Tarkanan Assassin
*Source: Eberron: Rising from the Last War p. 320*  

Tarkanan assassins are the elite killers, spies, and thieves who work for House Tarkanan, a criminal organization specializing in theft and assassination. In addition to their deadly skill, a Tarkanan assassin possesses an aberrant dragonmark—a twisted sigil that provides them with magical power. House Tarkanan actively seeks and recruits people with aberrant dragonmarks.

> [!note] Aberrant Dragonmark Innate Spells
> 
> The power granted by an aberrant dragonmark is unpredictable. When running a Tarkanan assassin, you can roll on the Aberrant Dragonmark Innate Spells table to determine the spells gained from that NPC's aberrant mark, replacing the spells in the stat block's Innate Spellcasting trait.
> 
> `dice: [](tarkanan-assassin-erlw.md#^at-will-1-day)`
> 
> | dice: d6 | At Will | 1/Day |
> |----------|---------|-------|
> | 1 | [Fire bolt](compendium/5e/spells/fire-bolt.md) (`dice:2d10\|noform\|noparens\|avg` (`2d10`)) | [Burning hands](compendium/5e/spells/burning-hands.md) (`dice:3d6\|noform\|noparens\|avg` (`3d6`)) |
> | 2 | [Shocking grasp](compendium/5e/spells/shocking-grasp.md) (`dice:2d8\|noform\|noparens\|avg` (`2d8`)) | [Chromatic orb](compendium/5e/spells/chromatic-orb.md) (`dice:4d8\|noform\|noparens\|avg` (`4d8`)) |
> | 3 | [Poison spray](compendium/5e/spells/poison-spray.md) (`dice:2d12\|noform\|noparens\|avg` (`2d12`)) | [Ray of sickness](compendium/5e/spells/ray-of-sickness.md) (`dice:3d8\|noform\|noparens\|avg` (`3d8`)) |
> | 4 | [Friends](compendium/5e/spells/friends.md) | [Charm person](compendium/5e/spells/charm-person.md) (two creatures) |
> | 5 | [Minor illusion](compendium/5e/spells/minor-illusion.md) | [Thunderwave](compendium/5e/spells/thunderwave.md) (`dice:2d8\|noform\|noparens\|avg` (`2d8`)) |
> | 6 | [Dancing lights](compendium/5e/spells/dancing-lights.md) | [Sleep](compendium/5e/spells/sleep.md) (`dice:7d8\|noform\|noparens\|avg` (`7d8`)) |
> ^at-will-1-day
^aberrant-dragonmark-innate-spells

```ad-statblock
title: Tarkanan Assassin
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Tarkanan%20Assassin.webp#token)
*Medium humanoid (any race), Any Non-Good alignment*

- **Armor Class** 15 ([studded leather](compendium/5e/items/studded-leather-armor-phb.md))
- **Hit Points** 45 (`7d8 + 14`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|16 (+3)|14 (+2)|10 (+0)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Athletics](rules/5e/skills.md#Athletics) +3, [Deception](rules/5e/skills.md#Deception) +2, [Perception](rules/5e/skills.md#Perception) +4, [Sleight of Hand](rules/5e/skills.md#Sleight%20of%20Hand) +5, [Stealth](rules/5e/skills.md#Stealth) +5
- **Senses** darkvision 60 ft., passive Perception 14
- **Languages** Common, Thieves' cant
- **Challenge** 2

## Traits

***Innate Spellcasting.*** The assassin's spellcasting ability is Constitution (`dice:1d20+4|noform|noparens|text(+4)` to hit with spell attacks). It can innately cast the following spells, requiring no material components:

**At will:** [fire bolt](compendium/5e/spells/fire-bolt.md)

**1/day:** [chromatic orb](compendium/5e/spells/chromatic-orb.md)

***Unstable Mark.*** When the assassin casts an innate spell, each creature within 10 feet of the assassin must make a DC 12 Constitution saving throw, taking `dice:1d8|noform|noparens|avg|text(4)` (`d8`) force damage on a failed save, or half as much damage on a successful one.

## Actions

***Multiattack.*** The assassin makes two shortsword attacks.

***Shortsword.*** *Melee Weapon Attack:* `dice:1d20+5|noform|noparens|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|noparens|avg|text(6)` (`1d6 + 3`) piercing damage plus `dice:2d6|noform|noparens|avg|text(7)` (`2d6`) poison damage.

***Fire Bolt (Cantrip).*** *Ranged Spell Attack:* `dice:1d20+4|noform|noparens|text(+4)` to hit, range 120 ft., one target. *Hit:* `dice:2d10|noform|noparens|avg|text(11)` (`2d10`) fire damage. A flammable object hit by this spell ignites if it isn't being worn or carried.

***Chromatic Orb (1/Day).*** *Ranged Spell Attack:* `dice:1d20+4|noform|noparens|text(+4)` to hit, range 90 ft., one creature. *Hit:* `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) damage of a type chosen by the assassin: acid, cold, fire, lightning, poison, or thunder.
```
^statblock