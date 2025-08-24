---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/17
- 5e/monster/environment/any
- 5e/monster/size/unknown
- 5e/monster/type/undead
aliases:
- Dracolich
---
# Dracolich
*Source: Monster Manual (2024) p. 102*  

## Dracolich

*Draconic Tyrant Reborn*

- **Habitat.** Any  
- **Treasure.** Any  

The vilest dragons seek to escape the grip of death, employing ageless secrets and blasphemous magic to become horrors called dracoliches. These deathless dragons bind their spirits to gems and magically animate their rotting corpses. Eventually becoming skeletal horrors, dracoliches continue the centuries-spanning plots they pursued in life, seek revenge on those that brought them low, and strive toward vicious goals they couldn't indulge in life.

Dracoliches combine the corrupt immortality of the undead with the legendary power of dragons. A dracolich retains a breath weapon, but it is a chilling necrotic blast. These terrors gradually sicken the land near their lairs and attract sinister followers—usually other undead or cultists seeking to revel in their terrible might. Living dragons of all types loathe and seek to destroy dracoliches, viewing them as distortions of draconic magic.

There are untold profane routes by which a dragon might become a dracolich. However one is created, a dracolich chooses a gem that becomes the anchor for its spirit and binds the deathless dragon to the world. So long as a dracolich is on the same plane of existence as its soul gem, the dracolich can survive the destruction of its physical body. Its spirit retreats into the gem if the dracolich's body is destroyed, and the monster might one day regain its terrifying form. Dracoliches often sequester their soul gems within meaningful treasure from their hoard or in unassuming baubles. Roll on or choose a result from the Dracolich Soul Gem Vessels table to inspire what holds a dracolich's soul gem.

**Dracolich Soul Gem Vessels**

`dice: [](dracolich.md#^dracolich-soul-gem-vessels)`

| dice: 1d10 | A Dracolich's Soul Gem Is Hidden In... |
|------------|----------------------------------------|
| 1 | Another dragon's treasure hoard. |
| 2 | The body of a servant or an ancestor. |
| 3 | The core of a dracolich's melted hoard. |
| 4 | A corrupted dragon egg. |
| 5 | A dragon horn a hero took as a trophy. |
| 6 | A nation's royal or religious treasure. |
| 7 | A powerful magic item. |
| 8 | A source of magical wonders, such as a giant tree or mystical pool. |
| 9 | The vault of an archdevil, a wicked god, or another extraplanar villain. |
| 10 | The weapon that slew the dracolich. |
^dracolich-soul-gem-vessels

### Dracolich Lairs

A dracolich lurks in a corrupted version of the lair it had in life.

> [!quote] A quote from Sammaster the Fallen's translation of The Chronicle of Years to Come  
> 
> And naught will be left save shattered thrones with no rulers. But the dead dragons shall rule the world entire...


```ad-statblock
title: Dracolich
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Dracolich.webp#token)
*Unknown undead, Lawful Evil*

- **Armor Class** 20
- **Hit Points** 225 (`18d12 + 108`)
- **Speed** 40 ft., burrow 30 ft., fly 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|25 (+7)|10 (+0)|23 (+6)|19 (+4)|15 (+2)|21 (+5)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +6, Wisdom +8
- **Skills** [Perception](rules/5e/skills.md#Perception) +14, [Stealth](rules/5e/skills.md#Stealth) +6
- **Senses** blindsight 60 ft., darkvision 120 ft., passive Perception 24
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [paralyzed](rules/5e/conditions.md#Paralyzed), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** Common, Draconic
- **Challenge** 17

## Traits

***Legendary Resistance (3/Day, or 4/Day in Lair).*** If the dracolich fails a saving throw, it can choose to succeed instead.

***Life Suppression.*** Creatures within 60 feet of the dracolich can't regain [Hit Points](rules/5e/variant-rules/hit-points-xphb.md).

***Magic Resistance.*** The dracolich has [Advantage](rules/5e/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

***Soul Gem.*** The dracolich has a magical gem. If the dracolich is destroyed while the gem is on the same plane of existence as it, the dracolich gains a new body in `dice:1d20|noform|noparens|avg` (`d20`) days, regaining all its [Hit Points](rules/5e/variant-rules/hit-points-xphb.md) and appearing within 5 feet of the gem.

The gem is a Tiny object that has AC 20; HP 50; and [Immunity](rules/5e/variant-rules/immunity-xphb.md) to Necrotic, Poison, and Psychic damage. The gem regains all its [Hit Points](rules/5e/variant-rules/hit-points-xphb.md) at the end of every turn, but it turns to dust if reduced to 0 [Hit Points](rules/5e/variant-rules/hit-points-xphb.md). If the gem is destroyed, the dracolich can create a new one by completing an 8-hour ritual using a gem worth 1,000+ GP and by expending 5,000 GP, which the ritual consumes.

## Actions

***Multiattack.*** The dracolich makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast [Ray of Sickness](compendium/5e/spells/ray-of-sickness.md) (level 2 version).

***Rend.*** *Melee Attack Roll:* `dice:1d20+13|noform|noparens|text(+13)`, reach 10 ft. *Hit:* `dice:2d10+7|noform|noparens|avg|text(18)` (`2d10 + 7`) Slashing damage plus `dice:1d8|noform|noparens|avg|text(4)` (`d8`) Necrotic damage.

***Necrotic Breath (Recharge 5-6).*** *Constitution Saving Throw:* DC 20, each creature in a 60-foot [Cone](rules/5e/variant-rules/cone-area-of-effect-xphb.md). *Failure:* `dice:8d12|noform|noparens|avg|text(52)` (`8d12`) Necrotic damage. *Success:* Half damage.

***Spellcasting.*** The dracolich casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 19, `dice:1d20+11|noform|noparens|text(+11)` to hit with spell attacks):

**At will:** [Detect Magic](compendium/5e/spells/detect-magic.md), [Ray of Sickness](compendium/5e/spells/ray-of-sickness.md) (level 2 version)

**1/day each:** [Create Undead](compendium/5e/spells/create-undead.md) (level 8 version), [Finger of Death](compendium/5e/spells/finger-of-death.md)

## Legendary Actions

***Pounce.*** The dracolich moves up to half its [Speed](rules/5e/variant-rules/speed-xphb.md), and it makes one Rend attack.

***Sickening Ray.*** The dracolich uses Spellcasting to cast [Ray of Sickness](compendium/5e/spells/ray-of-sickness.md) (level 2 version). The dracolich can't take this action again until the start of its next turn.

***Terrifying Presence.*** *Wisdom Saving Throw:* DC 19, each creature in a 30-foot [Emanation](rules/5e/variant-rules/emanation-area-of-effect-xphb.md) originating from the dracolich. *Failure:* `dice:2d10|noform|noparens|avg|text(11)` (`2d10`) Psychic damage, and the target has the [Frightened](rules/5e/conditions.md#Frightened) condition until the end of its next turn. *Failure or Success:* The dracolich can't take this action again until the start of its next turn.

![Dracolich](compendium/5e/bestiary/legendary-group/dracolich.md)
```
^statblock

## Environment

any