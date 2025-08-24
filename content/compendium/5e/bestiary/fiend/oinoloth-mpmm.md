---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mpmm
- 5e/monster/cr/12
- 5e/monster/environment/desert
- 5e/monster/environment/underdark
- 5e/monster/size/medium
- 5e/monster/type/fiend/yugoloth
aliases:
- Oinoloth
---
# Oinoloth
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 202, Mordenkainen's Tome of Foes p. 251*  

Grim specters of death, oinoloths bring pestilence wherever they go. When armies recognize their awful forms, their mere appearance causes soldiers to break ranks and flee, lest they succumb to one of the awful plagues that oinoloths let loose.

Oinoloths solve thorny problems by killing everyone involved. They are typically hired as a last resort when a siege has gone on too long or an army has proven too strong to overcome. Once summoned, oinoloths stalk the killing field, poisoning the ground and sickening creatures they encounter. Sometimes they might be hired to lift the very plagues they spread, but the price for such work is high, and the effort turns the creatures they save into debilitated wrecks.

```ad-statblock
title: Oinoloth
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Oinoloth.webp#token)
*Medium fiend (yugoloth), Typically  Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 119 (`14d8 + 56`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|17 (+3)|18 (+4)|17 (+3)|16 (+3)|19 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Wisdom +7
- **Skills** [Deception](rules/5e/skills.md#Deception) +8, [Intimidation](rules/5e/skills.md#Intimidation) +8, [Perception](rules/5e/skills.md#Perception) +7
- **Senses** blindsight 60 ft., darkvision 60 ft., passive Perception 17
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** Abyssal, Infernal, telepathy 60 ft.
- **Challenge** 12

## Traits

***Magic Resistance.*** The oinoloth has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The oinoloth makes two Claw attacks, and it uses Spellcasting or Teleport.

***Claw.*** *Melee Weapon Attack:* `dice:1d20+8|noform|noparens|text(+8)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+4|noform|noparens|avg|text(14)` (`3d6 + 4`) slashing damage plus `dice:4d10|noform|noparens|avg|text(22)` (`4d10`) necrotic damage.

***Corrupted Healing (Recharge 6).*** The oinoloth touches one willing creature within 5 feet of it. The target regains all its hit points. In addition, the oinoloth can end one disease on the target or remove one of the following conditions from it: [blinded](rules/5e/conditions.md#Blinded), [deafened](rules/5e/conditions.md#Deafened), [paralyzed](rules/5e/conditions.md#Paralyzed), or [poisoned](rules/5e/conditions.md#Poisoned). The target then gains 1 level of [exhaustion](rules/5e/conditions.md#Exhaustion), and its hit point maximum is reduced by `dice:2d6|noform|noparens|avg|text(7)` (`2d6`). This reduction can be removed only by a [wish](compendium/5e/spells/wish.md) spell or by casting [greater restoration](compendium/5e/spells/greater-restoration.md) on the target three times within the same hour. The target dies if its hit point maximum is reduced to 0.

***Teleport.*** The oinoloth teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.

***Spellcasting.*** The oinoloth casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 16):

**At will:** [darkness](compendium/5e/spells/darkness.md), [detect magic](compendium/5e/spells/detect-magic.md), [dispel magic](compendium/5e/spells/dispel-magic.md), [hold monster](compendium/5e/spells/hold-monster.md), [invisibility](compendium/5e/spells/invisibility.md) (self only)

**1/day each:** [feeblemind](compendium/5e/spells/befuddlement.md), [globe of invulnerability](compendium/5e/spells/globe-of-invulnerability.md)

## Bonus Actions

***Bringer of Plagues (Recharge 5-6).*** The oinoloth blights the area in a 30-foot-radius sphere centered on itself. The blight lasts for 24 hours. While the area is blighted, all normal plants there wither and die.

Furthermore, when a creature moves into the blighted area or starts its turn there, that creature must make a DC 16 Constitution saving throw. On a failed save, the creature takes `dice:4d6|noform|noparens|avg|text(14)` (`4d6`) poison damage and is [poisoned](rules/5e/conditions.md#Poisoned). On a successful save, the creature is immune to the oinoloth's Bringer of Plagues for the next 24 hours.

The [poisoned](rules/5e/conditions.md#Poisoned) creature can't regain hit points. After every 24 hours that elapse, the [poisoned](rules/5e/conditions.md#Poisoned) creature can repeat the saving throw. On a failed save, the creature's hit point maximum is reduced by `dice:1d10|noform|noparens|avg|text(5)` (`d10`). This reduction lasts until the poison ends, and the target dies if its hit point maximum is reduced to 0. The poison ends after the creature successfully saves against it three times.
```
^statblock

## Environment

desert, underdark