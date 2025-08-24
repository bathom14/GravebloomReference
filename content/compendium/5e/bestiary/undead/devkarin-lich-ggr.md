---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/ggr
- 5e/monster/cr/14
- 5e/monster/size/medium
- 5e/monster/type/undead
aliases:
- Devkarin Lich
---
# Devkarin Lich
*Source: Guildmasters' Guide to Ravnica p. 198*  

Powerful spellcasters of the Devkarin elves, steeped in Golgari magic, can transcend death to become liches. For them, life and death don't merely chase each other in an inevitable cycle; the two can intersect, and at that nexus the liches find immense power, which commands the awe, envy, and fear of other Golgari.

Unlike the shambling zombies they command, liches retain their memories, their personalities, and especially their ambition. They also retain the grace and stature of living elves, but their bodies are in a constant state of slow decay. Various forms of fungus grow in and over the rotting flesh to hold the body together.

## Undead Nature

The lich doesn't require air, food, drink, or sleep.

## Statblock

```ad-statblock
title: Devkarin Lich
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Devkarin%20Lich.webp#token)
*Medium undead, Neutral Evil*

- **Armor Class** 14 (natural armor)
- **Hit Points** 97 (`15d8 + 30`)
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|16 (+3)|14 (+2)|19 (+4)|16 (+3)|15 (+2)|

- **Proficiency Bonus** +5
- **Saving Throws** Constitution +7, Intelligence +9, Wisdom +8
- **Skills** [Arcana](rules/5e/skills.md#Arcana) +14, [Insight](rules/5e/skills.md#Insight) +8, [Perception](rules/5e/skills.md#Perception) +8
- **Senses** truesight 120 ft., passive Perception 18
- **Damage Resistances** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [paralyzed](rules/5e/conditions.md#Paralyzed), [poisoned](rules/5e/conditions.md#Poisoned)
- **Languages** Common, Elvish, Kraul
- **Challenge** 14

## Traits

***Spellcasting.*** The lich is a 14th-level Golgari spellcaster. Its spellcasting ability is Intelligence (spell save DC 17, `dice:1d20+9|noform|noparens|text(+9)` to hit with spell attacks). The lich has the following wizard spells prepared:

**Cantrips (at will):** [acid splash](compendium/5e/spells/acid-splash.md), [chill touch](compendium/5e/spells/chill-touch.md), [mage hand](compendium/5e/spells/mage-hand.md), [poison spray](compendium/5e/spells/poison-spray.md), [prestidigitation](compendium/5e/spells/prestidigitation.md)

**1st level (4 slots):** [chromatic orb](compendium/5e/spells/chromatic-orb.md), [magic missile](compendium/5e/spells/magic-missile.md), [ray of sickness](compendium/5e/spells/ray-of-sickness.md)

**2nd level (3 slots):** [Melf's acid arrow](compendium/5e/spells/melfs-acid-arrow.md), [ray of enfeeblement](compendium/5e/spells/ray-of-enfeeblement.md), [spider climb](compendium/5e/spells/spider-climb.md), [web](compendium/5e/spells/web.md)

**3rd level (3 slots):** [animate dead](compendium/5e/spells/animate-dead.md), [bestow curse](compendium/5e/spells/bestow-curse.md), [fear](compendium/5e/spells/fear.md), [vampiric touch](compendium/5e/spells/vampiric-touch.md)

**4th level (3 slots):** [blight](compendium/5e/spells/blight.md), [Evard's black tentacles](compendium/5e/spells/evards-black-tentacles.md)

**5th level (2 slots):** [cloudkill](compendium/5e/spells/cloudkill.md), [insect plague](compendium/5e/spells/insect-plague.md)

**6th level (1 slots):** [circle of death](compendium/5e/spells/circle-of-death.md), [create undead](compendium/5e/spells/create-undead.md)

**7th level (1 slots):** [finger of death](compendium/5e/spells/finger-of-death.md)

***Legendary Resistance (3/Day).*** If the lich fails a saving throw, it can choose to succeed instead.

***Regeneration.*** The lich regains 10 hit points at the start of its turn. If the lich takes fire or radiant damage, this trait doesn't function at the start of the lich's next turn. The lich dies only if it starts its turn with 0 hit points and doesn't regenerate.

***Turn Resistance.*** The lich has advantage on saving throws against any effect that turns undead.

***Undead Fortitude.*** If damage reduces the lich to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the lich drops to 1 hit point instead.

## Actions

***Noxious Touch.*** *Melee Spell Attack:* `dice:1d20+9|noform|noparens|text(+9)` to hit, reach 5 ft., one creature. *Hit:* `dice:4d6|noform|noparens|avg|text(14)` (`4d6`) poison damage, and the target must succeed on a DC 17 Constitution saving throw or be [poisoned](rules/5e/conditions.md#Poisoned) for 1 minute. The [poisoned](rules/5e/conditions.md#Poisoned) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

## Legendary Actions

***Cantrip.*** The lich casts one of its cantrips.

***Noxious Touch (Costs 2 Actions).*** The lich uses Noxious Touch.

***Disrupt Life (Costs 3 Actions).*** Each creature within 30 feet of the lich must make a DC 17 Constitution saving throw, taking `dice:6d6|noform|noparens|avg|text(21)` (`6d6`) necrotic damage on a failed save, or half as much damage on a successful one.
```
^statblock