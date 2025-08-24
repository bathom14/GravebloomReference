---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/toa
- 5e/monster/cr/6
- 5e/monster/size/medium
- 5e/monster/type/construct
aliases:
- Spiked Tomb Guardian
---
# Spiked Tomb Guardian
*Source: Tomb of Annihilation p. 154*  

Adventurers who have perished inside the tomb are stitched together by tomb dwarves and bolted into suits of armor. Once complete, these shambling golems are released into the tomb to hunt intruders.

A tomb guardian is a flesh golem clad in plate armor, giving it AC 17

```ad-statblock
title: Spiked Tomb Guardian
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToA/Spiked%20Tomb%20Guardian.webp#token)
*Medium construct, Neutral*

- **Armor Class** 17
- **Hit Points** 93 (`11d8 + 44`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)| 9 (-1)|18 (+4)| 6 (-2)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +3
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** darkvision 60 ft., passive Perception 10
- **Damage Immunities** lightning; poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [paralyzed](rules/5e/conditions.md#Paralyzed), [petrified](rules/5e/conditions.md#Petrified), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 6

## Traits

***Berserk.*** Whenever the tomb guardian starts its turn with 40 hit points or fewer, roll a `dice:d6|noform|noparens|avg` (`d6`). On a 6, the tomb guardian goes berserk. On each of its turns while berserk, the tomb guardian attacks the nearest creature it can see. If no creature is near enough to move to and attack, the tomb guardian attacks an object, with preference for an object smaller than itself. Once the tomb guardian goes berserk, it continues to do so until it is destroyed or regains all its hit points. The golem's creator, if within 60 feet of the berserk tomb guardian, can try to calm it by speaking firmly and persuasively. The tomb guardian must be able to hear its creator, who must take an action to make a DC 15 Charisma ([Persuasion](rules/5e/skills.md#Persuasion)) check. If the check succeeds, the tomb guardian ceases being berserk. If it takes damage while still at 40 hit points or fewer, the tomb guardian might go berserk again.

***Aversion of Fire.*** If the tomb guardian takes fire damage, it has disadvantage on attack rolls and ability checks until the end of its next turn.

***Immutable Form.*** The tomb guardian is immune to any spell or effect that would alter its form.

***Lightning Absorption.*** Whenever the tomb guardian is subjected to lightning damage, it takes no damage and instead regains a number of hit points equal to the lightning damage dealt.

***Magic Resistance.*** The tomb guardian has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The golem's weapon attacks are magical.

***Chained.*** 
> [!note]
> This trait applies when two guardians are chained together.

A magical spiked chain that binds a pair of guardians together prevents them from moving more than 15 feet apart. Additionally, as long as the chain is intact, damage dealt to either guardian is divided evenly between them. The spiked chain can be attacked separately and has AC 18, a damage threshold of 10, 5 hit points, and immunity to poison and psychic damage. If the chain breaks, both tomb guardians instantly go berserk.

## Actions

***Multiattack.*** The tomb guardian makes two spiked gauntlet attacks.

***Spiked Gauntlet.*** *Melee Weapon Attack:* `dice:1d20+7|noform|noparens|text(+7)` to hit, reach 5 ft., one target. *Hit:* `dice:2d8+4|noform|noparens|avg|text(13)` (`2d8 + 4`) bludgeoning damage plus `dice:2d6|noform|noparens|avg|text(9)` (`2d6`) piercing damage.
```
^statblock