---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/mpp
- 5e/monster/cr/16
- 5e/monster/size/large
- 5e/monster/type/fiend
aliases:
- Shator Demodand
---
# Shator Demodand
*Source: Morte's Planar Parade p. 28, Sigil and the Outlands*  

Shators, known as shaggy demodands, dominate demodand society, ruthlessly commanding their lesser kin. They are hulking creatures covered in fungal growths. Shators are the self-appointed wardens of Carceri, and they keep meticulous records of their subordinates and the prisoners they claim. On the rare occasions that shators find themselves on the Material Plane, they manipulate mortal leaders and philosophers, using them as mouthpieces to spread poisoned words and tempt souls toward Carceri's waiting chains.

## Demodands

Demodands, also called gehreleths, are Fiends from the Tarterian Depths of Carceri. Cast into the prison plane long ago for forgotten transgressions, these bitter, wicked creatures have appointed themselves the jailers of the plane. Demodands viciously defend the few known portals that lead out of Carceri and ruthlessly torment other creatures trapped there.

Demodands that manage to leave Carceri know they're doomed to return; a demodand that dies outside Carceri re-forms there in a torturous process that takes `dice:2d20|noform|noparens|avg` (`2d20`) days. Even those who survive on other planes find themselves eventually dragged back, pulled by some planar tether.

## Statblock

```ad-statblock
title: Shator Demodand
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/MPP/Shator%20Demodand.webp#token)
*Large fiend, typically  Neutral Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 195 (`23d10 + 69`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|15 (+2)|17 (+3)|21 (+5)|16 (+3)|20 (+5)|

- **Proficiency Bonus** +5
- **Saving Throws** Dexterity +7, Wisdom +8
- **Skills** [Perception](rules/5e/skills.md#Perception) +13, [Stealth](rules/5e/skills.md#Stealth) +7
- **Senses** truesight 120 ft., passive Perception 23
- **Damage Resistances** cold, fire
- **Damage Immunities** acid, poison
- **Condition Immunities** [charmed](rules/5e/conditions.md#Charmed), [frightened](rules/5e/conditions.md#Frightened), [paralyzed](rules/5e/conditions.md#Paralyzed), [poisoned](rules/5e/conditions.md#Poisoned), [restrained](rules/5e/conditions.md#Restrained)
- **Languages** Abyssal, Common, Demodand, Infernal, telepathy 120 ft.
- **Challenge** 16

## Traits

***Boundless Movement.*** The shator ignores difficult terrain, and magical effects can't reduce its speed. It can spend 5 feet of movement to automatically remove the [grappled](rules/5e/conditions.md#Grappled) condition from itself.

***Jailer (1/Day).*** The shator can cast the [imprisonment](compendium/5e/spells/imprisonment.md) spell, requiring no material components and using Intelligence as the spellcasting ability (chaining effect only; spell save DC 18).

***Liquefaction Ritual.*** The shator can perform a 1-minute ritual that turns all willing farastus and kelubars of its choice within 60 feet of itself into a living liquid form. Each liquefied demodand becomes enough liquid to fill a flask. A demodand's liquefaction lasts until a shator uses an action to end it or a creature opens a container holding the liquid. While liquefied in this way, a demodand has the [paralyzed](rules/5e/conditions.md#Paralyzed) condition despite any immunity to that condition, it has immunity to all damage, and any curse affecting it is suspended.

***Magic Resistance.*** The shator has advantage on saving throws against spells and other magical effects.

***Numbing Secretions.*** A creature that touches the shator or hits it with a melee attack while within 5 feet of it must succeed on a DC 17 Dexterity saving throw or have disadvantage on attack rolls and its speed halved until the end of its next turn.

## Actions

***Multiattack.*** The shator makes one Bite attack and two Enervating Trident attacks.

***Bite.*** *Melee Weapon Attack:* `dice:1d20+12|noform|noparens|text(+12)` to hit, reach 5 ft., one target. *Hit:* `dice:3d6+7|noform|noparens|avg|text(17)` (`3d6 + 7`) piercing damage plus `dice:4d12|noform|noparens|avg|text(26)` (`4d12`) acid damage. If the target is a creature, it must succeed on a DC 16 Constitution saving throw or have the [paralyzed](rules/5e/conditions.md#Paralyzed) condition until the start of the shator's next turn.

***Enervating Trident.*** *Melee Weapon Attack:* `dice:1d20+12|noform|noparens|text(+12)` to hit, reach 10 ft., one target. *Hit:* `dice:2d10+7|noform|noparens|avg|text(18)` (`2d10 + 7`) necrotic damage.

***Inhibitory Spray (Recharge 5-6).*** The shator exhales a spray of slime in a line 100 feet long and 5 feet wide. Each creature in that area must make a DC 16 Dexterity saving throw. On a failed save, a creature takes `dice:9d8|noform|noparens|avg|text(40)` (`9d8`) acid damage and has the [paralyzed](rules/5e/conditions.md#Paralyzed) condition for 1 minute. The creature repeats the saving throw at the end of each of its turns, ending the effect on itself on a success. On a successful save, a creature takes half as much damage only.

***Summon Demodand (1/Day).*** The shator has a 50 percent chance of summoning its choice of `dice:1d4|noform|noparens|avg` (`d4`) farastu demodands, `dice:1d2|noform|noparens|avg` (`d2`) kelubar demodands, or 1 shator demodand. A summoned demodand appears in an unoccupied space within 60 feet of the shator, acts as an ally of the shator, and can't summon other demodands. It remains for 1 minute, until it or the shator dies, or until the shator dismisses it as an action.

***Spellcasting.*** The shator casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 18, `dice:1d20+10|noform|noparens|text(+10)` to hit with spell attacks):

**At will:** [invisibility](compendium/5e/spells/invisibility.md) (self only), [suggestion](compendium/5e/spells/suggestion.md)

**1/day each:** [dispel magic](compendium/5e/spells/dispel-magic.md), [plane shift](compendium/5e/spells/plane-shift.md) (to Carceri only), [scrying](compendium/5e/spells/scrying.md) (as an action)
```
^statblock