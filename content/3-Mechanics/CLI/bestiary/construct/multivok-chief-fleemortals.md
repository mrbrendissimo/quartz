---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Multivok Chief
---
# [Multivok Chief](3-Mechanics\CLI\bestiary\construct/multivok-chief-fleemortals.md)
*Source: Flee, Mortals! p. 277*  

```statblock
"name": "Multivok Chief (FleeMortals)"
"size": "Medium"
"type": "construct"
"subtype": "Support"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "190"
"hit_dice": "20d8 + 100"
"modifier": !!int "0"
"stats":
  - !!int "21"
  - !!int "10"
  - !!int "20"
  - !!int "7"
  - !!int "12"
  - !!int "5"
"speed": "30 ft."
"saves":
  - "strength": !!int "10"
  - "dexterity": !!int "5"
  - "constitution": !!int "10"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+10"
"damage_resistances": "psychic; bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "Dwarvish"
"cr": "14"
"traits":
  - "desc": "The chief is immune to any power, spell, or effect that would alter their\
      \ form."
    "name": "Immutable Form"
  - "desc": "The chief has advantage on saving throws against powers, spells, and\
      \ other supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "The chief makes three attacks using Pneumatic Fist, Targeting Beam, or\
      \ both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 21\
      \ (3d10 + 5) bludgeoning damage. If the target is Medium or smaller, the chief\
      \ can push them up to 10 feet away."
    "name": "Pneumatic Fist"
  - "desc": "Ranged Spell Attack: +10 to hit, range 150 ft., one target. Hit:\
      \ 26 (4d12) force damage, and the target is marked by a beam of red light until\
      \ the end of the chief's next turn. While the target is marked, attack rolls\
      \ against them have advantage."
    "name": "Targeting Beam"
"bonus_actions":
  - "desc": "The chief shouts a command to an ally within 60 feet of them who can\
      \ hear them. The ally can either move up to their speed without provoking opportunity\
      \ attacks or make a melee attack (no action required)."
    "name": "Chief's Command"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/construct/token/multivok-chief-fleemortals.png"
```
^statblock