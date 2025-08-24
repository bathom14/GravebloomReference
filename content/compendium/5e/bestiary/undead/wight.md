---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/3
- 5e/monster/environment/desert
- 5e/monster/environment/planar
- 5e/monster/environment/shadowfell
- 5e/monster/environment/swamp
- 5e/monster/environment/underdark
- 5e/monster/environment/urban
- 5e/monster/size/medium
- 5e/monster/type/undead
aliases:
- Wight
---
# Wight
*Source: Monster Manual (2024) p. 332. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Wight

*Life-Leeching Corpse Warrior*

- **Habitat.** Desert, Planar (Shadowfell), Swamp, Underdark, Urban  
- **Treasure.** Armaments  

Wights are the withered corpses of relentless warriors whose wickedness sustains them beyond death. Unlike mere zombies, they retain the memories and evil agendas they harbored in life.

After dying and returning from the grave, a wight continues its villainous ways, but it is now driven by a hunger for life. A wight drains living essence through its attacks. Humanoids slain by a wight's life-sapping grip reanimate a day later and serve the wight as obedient zombies.

Wights might return from the dead for a multitude of sinister reasons. Roll on or choose a result from the Wight Motives table to inspire why a wight plagues the living.

**Wight Motives**

`dice: [](wight.md#^wight-motives)`

| dice: 1d8 | The Wight Returned from the Dead To... |
|-----------|----------------------------------------|
| 1 | Challenge anyone who passes near its grave on a certain cursed night. |
| 2 | Conquer the land it believes it should rule. |
| 3 | Continue the crimes it was executed for. |
| 4 | Follow the foul master it served in life. |
| 5 | Honor an oath it left unfulfilled in life. |
| 6 | Obey the cult or deity that gave it unlife. |
| 7 | Prove it was the greatest warrior to ever live. |
| 8 | Seek its stolen heart or other treasure. |
^wight-motives

```ad-statblock
title: Wight
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Wight.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14
- **Hit Points** 82 (`11d8 + 33`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|14 (+2)|16 (+3)|10 (+0)|13 (+1)|15 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Perception](rules/5e/skills.md#Perception) +3, [Stealth](rules/5e/skills.md#Stealth) +4
- **Senses** darkvision 60 ft., passive Perception 13
- **Damage Resistances** necrotic
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](rules/5e/conditions.md#Exhaustion), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** Common plus one other language
- **Challenge** 3

## Traits

***Sunlight Sensitivity.*** While in sunlight, the wight has [Disadvantage](rules/5e/variant-rules/disadvantage-xphb.md) on ability checks and attack rolls.

## Actions

***Multiattack.*** The wight makes two attacks, using Necrotic Sword or Necrotic Bow in any combination. It can replace one attack with a use of Life Drain.

***Necrotic Sword.*** *Melee Attack Roll:* `dice:1d20+4|noform|noparens|text(+4)`, reach 5 ft. *Hit:* `dice:1d8+2|noform|noparens|avg|text(6)` (`1d8 + 2`) Slashing damage plus `dice:1d8|noform|noparens|avg|text(4)` (`d8`) Necrotic damage.

***Necrotic Bow.*** *Ranged Attack Roll:* `dice:1d20+4|noform|noparens|text(+4)`, range 150/600 ft. *Hit:* `dice:1d8+2|noform|noparens|avg|text(6)` (`1d8 + 2`) Piercing damage plus `dice:1d8|noform|noparens|avg|text(4)` (`d8`) Necrotic damage.

***Life Drain.*** *Constitution Saving Throw:* DC 13, one creature within 5 feet. *Failure:* `dice:1d8+2|noform|noparens|avg|text(6)` (`1d8 + 2`) Necrotic damage, and the target's [Hit Point](rules/5e/variant-rules/hit-points-xphb.md) maximum decreases by an amount equal to the damage taken.

A Humanoid slain by this attack rises 24 hours later as a [Zombie](compendium/5e/bestiary/undead/zombie.md) under the wight's control, unless the Humanoid is restored to life or its body is destroyed. The wight can have no more than twelve zombies under its control at a time.
```
^statblock

## Environment

desert, planar, shadowfell, swamp, underdark, urban