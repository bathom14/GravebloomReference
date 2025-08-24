---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/7
- 5e/monster/environment/forest
- 5e/monster/environment/swamp
- 5e/monster/environment/urban
- 5e/monster/size/huge
- 5e/monster/type/undead
aliases:
- Graveyard Revenant
---
# Graveyard Revenant
*Source: Monster Manual (2024) p. 260*  

Graveyard revenants possess dozens of bodies that combine to form grotesque masses. They take revenge on those responsible for mass deaths or institutions that callously ruin lives.

## Revenants

*Vengeance from beyond the Grave*

- **Habitat.** Forest, Swamp, Urban  
- **Treasure.** Any  

Wrathful spirits bent on revenge, revenants possess corpses and other materials, using them to seek justice or vent their rage on those who wronged them. Revenants refuse to rest until those they seek to punish are no more. If their bodies are destroyed, revenants claim new forms and continue their ruthless quests.

## Statblock

```ad-statblock
title: Graveyard Revenant
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Graveyard%20Revenant.webp#token)
*Huge undead, Neutral*

- **Armor Class** 14
- **Hit Points** 161 (`14d12 + 70`)
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|20 (+5)|14 (+2)|20 (+5)|13 (+1)|16 (+3)|18 (+4)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +8, Constitution +8, Wisdom +6, Charisma +7
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 13
- **Damage Resistances** necrotic, psychic
- **Damage Immunities** poison
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [paralyzed](rules/5e/conditions.md#Paralyzed), [petrified](rules/5e/conditions.md#Petrified), [poisoned](rules/5e/conditions.md#Poisoned), [stunned](rules/5e/conditions.md#Stunned), [unconscious](rules/5e/conditions.md#Unconscious)
- **Languages** Common plus two other languages
- **Challenge** 7

## Traits

***Undead Restoration.*** If the revenant dies, it revives 24 hours later unless [Dispel Evil and Good](compendium/5e/spells/dispel-evil-and-good.md) is cast on its remains. If it revives, it animates another group of corpses elsewhere on the same plane of existence; it now looks different but uses the same stat block and returns with all its [Hit Points](rules/5e/variant-rules/hit-points-xphb.md).

## Actions

***Multiattack.*** The revenant makes two Suffocate attacks.

***Suffocate.*** *Melee Attack Roll:* `dice:1d20+8|noform|noparens|text(+8)`, reach 10 ft. *Hit:* `dice:1d10+5|noform|noparens|avg|text(10)` (`1d10 + 5`) Bludgeoning damage plus `dice:3d6|noform|noparens|avg|text(10)` (`3d6`) Necrotic damage. If the target is a Large or smaller creature, it has the [Grappled](rules/5e/conditions.md#Grappled) condition (escape DC 15). Until the grapple ends, the target is suffocating. The revenant can have up to two targets [Grappled](rules/5e/conditions.md#Grappled) in this way at a time.

***Haunting Glare (Recharge 5-6).*** *Wisdom Saving Throw:* DC 15, each creature in a 30-foot [Emanation](rules/5e/variant-rules/emanation-area-of-effect-xphb.md) originating from the revenant. *Failure:* The target has the [Paralyzed](rules/5e/conditions.md#Paralyzed) condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
```
^statblock

## Environment

forest, swamp, urban