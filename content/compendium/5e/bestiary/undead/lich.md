---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/21
- 5e/monster/environment/any
- 5e/monster/size/medium
- 5e/monster/type/undead/wizard
aliases:
- Lich
---
# Lich
*Source: Monster Manual (2024) p. 196, Dragon Delves. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Lich

*Deathless Master of Magic*

- **Habitat.** Any  
- **Treasure.** Arcana  

Some nefarious magic-users carry out forbidden necromantic rituals that sever their souls from their bodies to turn themselves into liches, masters of magic and undeath. With their souls preserved in hidden relics, liches puppet their own corpses as they pursue ambitions free from mortal bonds.

Liches possess exceptional cunning and magical prowess, and they use their unnatural immortality to pursue arcane secrets few could grasp in a single life. Uncanny agendas lead them to plumb the secrets of life, the multiverse, godhood, and less fathomable topics. Careless of mortal lives or desires, liches go to any lengths to achieve their goals.

A lich's age and origin influences its form. Older liches appear as little more than brittle skeletons clad in the rotten finery of forgotten empires, while younger liches more closely resemble living creatures and are clad in contemporary garb. Many cloak themselves in illusions of their idealized mortal forms.

Although liches don't fear death, they're not free from the ravages of time. Over ages, some liches lose their connection to time and the physical world, degenerating into demiliches.

### Lich Spirit Jars

The process of becoming a lich is involved, dangerous, and unique to each would-be lich. If the rite succeeds, the lich's soul is bound to a spirit jar, a specially prepared magical repository. This relic anchors the lich's spirit to the world and preserves it should the lich's body be destroyed. A lich can be slain only if its spirit jar is ruined. As such, a lich goes to great lengths to hide and protect its spirit jar.

Spirit jars are typically small, well-made objects that were meaningful to a lich in life. Roll on or choose a result from the Lich Spirit Jar table to inspire where a lich hides its soul.

**Lich Spirit Jars**

`dice: [](lich.md#^lich-spirit-jars)`

| dice: 1d8 | The Lich's Spirit Jar Is... |
|-----------|-----------------------------|
| 1 | A bottle or puzzle box inscribed with sigils. |
| 2 | A contract folded into a paper figure. |
| 3 | The first magic item the lich created. |
| 4 | A hollow figurine of a deity or monster. |
| 5 | An hourglass with its sands floating in stasis. |
| 6 | A locket or signet ring with a noble crest. |
| 7 | A rune-etched egg. |
| 8 | The skull of the lich's mentor. |
^lich-spirit-jars

### Lich Lairs

Liches create secluded libraries of magical lore and arcane laboratories hidden within extraplanar bastions, fortresses with cursed reputations, or other such deadly sanctuaries.

> [!quote] A quote from Rudolph van Richten  
> 
> Ambition can become an addiction of the mind and spirit. It builds beyond a driving flame into an insidious inferno that burns a mage hollow until only the desire for more magical power remains


```ad-statblock
title: Lich
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Lich.webp#token)
*Medium undead (wizard), Neutral Evil*

- **Armor Class** 20
- **Hit Points** 315 (`42d8 + 126`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|16 (+3)|21 (+5)|14 (+2)|16 (+3)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +10, Constitution +10, Intelligence +12, Wisdom +9
- **Skills** [Arcana](rules/5e/skills.md#Arcana) +19, [History](rules/5e/skills.md#History) +12, [Insight](rules/5e/skills.md#Insight) +9, [Perception](rules/5e/skills.md#Perception) +9
- **Senses** truesight 120 ft., passive Perception 19
- **Damage Resistances** cold, lightning
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [paralyzed](rules/5e/conditions.md#Paralyzed), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** all
- **Challenge** 21

## Traits

***Legendary Resistance (4/Day, or 5/Day in Lair).*** If the lich fails a saving throw, it can choose to succeed instead.

***Spirit Jar.*** If destroyed, the lich reforms in `dice:1d10|noform|noparens|avg` (`d10`) days if it has a spirit jar, reviving with all its [Hit Points](rules/5e/variant-rules/hit-points-xphb.md). The new body appears in an unoccupied space within the lich's lair.

## Actions

***Multiattack.*** The lich makes three attacks, using Eldritch Burst or Paralyzing Touch in any combination.

***Eldritch Burst.*** *Melee  or Ranged Attack Roll:* `dice:1d20+12|noform|noparens|text(+12)`, reach 5 ft. or range 120 ft. *Hit:* `dice:4d12+5|noform|noparens|avg|text(31)` (`4d12 + 5`) Force damage.

***Paralyzing Touch.*** *Melee Attack Roll:* `dice:1d20+12|noform|noparens|text(+12)`, reach 5 ft. *Hit:* `dice:3d6+5|noform|noparens|avg|text(15)` (`3d6 + 5`) Cold damage, and the target has the [Paralyzed](rules/5e/conditions.md#Paralyzed) condition until the start of the lich's next turn.

***Spellcasting.*** The lich casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 20):

**At will:** [Detect Magic](compendium/5e/spells/detect-magic.md), [Detect Thoughts](compendium/5e/spells/detect-thoughts.md), [Dispel Magic](compendium/5e/spells/dispel-magic.md), [Fireball](compendium/5e/spells/fireball.md) (level 5 version), [Invisibility](compendium/5e/spells/invisibility.md), [Lightning Bolt](compendium/5e/spells/lightning-bolt.md) (level 5 version), [Mage Hand](compendium/5e/spells/mage-hand.md), [Prestidigitation](compendium/5e/spells/prestidigitation.md)

**2/day each:** [Animate Dead](compendium/5e/spells/animate-dead.md), [Dimension Door](compendium/5e/spells/dimension-door.md), [Plane Shift](compendium/5e/spells/plane-shift.md)

**1/day each:** [Chain Lightning](compendium/5e/spells/chain-lightning.md), [Finger of Death](compendium/5e/spells/finger-of-death.md), [Power Word Kill](compendium/5e/spells/power-word-kill.md), [Scrying](compendium/5e/spells/scrying.md)

## Reactions

***Protective Magic.*** The lich casts [Counterspell](compendium/5e/spells/counterspell.md) or [Shield](compendium/5e/spells/shield.md) in response to the spell's trigger, using the same spellcasting ability as Spellcasting.


## Legendary Actions

***Deathly Teleport.*** The lich teleports up to 60 feet to an unoccupied space it can see, and each creature within 10 feet of the space it left takes `dice:2d10|noform|noparens|avg|text(11)` (`2d10`) Necrotic damage.

***Disrupt Life.*** *Constitution Saving Throw:* DC 20, each creature that isn't an Undead in a 20-foot [Emanation](rules/5e/variant-rules/emanation-area-of-effect-xphb.md) originating from the lich. *Failure:* `dice:9d6|noform|noparens|avg|text(31)` (`9d6`) Necrotic damage. *Success:* Half damage. *Failure or Success:* The lich can't take this action again until the start of its next turn.

***Frightening Gaze.*** The lich casts [Fear](compendium/5e/spells/fear.md), using the same spellcasting ability as Spellcasting. The lich can't take this action again until the start of its next turn.


![Lich](compendium/5e/bestiary/legendary-group/lich.md)
```
^statblock

## Environment

any