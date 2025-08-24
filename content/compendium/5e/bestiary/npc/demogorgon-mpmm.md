---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mpmm
- 5e/monster/cr/26
- 5e/monster/size/huge
- 5e/monster/type/fiend/demon
aliases:
- Demogorgon
---
# Demogorgon
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 90, Mordenkainen's Tome of Foes p. 144*  

> [!quote] A quote from Mordenkainen  
> 
> Are two heads better than one? In Demogorgon's case, the two double the horror and the chaos.

Prince of Demons, the Sibilant Beast, and Master of the Spiraling Depths, Demogorgon is the embodiment of chaos, confusion, and destruction, seeking to corrupt all that is good and undermine order in the multiverse, to see everything dragged howling into the infinite depths of the Abyss.

The demon lord is a meld of different forms. He has a saurian lower body and clawed, webbed feet; suckered tentacles sprout from the shoulders of his great apelike torso, which is surmounted by two hideous simian heads named Aameul and Hathradiah. Their gaze brings bewilderment and confusion to any who confront them.

Similarly, the spiraling Y sign of Demogorgon's cult drives those who contemplate it for too long to delirium. As a result, all followers of the Prince of Demons break with reality sooner or later.

## Cultists of Demogorgon

> [!note]
> See the Cult of Demogorgon entry.

## Demogorgon's Lair

Demogorgon makes his lair in a palace called Abysm, found on a layer of the Abyss known as the Gaping Maw. Demogorgon's lair is a place of confusion and duality; the portion of the palace that lies above water takes the form of two serpentine towers, each crowned by a skull-shaped minaret. There, Demogorgon's heads contemplate the mysteries of the arcane while arguing about how best to obliterate their rivals. The bulk of this palace extends deep underwater, in chill and darkened caverns.

## Statblock

```ad-statblock
title: Demogorgon
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPMM/Demogorgon.webp#token)
*Huge fiend (demon), Chaotic Evil*

- **Armor Class** 22 (natural armor)
- **Hit Points** 464 (`32d12 + 256`)
- **Speed** 50 ft., swim 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|29 (+9)|14 (+2)|26 (+8)|20 (+5)|17 (+3)|25 (+7)|

- **Proficiency Bonus** +8
- **Saving Throws** Dexterity +10, Constitution +16, Wisdom +11, Charisma +15
- **Skills** [Insight](rules/5e/skills.md#Insight) +11, [Perception](rules/5e/skills.md#Perception) +19
- **Senses** truesight 120 ft., passive Perception 29
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** poison; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 26

## Traits

***Legendary Resistance (3/Day).*** If Demogorgon fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Demogorgon has advantage on saving throws against spells and other magical effects.

***Two Heads.*** Demogorgon has advantage on saving throws against being [blinded](rules/5e/conditions.md#Blinded), [deafened](rules/5e/conditions.md#Deafened), [stunned](rules/5e/conditions.md#Stunned), or knocked [unconscious](rules/5e/conditions.md#Unconscious).

## Actions

***Multiattack.*** Demogorgon makes two Tentacle attacks. He can replace one attack with a use of Gaze.

***Tentacle.*** *Melee Weapon Attack:* `dice:1d20+17|noform|noparens|text(+17)` to hit, reach 10 ft., one target. *Hit:* `dice:3d12+9|noform|noparens|avg|text(28)` (`3d12 + 9`) force damage. If the target is a creature, it must succeed on a DC 23 Constitution saving throw, or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.

***Gaze.*** Demogorgon turns his magical gaze toward one creature he can see within 120 feet of him. The target must succeed on a DC 23 Wisdom saving throw or suffer one of the following effects (choose one or roll a `dice:d6|noform|noparens|avg` (`d6`)):

- **1–2 Beguiling Gaze.** The target is [stunned](rules/5e/conditions.md#Stunned) until the start of Demogorgon's next turn or until Demogorgon is no longer within line of sight.  
- **3–4 Confusing Gaze.** The target suffers the effect of the [confusion](compendium/5e/spells/confusion.md) spell without making a saving throw. The effect lasts until the start of Demogorgon's next turn. Demogorgon doesn't need to concentrate on the spell.  
- **5–6 Hypnotic Gaze.** The target is [charmed](rules/5e/conditions.md#Charmed) by Demogorgon until the start of Demogorgon's next turn. Demogorgon chooses how the [charmed](rules/5e/conditions.md#Charmed) target uses its action, reaction, and movement.  

***Spellcasting.*** Demogorgon casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 23):

**At will:** [detect magic](compendium/5e/spells/detect-magic.md), [major image](compendium/5e/spells/major-image.md)

**3/day each:** [dispel magic](compendium/5e/spells/dispel-magic.md), [fear](compendium/5e/spells/fear.md), [telekinesis](compendium/5e/spells/telekinesis.md)

**1/day each:** [feeblemind](compendium/5e/spells/befuddlement.md), [project image](compendium/5e/spells/project-image.md)

## Legendary Actions

***Gaze.*** Demogorgon uses Gaze and must use either Beguiling Gaze or Confusing Gaze.

***Tail.*** *Melee Weapon Attack:* `dice:1d20+17|noform|noparens|text(+17)` to hit, reach 15 ft., one target. *Hit:* `dice:2d10+9|noform|noparens|avg|text(20)` (`2d10 + 9`) bludgeoning damage plus `dice:2d10|noform|noparens|avg|text(11)` (`2d10`) necrotic damage.

***Cast a Spell (Costs 2 Actions).*** Demogorgon uses Spellcasting.

![Demogorgon](compendium/5e/bestiary/legendary-group/demogorgon-mpmm.md)
```
^statblock