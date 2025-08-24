---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/11
- 5e/monster/environment/arctic
- 5e/monster/environment/coastal
- 5e/monster/environment/desert
- 5e/monster/environment/hill
- 5e/monster/environment/mountain
- 5e/monster/size/gargantuan
- 5e/monster/type/monstrosity
aliases:
- Roc
---
# Roc
*Source: Monster Manual (2024) p. 261, Dragon Delves. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Roc

*Avian of Unbelievable Size*

- **Habitat.** Arctic, Coastal, Desert, Hill, Mountain  
- **Treasure.** Any  

Birds of prey of fantastic scale, rocs hunt over vast territories and can snatch whole elephants, whales, or wagons in their talons. They then carry their prey back to their remote nests, journeys that can take days and cover hundreds of miles.

Rocs nest amid remote heights. Their nests are typically littered with treasure and uneaten prey. Roll on or choose an option from the Roc Nest Remnants table to inspire what's in a roc's nest.

**Roc Nest Remnants**

`dice: [](roc.md#^roc-nest-remnants)`

| dice: 1d6 | The Roc's Nest Holds... |
|-----------|-------------------------|
| 1 | The burial litter of a lost hero. |
| 2 | A caravan wagon full of trade goods. |
| 3 | A live elephant. |
| 4 | `dice:1d4\|noform\|noparens\|avg` (`d4`) eggs larger than adult humans. |
| 5 | Someone marooned in the nest. |
| 6 | A statue of a knight riding a rearing steed. |
^roc-nest-remnants

```ad-statblock
title: Roc
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Roc.webp#token)
*Gargantuan monstrosity, Unaligned*

- **Armor Class** 15
- **Hit Points** 248 (`16d20 + 80`)
- **Speed** 20 ft., fly 120 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|28 (+9)|10 (+0)|20 (+5)| 3 (-4)|10 (+0)| 9 (-1)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +4, Wisdom +4
- **Skills** [Perception](rules/5e/skills.md#Perception) +8
- **Senses** passive Perception 18
- **Languages** —
- **Challenge** 11

## Actions

***Multiattack.*** The roc makes two Beak attacks. It can replace one attack with a Talons attack.

***Beak.*** *Melee Attack Roll:* `dice:1d20+13|noform|noparens|text(+13)`, reach 10 ft. *Hit:* `dice:3d12+9|noform|noparens|avg|text(28)` (`3d12 + 9`) Piercing damage.

***Talons.*** *Melee Attack Roll:* `dice:1d20+13|noform|noparens|text(+13)`, reach 5 ft. *Hit:* `dice:4d6+9|noform|noparens|avg|text(23)` (`4d6 + 9`) Slashing damage. If the target is a Huge or smaller creature, it has the [Grappled](rules/5e/conditions.md#Grappled) condition (escape DC 19) from both talons, and it has the [Restrained](rules/5e/conditions.md#Restrained) condition until the grapple ends.

## Bonus Actions

***Swoop (Recharge 5-6).*** If the roc has a creature [Grappled](rules/5e/conditions.md#Grappled), the roc flies up to half its [Fly Speed](rules/5e/variant-rules/fly-speed-xphb.md) without provoking [Opportunity Attacks](rules/5e/actions.md#Opportunity%20Attack) and drops that creature.
```
^statblock

## Environment

arctic, coastal, desert, hill, mountain