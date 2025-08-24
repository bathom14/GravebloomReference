---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/ggr
- 5e/monster/cr/5
- 5e/monster/size/medium
- 5e/monster/type/humanoid/elf
aliases:
- Golgari Shaman
---
# Golgari Shaman
*Source: Guildmasters' Guide to Ravnica p. 236*  

Golgari shamans are the spiritual leaders of the Golgari Swarm. They teach the guild's beliefs about the cycles of nature, using their necromantic magic to show how life sprouts from death.

Golgari shamans paint their faces so they appear to have extra eyes on their cheeks and chins. They sometimes use magical moodmark paint (described in chapter 5) to allow them to communicate by means of these marks. They wear clothing adorned with beetle carapaces, spiderwebs, or shelf fungus.

## Golgari Lairs

Members of the Golgari Swarm have an intimate connection to their territory. When at least six Golgari defend their territory together, they can call on the environment to aid them. The group must include Jarad Vod Savo or at least one Golgari shaman, kraul death priest, undercity medusa, or Devkarin lich. When determining the difficulty of such an encounter, consider the lair to be one additional creature of challenge rating 1.

## Statblock

```ad-statblock
title: Golgari Shaman
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Golgari%20Shaman.webp#token)
*Medium humanoid (elf), Neutral Evil*

- **Armor Class** 14 ([hide armor](compendium/5e/items/hide-armor-phb.md))
- **Hit Points** 88 (`16d8 + 16`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|15 (+2)|12 (+1)|12 (+1)|17 (+3)|16 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Constitution +4, Wisdom +6
- **Skills** [Arcana](rules/5e/skills.md#Arcana) +4, [Insight](rules/5e/skills.md#Insight) +6, [Nature](rules/5e/skills.md#Nature) +4, [Religion](rules/5e/skills.md#Religion) +4
- **Senses** darkvision 60 ft., passive Perception 13
- **Languages** Common, Elvish
- **Challenge** 5

## Traits

***Spellcasting.*** The shaman is an 8th-level Golgari spellcaster. Its spellcasting ability is Wisdom (spell save DC 14, `dice:1d20+6|noform|noparens|text(+6)` to hit with spell attacks). The shaman has the following druid spells prepared:

**Cantrips (at will):** [poison spray](compendium/5e/spells/poison-spray.md), [shillelagh](compendium/5e/spells/shillelagh.md), [thorn whip](compendium/5e/spells/thorn-whip.md)

**1st level (4 slots):** [cure wounds](compendium/5e/spells/cure-wounds.md), [entangle](compendium/5e/spells/entangle.md), [ray of sickness](compendium/5e/spells/ray-of-sickness.md)

**2nd level (3 slots):** [pass without trace](compendium/5e/spells/pass-without-trace.md), [ray of enfeeblement](compendium/5e/spells/ray-of-enfeeblement.md), [spike growth](compendium/5e/spells/spike-growth.md)

**3rd level (3 slots):** [animate dead](compendium/5e/spells/animate-dead.md), [dispel magic](compendium/5e/spells/dispel-magic.md), [plant growth](compendium/5e/spells/plant-growth.md)

**4th level (2 slots):** [blight](compendium/5e/spells/blight.md), [giant insect](compendium/5e/spells/giant-insect.md)

***Fey Ancestry.*** The shaman has advantage on saving throws against being [charmed](rules/5e/conditions.md#Charmed), and magic can't put it to sleep.

## Actions

***Quarterstaff.*** *Melee Weapon Attack:* `dice:1d20+4|noform|noparens|text(+4)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+2|noform|noparens|avg|text(5)` (`1d6 + 2`) bludgeoning damage, or `dice:1d8+2|noform|noparens|avg|text(6)` (`1d8 + 2`) bludgeoning damage if used with two hands.

***Fungal Rot.*** *Melee Spell Attack:* `dice:1d20+6|noform|noparens|text(+6)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8|noform|noparens|avg|text(9)` (`2d8`) necrotic damage, and the target must make a DC 14 Constitution saving throw, taking `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) poison damage on a failed save, or half as much damage on a successful one.

## Reactions

***Feed on Death.*** When a creature within 30 feet of the shaman drops to 0 hit points, the shaman gains `dice:1d10|noform|noparens|avg|text(5)` (`d10`) temporary hit points.
```
^statblock