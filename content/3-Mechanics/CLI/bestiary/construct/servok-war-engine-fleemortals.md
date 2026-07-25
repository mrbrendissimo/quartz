---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/construct/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Servok War Engine
---
# [Servok War Engine](3-Mechanics\CLI\bestiary\construct/servok-war-engine-fleemortals.md)
*Source: Flee, Mortals! p. 280*  

```statblock
"name": "Servok War Engine (FleeMortals)"
"size": "Huge"
"type": "construct"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "270"
"hit_dice": "20d12 + 140"
"modifier": !!int "-2"
"stats":
  - !!int "29"
  - !!int "6"
  - !!int "24"
  - !!int "3"
  - !!int "8"
  - !!int "1"
"speed": "20 ft."
"saves":
  - "strength": !!int "14"
  - "constitution": !!int "12"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+14"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 9"
"languages": "understands Dwarvish but can't speak"
"cr": "16"
"traits":
  - "desc": "The engine is immune to any power, spell, or effect that would alter\
      \ their form."
    "name": "Immutable Form"
  - "desc": "The engine deals double damage to objects and structures."
    "name": "Siege Monster"
  - "desc": "The engine has advantage on saving throws against powers, spells, and\
      \ other supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "The engine makes two attacks using Blade Rake, Force Cannon, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +14 to hit, reach 15 ft., one target. Hit: 35\
      \ (4d12 + 9) slashing damage. If the target is Large or smaller, they are pulled\
      \ up to 15 feet toward the engine."
    "name": "Blade Rake"
  - "desc": "Ranged Spell Attack: +12 to hit, range 400 ft., one target. Hit:\
      \ 33 (6d10) force damage, and the target is [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ until the end of their next turn."
    "name": "Force Cannon"
  - "desc": "The engine shoots burning oil in a 60-foot cone. Each creature in that\
      \ area must make a DC 20 Dexterity saving throw. On a failed save, a creature\
      \ takes 52 (15d6) fire damage and is covered in scalding oil. A creature covered\
      \ in scalding oil takes 10 (3d6) fire damage at the start of each of their turns.\
      \ A creature can use an action to remove the oil from themself or a creature\
      \ they can reach, ending the effect. On a successful save, a creature takes\
      \ half as much damage and is not covered in scalding oil."
    "name": "Burning Oil (Recharge 6)"
"bonus_actions":
  - "desc": "The engine moves up to their speed in a straight line, destroying mundane\
      \ walls in their path that are less than 10 feet thick. Medium or smaller mundane\
      \ objects in the engine's path are destroyed if the objects aren't being worn\
      \ or carried by a creature. The engine can move through the spaces of other\
      \ creatures during this movement as if they were difficult terrain, and if the\
      \ engine does so, the creature must succeed on a DC 20 Dexterity saving throw\
      \ or take 11 (2d10) bludgeoning damage and be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Destructive Rollout"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/construct/token/servok-war-engine-fleemortals.png"
```
^statblock