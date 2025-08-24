---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/erlw
- 5e/monster/cr/7
- 5e/monster/size/large
- 5e/monster/type/construct
aliases:
- Living Cloudkill
---
# Living Cloudkill
*Source: Eberron: Rising from the Last War p. 299*  

## Constructed Nature

A living spell doesn't require air, food, drink, or sleep.

Of all the anomalies that emerged from the magical cataclysm that created the Mournland, the appearance of living spells might be the most mysterious. In some unknown fashion, the magical energy unleashed during the Last War caused spell effects to take on sentience. A living spell appears much like a normal spell effect, except that its magical energy endures indefinitely.

Living spells haunt the Mournland and other areas blasted by the Last War, somehow subsisting on ambient magical energy as they writhe and across the landscape. Though they have no need for sustenance, they attack any creatures they come into contact with, lashing out indiscriminately with their corrupted magic.

## Customizing a Living Spell

Living spells come in many varieties; the stat blocks here are three examples. Living spells most often manifest from evocation and conjuration spells. To make a living spell from a different spell, choose a damage-dealing evocation or conjuration spell from the wizard spell list of up to 5th level. Then consult the Living Spell Customization table to see which stat block to customize, based on the chosen spell's level.

**Living Spell Customization**

| Spell Level | Stat Block to Customize |
|-------------|-------------------------|
| 1–2 | Living burning hands |
| 3–4 | Living lightning bolt |
| 5 | Living cloudkill |
^living-spell-customization

Now make the following changes to that stat block:

**Damage Immunity**. Replace the living spell's damage immunity with immunity to the type (or types) of damage dealt by the chosen spell.

**Magical Strike**. Replace the damage that Magical Strike deals with one type of damage dealt by the chosen spell.

**Spell Mimicry**. Replace the effect of Spell Mimicry with the effect of the chosen spell. If that spell requires a saving throw, use spell save DC from the replaced spell, and if the spell involves an attack roll, use the attack bonus from the living spell's Magical Strike.

For example, if you turn [fireball](compendium/5e/spells/fireball.md) (a 3rd-level spell) into a living spell, customize the [living lightning bolt](compendium/5e/bestiary/construct/living-lightning-bolt-erlw.md). The living fireball has immunity to fire damage, instead of lightning damage; deals fire damage with its Magical Strike; and replicates [fireball](compendium/5e/spells/fireball.md) with Spell Mimicry.

## Statblock

```ad-statblock
title: Living Cloudkill
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Living%20Cloudkill.webp#token)
*Large construct, Unaligned*

- **Armor Class** 15 (natural armor)
- **Hit Points** 73 (`7d10 + 35`)
- **Speed** 25 ft., fly 25 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|15 (+2)|20 (+5)| 3 (-4)|11 (+0)| 6 (-2)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [blinded](rules/5e/conditions.md#Blinded), [charmed](rules/5e/conditions.md#Charmed), [deafened](rules/5e/conditions.md#Deafened), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [grappled](rules/5e/conditions.md#Grappled), [poisoned](rules/5e/conditions.md#Poisoned), [prone](rules/5e/conditions.md#Prone)
- **Languages** —
- **Challenge** 7

## Traits

***Amorphous.*** The living spell can move through a space as narrow as 1 inch wide without squeezing.

***Magic Resistance.*** The living spell has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The living spell makes two Magical Strike attacks.

***Magical Strike.*** *Melee Spell Attack:* `dice:1d20+8|noform|noparens|text(+8)` to hit, reach 10 ft., one target. *Hit:* `dice:5d6+5|noform|noparens|avg|text(22)` (`5d6 + 5`) poison damage.

***Spell Mimicry (Recharge 5-6).*** The living spell creates a 40-foot-diameter sphere of fog within 60 feet of it (the fog spreads around corners). When a creature enters the fog for the first time on a turn or starts its turn there, it must make a DC 16 Constitution saving throw, taking `dice:5d8|noform|noparens|avg|text(22)` (`5d8`) poison damage on a failed save, or half as much damage on a successful one.

The fog moves 10 feet away from the living spell at the start of each of its turns, rolling along the ground and through openings. The fog lasts for 10 minutes or until the living spell's [concentration](rules/5e/conditions.md#Concentration) ends (as if [concentrating](rules/5e/conditions.md#Concentration) on a spell).
```
^statblock