---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/2
- 5e/monster/environment/desert
- 5e/monster/environment/forest
- 5e/monster/environment/grassland
- 5e/monster/environment/hill
- 5e/monster/environment/mountain
- 5e/monster/environment/swamp
- 5e/monster/environment/underdark
- 5e/monster/environment/urban
- 5e/monster/size/medium
- 5e/monster/type/monstrosity
aliases:
- Swarm of Stirges
---
# Swarm of Stirges
*Source: Monster Manual (2024) p. 299*  

Swarms of stirges sometimes form in swamps and Underdark caverns, draining livestock and any other creatures that can't escape them.

## Stirges

*Notorious, Clinging Bloodsuckers*

- **Habitat.** Desert, Forest, Grassland, Hill, Mountain, Swamp, Underdark, Urban  
- **Treasure.** None  

Stirges are bat-size vermin with dagger-length proboscises that attach to other creatures and drain life from them. Stirges are most active at night and hide in shadowy places during the day. If disturbed, they take flight and defend themselves. Roll on or choose a result from the Stirge Roosts table to inspire where stirges might lurk.

**Stirge Roosts**

`dice: [](swarm-of-stirges.md#^stirge-roosts)`

| dice: 1d4 | Between Hunts, the Stirge Lurks In... |
|-----------|---------------------------------------|
| 1 | The attic or furniture of a ruined building. |
| 2 | A cave or narrow crevice. |
| 3 | A hollow tree or thicket. |
| 4 | The remains of a gigantic, dead creature. |
^stirge-roosts

## Statblock

```ad-statblock
title: Swarm of Stirges
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Swarm%20of%20Stirges.webp#token)
*Medium monstrosity, Unaligned*

- **Armor Class** 14
- **Hit Points** 36 (`8d8`)
- **Speed** 10 ft., fly 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 4 (-3)|16 (+3)|11 (+0)| 2 (-4)| 8 (-1)| 6 (-2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 9
- **Damage Resistances** bludgeoning, piercing, slashing
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [frightened](rules/5e/conditions.md#Frightened), [grappled](rules/5e/conditions.md#Grappled), [paralyzed](rules/5e/conditions.md#Paralyzed), [petrified](rules/5e/conditions.md#Petrified), [prone](rules/5e/conditions.md#Prone), [restrained](rules/5e/conditions.md#Restrained), [stunned](rules/5e/conditions.md#Stunned)
- **Languages** —
- **Challenge** 2

## Traits

***Swarm.*** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny creature. The swarm can't regain [Hit Points](rules/5e/variant-rules/hit-points-xphb.md) or gain [Temporary Hit Points](rules/5e/variant-rules/temporary-hit-points-xphb.md).

## Actions

***Swarm of Proboscises.*** *Melee Attack Roll:* `dice:1d20+5|noform|noparens|text(+5)`, reach 5 ft. *Hit:* `dice:2d10+3|noform|noparens|avg|text(14)` (`2d10 + 3`) Piercing damage, or `dice:1d10+3|noform|noparens|avg|text(8)` (`1d10 + 3`) Piercing damage if the swarm is [Bloodied](rules/5e/variant-rules/bloodied-xphb.md). If the target is a Medium or smaller creature in the swarm's space, the target has the [Grappled](rules/5e/conditions.md#Grappled) condition (escape DC 13). Until the grapple ends, the target takes `dice:2d6|noform|noparens|avg|text(7)` (`2d6`) Necrotic damage at the end of each of its turns.
```
^statblock

## Environment

desert, forest, grassland, hill, mountain, swamp, underdark, urban