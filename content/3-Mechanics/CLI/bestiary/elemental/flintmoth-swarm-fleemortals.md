---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/unknown
- ttrpg-cli/monster/type/elemental/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Flintmoth Swarm
---
# [Flintmoth Swarm](3-Mechanics\CLI\bestiary\elemental/flintmoth-swarm-fleemortals.md)
*Source: Flee, Mortals! p. 321*  

```statblock
"name": "Flintmoth Swarm (FleeMortals)"
"size": "Unknown"
"type": "elemental"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d12 + 32"
"modifier": !!int "5"
"stats":
  - !!int "13"
  - !!int "20"
  - !!int "15"
  - !!int "1"
  - !!int "8"
  - !!int "1"
"speed": "20 ft., climb 20 ft., fly 40 ft."
"saves":
  - "dexterity": !!int "9"
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+9"
"damage_resistances": "bludgeoning, piercing, slashing"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ flanked, [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "blindsight 15 ft., darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "11"
"traits":
  - "desc": "Other creatures in the swarm's space are [blinded](/3-Mechanics/CLI/conditions.md#Blinded)."
    "name": "Obscuring Form"
  - "desc": "When the swarm is reduced to half their hit points, their size becomes\
      \ Large."
    "name": "Shrink"
  - "desc": "The swarm has advantage on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth))\
      \ checks made to hide in rocky terrain."
    "name": "Stone Camouflage"
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny insect. The swarm\
      \ can't regain hit points or gain temporary hit points."
    "name": "Swarm"
"actions":
  - "desc": "The swarm makes three Flutter Cutter attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 0 ft., one target in the swarm's\
      \ space. Hit: 26 (6d6 + 5) slashing damage, or 33 (8d6 + 5) slashing damage\
      \ if the target is a Construct made of stone or is holding or wearing an object\
      \ that emits bright light."
    "name": "Flutter Cutter"
"bonus_actions":
  - "desc": "The swarm feeds on a mundane object or structure within 5 feet of them\
      \ that is made mostly of stone.\n\nIf the swarm targets a Medium or smaller\
      \ object, it is entirely devoured. If the swarm targets a structure or a Large\
      \ or larger object, the swarm devours a 5-foot-cube portion of it."
    "name": "Devour Stone"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/flintmoth-swarm-fleemortals.png"
```
^statblock