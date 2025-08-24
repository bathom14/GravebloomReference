---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- 5e/compendium/src/5e/xmm
- 5e/monster/cr/22
- 5e/monster/environment/elemental-chaos
- 5e/monster/environment/planar
- 5e/monster/size/gargantuan
- 5e/monster/type/elemental/titan
aliases:
- Elemental Cataclysm
---
# Elemental Cataclysm
*Source: Monster Manual (2024) p. 111*  

## Elemental Cataclysm

*The End and Beginning of Ages*

- **Habitat.** Planar (Elemental Chaos)  
- **Treasure.** None  

Beyond the fringes of the Elemental Planes, primordial forces endlessly clash amid the Elemental Chaos. Within the vastness and violence of this realm rage elemental cataclysms, entities spawned from the raw forces of the multiverse and awash in dissonant elemental powers. These beings of primal conflict annihilate nearly all they encounter and seed the ruins left in their wake with the potential for new creations.

Elemental cataclysms rarely escape the Elemental Chaos. When they do, it is typically due to some planar disruption or the summons of nihilistic cultists. When they emerge on Material Plane worlds, elemental cataclysms create realm-altering trails of destruction, carelessly destroying cities and throwing whole nations into chaos. The rampages aren't random. Elemental cataclysms abhor anything that visibly mars nature, be it mines or monuments, fortresses or cities, but they vent their most intense rage on works of metal and clockwork. As they sow destruction, they howl condemnation and chant words of unmaking in the languages of the Inner Planes.

Little can stop an elemental cataclysm. Those that oppose one of these calamities often attempt to reverse the ritual that summoned it, coax it through a planar rift, or conjure another titan in hopes that the two destroy one another. These terrors leave a wake of ashes, floods, storms, and broken earth. But after these disasters recede, the land is imbued with new life or environmental changes. Roll on or choose a result from the Elemental Alterations table to inspire what changes emerge after an elemental cataclysm's destruction.

**Elemental Alterations**

`dice: [](elemental-cataclysm.md#^elemental-alterations)`

| dice: 1d8 | The Elemental Cataclysm Leaves Behind A... |
|-----------|--------------------------------------------|
| 1 | Dramatic increase or decrease in temperature. |
| 2 | Gigantic coral reef or fungal forest. |
| 3 | Never-ending storm or whirlpool. |
| 4 | Passage to the Underdark or portal to an Elemental Plane. |
| 5 | Primeval or previously extinct animal population. |
| 6 | Rapidly growing rainforest. |
| 7 | River where previously there was none. |
| 8 | Series of dramatic rock formations. |
^elemental-alterations

```ad-statblock
title: Elemental Cataclysm
![](https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/XMM/Elemental%20Cataclysm.webp#token)
*Gargantuan elemental (titan), Chaotic Neutral*

- **Armor Class** 20
- **Hit Points** 370 (`20d20 + 160`)
- **Speed** 60 ft., burrow 60 ft., fly 80 ft. (hover), swim 80 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|19 (+4)|27 (+8)| 9 (-1)|14 (+2)| 9 (-1)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +11, Constitution +15, Wisdom +9, Charisma +6
- **Skills** ⏤
- **Senses** truesight 150 ft., passive Perception 12
- **Damage Immunities** acid, cold, fire, lightning, poison, thunder
- **Condition Immunities** [blinded](rules/5e/conditions.md#Blinded), [charmed](rules/5e/conditions.md#Charmed), [deafened](rules/5e/conditions.md#Deafened), [exhaustion](rules/5e/conditions.md#Exhaustion), [frightened](rules/5e/conditions.md#Frightened), [grappled](rules/5e/conditions.md#Grappled), [paralyzed](rules/5e/conditions.md#Paralyzed), [petrified](rules/5e/conditions.md#Petrified), [poisoned](rules/5e/conditions.md#Poisoned), [prone](rules/5e/conditions.md#Prone), [restrained](rules/5e/conditions.md#Restrained), [stunned](rules/5e/conditions.md#Stunned), [unconscious](rules/5e/conditions.md#Unconscious)
- **Languages** Primordial
- **Challenge** 22

## Traits

***Earth Glide.*** The cataclysm can burrow through nonmagical, unworked earth and stone. While doing so, the cataclysm doesn't disturb the material it moves through.

***Legendary Resistance (4/Day).*** If the cataclysm fails a saving throw, it can choose to succeed instead.

***Siege Monster.*** The cataclysm deals double damage to objects and structures.

## Actions

***Multiattack.*** The cataclysm makes two Elemental Burst attacks.

***Elemental Burst.*** *Melee  or Ranged Attack Roll:* `dice:1d20+15|noform|noparens|text(+15)`, reach 30 ft. or range 150 ft. *Hit:* `dice:5d6+8|noform|noparens|avg|text(25)` (`5d6 + 8`) damage of a type chosen by the cataclysm: Acid, Cold, Fire, Lightning, or Thunder.

***Cataclysmic Event (Recharge 4-6).*** The cataclysm creates one of the following effects at random (roll `dice:1d4|noform|noparens|avg` (`d4`)):

- **1 Clinging Flames.** *Dexterity Saving Throw:* DC 23, each creature in a 60-foot-radius [Sphere](rules/5e/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the cataclysm can see within 150 feet. *Failure:* `dice:13d6|noform|noparens|avg|text(45)` (`13d6`) Fire damage. *Success:* Half damage. *Failure or Success:* The target starts [burning](compendium/5e/traps-hazards/burning-xphb.md).  
- **2 Freezing Waves.** *Strength Saving Throw:* DC 23, each creature in a 90-foot [Cone](rules/5e/variant-rules/cone-area-of-effect-xphb.md). *Failure:* `dice:5d8|noform|noparens|avg|text(22)` (`5d8`) Bludgeoning damage plus `dice:5d8|noform|noparens|avg|text(22)` (`5d8`) Cold damage, and the target has the [Prone](rules/5e/conditions.md#Prone) condition. *Success:* Half damage only. *Failure or Success:* The target's [Speed](rules/5e/variant-rules/speed-xphb.md) is reduced to 0 until the end of its next turn.  
- **3 Raging Storm.** A storm cloud fills a 60-foot-radius [Sphere](rules/5e/variant-rules/sphere-area-of-effect-xphb.md) centered on a point the cataclysm can see within 150 feet. The cloud lasts for 1 minute or until the cataclysm uses Cataclysmic Event again. Creatures entirely in the cloud have the [Blinded](rules/5e/conditions.md#Blinded) and [Deafened](rules/5e/conditions.md#Deafened) conditions and can't cast spells with a Verbal component. *Dexterity Saving Throw:* DC 23, each creature that enters the cloud for the first time on a turn or starts its turn there. *Failure:* `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) Lightning damage plus `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) Thunder damage. *Success:* Half damage.  
- **4 Swallowing Earth.** *Strength Saving Throw:* DC 23, each creature in a 90-foot [Cube](rules/5e/variant-rules/cube-area-of-effect-xphb.md) originating from a point on the ground within 150 feet. *Failure:* `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) Bludgeoning damage plus `dice:4d8|noform|noparens|avg|text(18)` (`4d8`) Acid damage, and the target has the [Prone](rules/5e/conditions.md#Prone) condition and is buried under rubble. A buried target has the [Restrained](rules/5e/conditions.md#Restrained) condition, has [Total Cover](rules/5e/variant-rules/cover-xphb.md), and is suffocating. As an action, a buried creature or another creature within 5 feet of it can make a DC 18 Strength ([Athletics](rules/5e/skills.md#Athletics)) check. On a successful check, the creature is no longer buried. *Success:* Half damage only.  

***Control Weather.*** The cataclysm casts the [Control Weather](compendium/5e/spells/control-weather.md) spell, requiring no spell components and using Constitution as the spellcasting ability.


## Legendary Actions

***Eruption.*** The cataclysm makes one Elemental Burst attack.

***Rumbling Movement.*** The cataclysm moves up to its [Speed](rules/5e/variant-rules/speed-xphb.md), [Fly Speed](rules/5e/variant-rules/fly-speed-xphb.md), or [Swim Speed](rules/5e/variant-rules/swim-speed-xphb.md) without provoking [Opportunity Attacks](rules/5e/actions.md#Opportunity%20Attack). Each creature within 5 feet of the cataclysm as it moves is targeted once by the following effect. *Constitution Saving Throw:* DC 23. *Failure:* The target has the [Prone](rules/5e/conditions.md#Prone) condition. *Failure or Success:* The cataclysm can't take this action again until the start of its next turn.
```
^statblock

## Environment

planar, elemental chaos