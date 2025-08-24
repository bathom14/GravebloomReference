---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/erlw
- 5e/monster/cr/0
- 5e/monster/size/medium
- 5e/monster/type/humanoid/any-race
aliases:
- Magewright
---
# Magewright
*Source: Eberron: Rising from the Last War p. 318*  

In Khorvaire, magic is part of everyday life. A chef might use [prestidigitation](compendium/5e/spells/prestidigitation.md) to heat and season food, while a blacksmith uses [mending](compendium/5e/spells/mending.md) to perform minor repairs and [guidance](compendium/5e/spells/guidance.md) to help inspire their work. Those who work minor magic into their labors are called magewrights.

Far more limited in magical power than a typical spellcaster, a magewright is dedicated to learning a handful of spells, and magewrights cast their non-cantrip spells as rituals—even spells that can't normally be cast in this way. Most magewright rituals take 10 minutes to perform, but certain complex rituals can take up to 1 hour. However long the ritual takes, it requires extra material components, usually in the form of dragonshards.

## Creating a Magewright

The magewright stat block provides the baseline statistics for a magewright. You then add to that baseline by choosing a specialty from the Magewright Specialties table, or roll for one. The specialty determines additional spells the magewright knows, including ones that can be cast only as rituals. The specialty also gives the magewright more proficiencies.

**Magewright Specialties**

`dice: [](magewright-erlw.md#^magewright-specialties)`

| dice: d8 | Specialty | Spells | Proficiencies |
|----------|-----------|--------|---------------|
| 1 | Artisan | [Guidance](compendium/5e/spells/guidance.md), [mending](compendium/5e/spells/mending.md) | One type of artisan's tools |
| 2 | Entertainer | [Minor illusion](compendium/5e/spells/minor-illusion.md), [thaumaturgy](compendium/5e/spells/thaumaturgy.md). Ritual only: [disguise self](compendium/5e/spells/disguise-self.md). | [Performance](rules/5e/skills.md#Performance) (+3) |
| 3 | Healer | [Resistance](compendium/5e/spells/resistance.md), [spare the dying](compendium/5e/spells/spare-the-dying.md). Ritual only: [detect poison and disease](compendium/5e/spells/detect-poison-and-disease.md), [lesser restoration](compendium/5e/spells/lesser-restoration.md) (1 hour). | [Medicine](rules/5e/skills.md#Medicine) (+4), [herbalism kit](compendium/5e/items/herbalism-kit.md) |
| 4 | Lamplighter | [Light](compendium/5e/spells/light.md). Ritual only: [continual flame](compendium/5e/spells/continual-flame.md) (1 hour). | [Tinker's tools](compendium/5e/items/tinkers-tools.md) |
| 5 | Locksmith | [Mending](compendium/5e/spells/mending.md). Ritual only: [arcane lock](compendium/5e/spells/arcane-lock.md) (1 hour), [knock](compendium/5e/spells/knock.md). | [Thieves' tools](compendium/5e/items/thieves-tools.md), [tinker's tools](compendium/5e/items/tinkers-tools.md) |
| 6 | Mediator | [Guidance](compendium/5e/spells/guidance.md). Ritual only: [comprehend languages](compendium/5e/spells/comprehend-languages.md), [zone of truth](compendium/5e/spells/zone-of-truth.md). | [Insight](rules/5e/skills.md#Insight) (+4), [Persuasion](rules/5e/skills.md#Persuasion) (+3) |
| 7 | Medium | [Minor illusion](compendium/5e/spells/minor-illusion.md). Ritual only: [speak with dead](compendium/5e/spells/speak-with-dead.md). | [Deception](rules/5e/skills.md#Deception) (+3), [Religion](rules/5e/skills.md#Religion) (+4) |
| 8 | Oracle | [Guidance](compendium/5e/spells/guidance.md). Ritual only: [augury](compendium/5e/spells/augury.md), [divination](compendium/5e/spells/divination.md) (1 hour). | [History](rules/5e/skills.md#History) (+4), [Religion](rules/5e/skills.md#Religion) (+4) |
^magewright-specialties

## Statblock

```ad-statblock
title: Magewright
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ERLW/Magewright.webp#token)
*Medium humanoid (any race), Any alignment*

- **Armor Class** 11
- **Hit Points** 9 (`2d8`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|13 (+1)|10 (+0)|14 (+2)|14 (+2)|12 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Arcana](rules/5e/skills.md#Arcana) +4
- **Senses** passive Perception 12
- **Languages** Common plus any two languages
- **Challenge** 0

## Traits

***Spellcasting.*** The magewright's spellcasting ability is Intelligence (spell save DC 12). To cast one of its rituals, the magewright must provide additional material components whose value in gold pieces is 20 times the spell's level. These components are consumed when the ritual is finished. The magewright knows the following spells:

**At will:** [mage hand](compendium/5e/spells/mage-hand.md), [prestidigitation](compendium/5e/spells/prestidigitation.md)

**Rituals:** [knock](compendium/5e/spells/knock.md)

## Actions

***Dagger.*** *Melee  or Ranged Weapon Attack:* `dice:1d20+3|noform|noparens|text(+3)` to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* `dice:1d4+1|noform|noparens|avg|text(3)` (`1d4 + 1`) piercing damage.
```
^statblock