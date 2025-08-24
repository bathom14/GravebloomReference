---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mot
- 5e/monster/cr/3
- 5e/monster/size/medium
- 5e/monster/type/humanoid
aliases:
- Meletian Hoplite
---
# Meletian Hoplite
*Source: Mythic Odysseys of Theros p. 229*  

Meletian hoplites use a combination of cunning, faith, and magic to defend their coastal home. Most of these skilled soldiers serve in the Reverent Army, the defenders of Meletis, which uses an array of proven strategies and flexible troop formations to gain the advantage over foes. Bolstered by trained griffon and pegasus steeds, they strike foes where they least expect.

Hoplites are highly trained warriors, versed not only in strategy and tactics but in the glorification of the warrior's spirit, the basis of an ethos that forges an unbreakable bond between members of a military unit. In combat, hoplites typically work in groups and use coordinated tactics to win victories.

The three Hoplite Unit Names tables present the sorts of titles used by hoplite contingents hailing from Theros's great poleis. Consider using these names for military forces characters encounter during their adventures or that they were once a part of.

**Akroan Hoplite Unit Names**

| D8 | Name |
|----|------|
| 1 | Spears of Iroas |
| 2 | Iron Fangs |
| 3 | Arrows of Anax |
| 4 | The Unbroken |
| 5 | Anvil of Purphoros |
| 6 | Skewering Squad |
| 7 | Shield of Akros |
| 8 | Cymede's Heart |
^akroan-hoplite-unit-names

**Meletian Hoplite Unit Names**

| D8 | Name |
|----|------|
| 1 | Kraken's Claw |
| 2 | Hands of Justice |
| 3 | Thassa's Spear |
| 4 | Ephara's Shield |
| 5 | Kindred of the Deep |
| 6 | Riders of Heliod |
| 7 | Keepers of Pyrgnos |
| 8 | The Skysworn |
^meletian-hoplite-unit-names

**Setessan Hoplite Unit Names**

`dice: [](meletian-hoplite-mot.md#^setessan-hoplite-unit-names)`

| dice: d8 | Name |
|----------|------|
| 1 | Nylea's Arrows |
| 2 | The Watchers |
| 3 | Fangs of Ophis |
| 4 | The Swiftswords |
| 5 | Karametra's Wolves |
| 6 | Defenders of the Grove |
| 7 | Bronze Blades |
| 8 | The Jackals |
^setessan-hoplite-unit-names

```ad-statblock
title: Meletian Hoplite
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MOT/Meletian%20Hoplite.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 18 ([breastplate](compendium/5e/items/breastplate-phb.md), [shield](compendium/5e/items/shield-phb.md))
- **Hit Points** 49 (`9d8 + 9`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|14 (+2)|12 (+1)|16 (+3)|13 (+1)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +4, Intelligence +5
- **Skills** [Arcana](rules/5e/skills.md#Arcana) +5, [History](rules/5e/skills.md#History) +5, [Perception](rules/5e/skills.md#Perception) +3
- **Senses** passive Perception 13
- **Languages** Common
- **Challenge** 3

## Traits

***Spellcasting.*** The hoplite is a 3rd-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 13, `dice:1d20+5|noform|noparens|text(+5)` to hit with spell attacks). It has the following wizard spells prepared:

**Cantrips (at will):** [mage hand](compendium/5e/spells/mage-hand.md), [minor illusion](compendium/5e/spells/minor-illusion.md), [ray of frost](compendium/5e/spells/ray-of-frost.md) (see "Actions" below)

**1st level (4 slots):** [color spray](compendium/5e/spells/color-spray.md), [expeditious retreat](compendium/5e/spells/expeditious-retreat.md), [sleep](compendium/5e/spells/sleep.md)

**2nd level (2 slots):** [blur](compendium/5e/spells/blur.md), [cloud of daggers](compendium/5e/spells/cloud-of-daggers.md), [invisibility](compendium/5e/spells/invisibility.md)

## Actions

***Multiattack.*** The hoplite makes three weapon attacks. It can replace one weapon attack with ray of frost.

***Spear.*** *Melee  or Ranged Weapon Attack:* `dice:1d20+5|noform|noparens|text(+5)` to hit, reach 5 ft., one target. *Hit:* `dice:1d6+3|noform|noparens|avg|text(6)` (`1d6 + 3`) piercing damage, or `dice:1d8+3|noform|noparens|avg|text(7)` (`1d8 + 3`) piercing damage if used with two hands to make a melee attack.

***Shield Bash.*** *Melee Weapon Attack:* `dice:1d20+5|noform|noparens|text(+5)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d4+3|noform|noparens|avg|text(5)` (`1d4 + 3`) bludgeoning damage. If the target is a Medium or smaller creature, it must succeed on a DC 13 Strength saving throw or be knocked [prone](rules/5e/conditions.md#Prone).

***Ray of Frost (Cantrip).*** *Ranged Spell Attack:* `dice:1d20+5|noform|noparens|text(+5)` to hit, range 60 ft., one creature. *Hit:* `dice:1d8|noform|noparens|avg|text(4)` (`d8`) cold damage, and the target's speed is reduced by 10 feet until the start of the hoplite's next turn.
```
^statblock