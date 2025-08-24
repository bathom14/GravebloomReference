---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/10
- 5e/monster/environment/any
- 5e/monster/size/large
- 5e/monster/type/construct
aliases:
- Stone Golem
---
# Stone Golem
*Source: Monster Manual (2024) p. 301. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Stone Golem

*Guardian of the Storied and Sacred*

- **Habitat.** Any  
- **Treasure.** None  

Stone golems take varied forms, such as weathered carvings of ancient deities, lifelike sculptures of heroes, or any other shape their makers imagine. No matter their design or the rock from which they're crafted, these golems are strengthened by the magic that animates them, allowing them to follow their creators' orders for centuries.

Stone golems are typically created to protect places of significance to a group, such as a monument to an important event, a leader's tomb, or a faith's sanctuary. Roll on or choose a result from the Stone Golem Orders table to inspire the commands a stone golem follows.

**Stone Golem Orders**

`dice: [](stone-golem.md#^stone-golem-orders)`

| dice: 1d6 | The Stone Golem Follows Orders To... |
|-----------|--------------------------------------|
| 1 | Allow only those wearing ritual garb to pass. |
| 2 | Cast [Slow](compendium/5e/spells/slow.md) on and aid in apprehending anyone who touches a city's prized relic. |
| 3 | Destroy a dam or bridge at the command of one bearing a ruler's medallion of office. |
| 4 | Obey whoever places a missing crest in its chest, then deactivate for a year. |
| 5 | Reveal a hidden passage to those who recite a leader's final words. |
| 6 | Watch for and do battle with the type of monster that slew the hero it resembles. |
^stone-golem-orders

> [!quote]  
> 
> Exercise discernment when deciding the golem's appearance, as your creation is likely to long outlive its model.


```ad-statblock
title: Stone Golem
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Stone%20Golem.webp#token)
*Large construct, Unaligned*

- **Armor Class** 18
- **Hit Points** 220 (`21d10 + 105`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)| 9 (-1)|20 (+5)| 3 (-4)|11 (+0)| 1 (-5)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 120 ft., passive Perception 10
- **Damage Immunities** poison, psychic
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [paralyzed](rules/5e/conditions.md#Paralyzed), [petrified](rules/5e/conditions.md#Petrified), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** understands Common plus two other languages but can't speak
- **Challenge** 10

## Traits

***Immutable Form.*** The golem can't shape-shift.

***Magic Resistance.*** The golem has [Advantage](rules/5e/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The golem makes two attacks, using Slam or Force Bolt in any combination.

***Slam.*** *Melee Attack Roll:* `dice:1d20+10|noform|noparens|text(+10)`, reach 5 ft. *Hit:* `dice:2d8+6|noform|noparens|avg|text(15)` (`2d8 + 6`) Bludgeoning damage plus `dice:2d8|noform|noparens|avg|text(9)` (`2d8`) Force damage.

***Force Bolt.*** *Ranged Attack Roll:* `dice:1d20+9|noform|noparens|text(+9)`, range 120 ft. *Hit:* `dice:4d10|noform|noparens|avg|text(22)` (`4d10`) Force damage.

## Bonus Actions

***Slow (Recharge 5-6).*** The golem casts the [Slow](compendium/5e/spells/slow.md) spell, requiring no spell components and using Constitution as the spellcasting ability (spell save DC 17).

```
^statblock

## Environment

any