---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mpmm
- 5e/monster/cr/3
- 5e/monster/size/medium
- 5e/monster/type/undead/warlock
aliases:
- Deathlock Wight
---
# Deathlock Wight
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 87, Mordenkainen's Tome of Foes p. 129*  

Deprived of much of its magic as a special punishment, a deathlock wight lingers between the warlock it was and the wretched existence of a wight.

## Deathlocks

The forging of a pact between a warlock and a patron is no minor occasion—at least not for the warlock. The consequences of breaking that pact can be dire and, in some cases, lethal. A warlock who fails to live up to a bargain with an evil patron runs the risk of rising from the dead as a deathlock, a foul Undead driven to serve its otherworldly patron.

An powerful necromancer might also discover the wicked methods of creating a deathlock and then subjugate it, acting as the deathlock's patron.

## Statblock

```ad-statblock
title: Deathlock Wight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Deathlock%20Wight.webp#token)
*Medium undead (warlock), Typically  Neutral Evil*

- **Armor Class** 12
- **Hit Points** 37 (`5d8 + 15`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|14 (+2)|16 (+3)|12 (+1)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +4
- **Skills** [Arcana](rules/5e/skills.md#Arcana) +3, [Perception](rules/5e/skills.md#Perception) +4
- **Senses** darkvision 60 ft., passive Perception 14
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](rules/5e/conditions.md#Exhaustion), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** the languages it knew in life
- **Challenge** 3

## Traits

***Sunlight Sensitivity.*** While in sunlight, the deathlock has disadvantage on attack rolls, as well as on Wisdom ([Perception](rules/5e/skills.md#Perception)) checks that rely on sight.

***Unusual Nature.*** The deathlock doesn't require air, food, drink, or sleep.

## Actions

***Multiattack.*** The deathlock makes two Life Drain or Grave Bolt attacks.

***Life Drain.*** *Melee Weapon Attack:* `dice:1d20+4|noform|noparens|text(+4)` to hit, reach 5 ft., one creature. *Hit:* `dice:1d8+2|noform|noparens|avg|text(6)` (`1d8 + 2`) necrotic damage. The target must succeed on a DC 13 Constitution saving throw, or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

A Humanoid slain by this attack rises 24 hours later as a [zombie](compendium/5e/bestiary/undead/zombie.md) under the deathlock's control, unless the Humanoid is restored to life or its body is destroyed. The deathlock can have no more than twelve zombies under its control at one time.

***Grave Bolt.*** *Ranged Spell Attack:* `dice:1d20+5|noform|noparens|text(+5)` to hit, range 60 ft., one target. *Hit:* `dice:2d8+3|noform|noparens|avg|text(12)` (`2d8 + 3`) necrotic damage.

***Spellcasting.*** The deathlock casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 13):

**At will:** [detect magic](compendium/5e/spells/detect-magic.md), [disguise self](compendium/5e/spells/disguise-self.md), [mage armor](compendium/5e/spells/mage-armor.md)

**1/day each:** [fear](compendium/5e/spells/fear.md), [hold person](compendium/5e/spells/hold-person.md)
```
^statblock