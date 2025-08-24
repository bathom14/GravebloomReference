---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/1-2
- 5e/monster/environment/elemental
- 5e/monster/environment/planar
- 5e/monster/size/small
- 5e/monster/type/elemental
aliases:
- Ice Mephit
---
# Ice Mephit
*Source: Monster Manual (2024) p. 206, Dragon Delves. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

Ice mephits have bodies made of frigid air and frozen water. They delight in freezing things and dropping ice into peoples' clothes.

## Mephits

*Malicious Elemental Hooligans*

- **Habitat.** Planar (Elemental Planes)  
- **Treasure.** None  

Mephits are mean-spirited tricksters that dwell on the Elemental Planes. The six most prominent types of mephits resemble halfling-size gargoyles with wings, exaggerated features, and bodies composed of two elements. Most live self-interested existences, indulging their warped senses of humor or overblown egos on their home planes of existence. Some serve as messengers or spies for genies or magic-users.

Mephits resent leaving the elemental extremes where they make their homes. If loosed on the Material Plane or other realms, they lash out with nasty pranks or by tormenting weaker creatures. When destroyed, mephits explode in a burst of elemental magic.

> [!quote] A quote from Seamusxanthuszenus, smoke mephit with a typically inflated impression of itself  
> 
> I am Seamusxanthuszenus, Slayer of Fiends, Merchant Most Excellent, Purveyor of Death!


## Statblock

```ad-statblock
title: Ice Mephit
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Ice%20Mephit.webp#token)
*Small elemental, Neutral Evil*

- **Armor Class** 11
- **Hit Points** 21 (`6d6`)
- **Speed** 30 ft., fly 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)|13 (+1)|10 (+0)| 9 (-1)|11 (+0)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Perception](rules/5e/skills.md#Perception) +2, [Stealth](rules/5e/skills.md#Stealth) +3
- **Senses** darkvision 60 ft., passive Perception 12
- **Damage Vulnerabilities** fire
- **Damage Immunities** cold, poison
- **Condition Immunities** [exhaustion](rules/5e/conditions.md#Exhaustion), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** Primordial (Aquan, Auran)
- **Challenge** 1/2

## Traits

***Death Burst.*** The mephit explodes when it dies. *Constitution Saving Throw:* DC 10, each creature in a 5-foot [Emanation](rules/5e/variant-rules/emanation-area-of-effect-xphb.md) originating from the mephit. *Failure:* `dice:2d4|noform|noparens|avg|text(5)` (`2d4`) Cold damage. *Success:* Half damage.

## Actions

***Claw.*** *Melee Attack Roll:* `dice:1d20+3|noform|noparens|text(+3)`, reach 5 ft. *Hit:* `dice:1d4+1|noform|noparens|avg|text(3)` (`1d4 + 1`) Slashing damage plus `dice:1d4|noform|noparens|avg|text(2)` (`d4`) Cold damage.

***Frost Breath (Recharge 6).*** *Constitution Saving Throw:* DC 10, each creature in a 15-foot [Cone](rules/5e/variant-rules/cone-area-of-effect-xphb.md). *Failure:* `dice:3d4|noform|noparens|avg|text(7)` (`3d4`) Cold damage. *Success:* Half damage.

***Fog Cloud (1/Day).*** The mephit casts [Fog Cloud](compendium/5e/spells/fog-cloud.md), requiring no spell components and using Charisma as the spellcasting ability.

```
^statblock

## Environment

planar, elemental