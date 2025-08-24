---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/15
- 5e/monster/environment/underdark
- 5e/monster/environment/urban
- 5e/monster/size/small-or-medium
- 5e/monster/type/undead
aliases:
- Vampire Umbral Lord
---
# Vampire Umbral Lord
*Source: Monster Manual (2024) p. 318*  

Vampire umbral lords embrace their ties to the darkness, devoting themselves to sinister powers in exchange for access to forbidden magic.

## Vampires

*Blood-Sucking Lords of the Night*

- **Habitat.** Underdark, Urban  
- **Treasure.** Any  

Vampires disguise their accursed, immortal natures, passing as mortals to feed on the blood of the living. While the youngest vampires might be little more than bloodthirsty servants of their creators, the eldest possess incredible cunning and control over supernatural forces of the night.

Undead vampires lie dormant during the day, retreating to resting places hidden from foes and the sun's searing rays. Roll on or choose a result from the Vampire Resting Places table to inspire a vampire's grim sanctuary.

**Vampire Resting Places**

`dice: [](vampire-umbral-lord.md#^vampire-resting-places)`

| dice: 1d6 | The Vampire's Resting Place Is... |
|-----------|-----------------------------------|
| 1 | Among the roots of a dead tree. |
| 2 | At the bottom of a stagnant pool. |
| 3 | A coffin filled with grave dirt. |
| 4 | A large pot full of blood or vinegar. |
| 5 | A space accessible only by shape-shifting. |
| 6 | Within a statue or suit of armor. |
^vampire-resting-places

### Vampire Lairs

Vampires and vampire umbral lords create sanctuaries apart from the living, whether hidden in cosmopolitan cities or sequestered in ruins where they dwelled in life.

> [!quote] A quote from Astarion, Vampire Spawn  
> 
> Darling, you are simply delicious...


## Statblock

```ad-statblock
title: Vampire Umbral Lord
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Vampire%20Umbral%20Lord.webp#token)
*Small or Medium undead, Lawful Evil*

- **Armor Class** 16
- **Hit Points** 187 (`22d8 + 88`)
- **Speed** 40 ft., climb 40 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|18 (+4)|18 (+4)|19 (+4)|16 (+3)|21 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +10, Dexterity +9, Wisdom +8, Charisma +10
- **Skills** [Arcana](rules/5e/skills.md#Arcana) +9, [Perception](rules/5e/skills.md#Perception) +13, [Stealth](rules/5e/skills.md#Stealth) +9
- **Senses** blindsight 120 ft., passive Perception 23
- **Damage Immunities** cold, necrotic
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [exhaustion](rules/5e/conditions.md#Exhaustion)
- **Languages** Common plus three other languages
- **Challenge** 15

## Traits

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the vampire fails a saving throw, it can choose to succeed instead.

***Shadow Escape.*** If the vampire drops to 0 [Hit Points](rules/5e/variant-rules/hit-points-xphb.md) outside its resting place, it teleports into its resting place unless it is in running water or sunlight. If it can't teleport, it is destroyed. Once inside its resting place, it has the [Paralyzed](rules/5e/conditions.md#Paralyzed) condition for 1 hour, after which it regains 1 [Hit Point](rules/5e/variant-rules/hit-points-xphb.md).

***Vampire Weakness.*** The vampire has these weaknesses:

- **Forbiddance.** The vampire can't enter a residence without an invitation from an occupant.  
- **Running Water.** The vampire takes 20 Acid damage if it ends its turn in running water.  
- **Stake to the Heart.** If a weapon that deals Piercing damage is driven into the vampire's heart while the vampire has the [Incapacitated](rules/5e/conditions.md#Incapacitated) condition in its resting place, the vampire has the [Paralyzed](rules/5e/conditions.md#Paralyzed) condition until the weapon is removed.  
- **Sunlight.** The vampire takes 20 Radiant damage if it starts its turn in sunlight. While in sunlight, it has [Disadvantage](rules/5e/variant-rules/disadvantage-xphb.md) on attack rolls and ability checks.  

## Actions

***Multiattack.*** The vampire makes two attacks, using Grave Strike or Sickening Ray in any combination.

***Grave Strike.*** *Melee Attack Roll:* `dice:1d20+10|noform|noparens|text(+10)`, reach 5 ft. *Hit:* `dice:1d8+5|noform|noparens|avg|text(9)` (`1d8 + 5`) Slashing damage plus `dice:3d8|noform|noparens|avg|text(13)` (`3d8`) Necrotic damage.

***Sickening Ray.*** *Ranged Attack Roll:* `dice:1d20+10|noform|noparens|text(+10)`, range 120 ft. *Hit:* `dice:2d10+5|noform|noparens|avg|text(16)` (`2d10 + 5`) Necrotic damage, and the target has the [Poisoned](rules/5e/conditions.md#Poisoned) condition until the start of the vampire's next turn.

***Hunger of Hadar (Recharge 5-6).*** The vampire casts [Hunger of Hadar](compendium/5e/spells/hunger-of-hadar.md) (level 5 version), requiring no spell components and using Charisma as the spellcasting ability (spell save DC 18).


## Bonus Actions

***Sanguine Drain.*** *Constitution Saving Throw:* DC 18, one creature the vampire can see within 30 feet that isn't a Construct or an Undead. *Failure:* `dice:4d6|noform|noparens|avg|text(14)` (`4d6`) Necrotic damage. The target's [Hit Point](rules/5e/variant-rules/hit-points-xphb.md) maximum decreases by an amount equal to the damage taken, and the vampire regains [Hit Points](rules/5e/variant-rules/hit-points-xphb.md) equal to that amount.

## Legendary Actions

***Umbral Strike.*** The vampire moves up to half its [Speed](rules/5e/variant-rules/speed-xphb.md), and it makes one Grave Strike or Sickening Ray attack.

***Beguile.*** The vampire casts [Command](compendium/5e/spells/command.md), requiring no spell components and using Charisma as the spellcasting ability (spell save DC 18). The vampire can't take this action again until the start of its next turn.


![Vampire](compendium/5e/bestiary/legendary-group/vampire.md)
```
^statblock

## Environment

underdark, urban