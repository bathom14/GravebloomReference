---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/ggr
- 5e/monster/cr/14
- 5e/monster/size/medium
- 5e/monster/type/celestial
aliases:
- Deathpact Angel
---
# Deathpact Angel
*Source: Guildmasters' Guide to Ravnica p. 192*  

Deathpact angels dwell in the grandest of Orzhov cathedrals, where they surround themselves with wealth and wretched vassals that are utterly in their thrall.

## Gift Givers

Posing as a beneficent god, a deathpact angel attracts petitioners who beg the angel for blessings: wealth, prestige, health, revenge, and the like. Imagining itself generous and merciful, the angel usually tries to grant the petitioners what they seek by using its abilities, drawing from its hoard of riches, or extorting favors from other members of the guild. True to the spirit of the Orzhov, though, the angel doesn't bestow these gifts out of kindness, but for the sake of gaining fanatical followers who owe it life debts.

## Debt and Indenture

Those who receive favors from a deathpact angel incur a debt that they carry with fervent devotion. They regularly bring trinkets and offerings to the angel, no longer asking or expecting anything in return, and even willingly offer up their mortal lives for their angelic patron. Even after death, these debtors continue to serve the angel and the Orzhov Syndicate as indentured spirits (described later in this chapter).

Debts Paid

## Orzhov Angels

Few angels find anything appealing in the corruption and decadence embodied by the Orzhov Syndicate, since such a society is fundamentally antithetical to their natures, but disillusionment can seduce even immortal beings. When cynicism takes root in an angel's heart, when questions undermine devotion to the cause of justice, when strength becomes a tool to lord over the weak, the Orzhov Syndicate is there to welcome the angel with open arms, offering status, respect, and power.

Orzhov angels might claim positions as executioners, commanders, or power brokers, but more often they carve out their own place in the guild, standing apart from the otherwise rigid hierarchy of the Orzhov.

## Statblock

```ad-statblock
title: Deathpact Angel
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Deathpact%20Angel.webp#token)
*Medium celestial, Lawful Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 175 (`27d8 + 54`)
- **Speed** 30 ft., fly 90 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|18 (+4)|14 (+2)|19 (+4)|20 (+5)|23 (+6)|

- **Proficiency Bonus** +5
- **Saving Throws** Intelligence +9, Wisdom +10, Charisma +11
- **Skills** [Insight](rules/5e/skills.md#Insight) +10, [Intimidation](rules/5e/skills.md#Intimidation) +11, [Perception](rules/5e/skills.md#Perception) +10, [Persuasion](rules/5e/skills.md#Persuasion) +11
- **Senses** truesight 120 ft., passive Perception 20
- **Damage Resistances** necrotic; radiant; bludgeoning, piercing, slashing from nonmagical attacks
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened)
- **Languages** all
- **Challenge** 14

## Traits

***Innate Spellcasting.*** The angel's innate spellcasting ability is Charisma (spell save DC 19, `dice:1d20+11|noform|noparens|text(+11)` to hit with spell attacks). The angel can innately cast the following spells, requiring no material components:

**At will:** [command](compendium/5e/spells/command.md) (as a 2nd-level spell), [detect evil and good](compendium/5e/spells/detect-evil-and-good.md)

**3/day each:** [charm person](compendium/5e/spells/charm-person.md) (as a 5th-level spell), [darkness](compendium/5e/spells/darkness.md), [suggestion](compendium/5e/spells/suggestion.md)

**1/day:** [raise dead](compendium/5e/spells/raise-dead.md)

***Exploitation of the Debtors.*** As a bonus action, the angel targets a creature [charmed](rules/5e/conditions.md#Charmed) by it that it can see within 30 feet of it. The angel deals `dice:2d10|noform|noparens|avg|text(11)` (`2d10`) necrotic damage to the target, and the angel gains temporary hit points equal to the damage dealt.

***Flyby.*** The angel doesn't provoke an opportunity attack when it flies out of an enemy's reach.

***Magic Resistance.*** The angel has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The angel makes two attacks with its scythe. It can substitute Chains of Obligation for one of these attacks.

***Scythe.*** *Melee Weapon Attack:* `dice:1d20+9|noform|noparens|text(+9)` to hit, reach 10 ft., one target. *Hit:* `dice:2d4+4|noform|noparens|avg|text(9)` (`2d4 + 4`) slashing damage plus `dice:6d8|noform|noparens|avg|text(27)` (`6d8`) necrotic damage.

***Chains of Obligation.*** The angel targets one creature [charmed](rules/5e/conditions.md#Charmed) by it that it can see within 90 feet of it. The target must succeed on a DC 19 Charisma saving throw or become [paralyzed](rules/5e/conditions.md#Paralyzed) for 1 minute or until it takes any damage.
```
^statblock