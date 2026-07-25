---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/construct/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Servok Builder
---
# [Servok Builder](3-Mechanics\CLI\bestiary\construct/servok-builder-fleemortals.md)
*Source: Flee, Mortals! p. 278*  

```statblock
"name": "Servok Builder (FleeMortals)"
"size": "Huge"
"type": "construct"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "216"
"hit_dice": "16d12 + 112"
"modifier": !!int "-2"
"stats":
  - !!int "25"
  - !!int "6"
  - !!int "24"
  - !!int "3"
  - !!int "8"
  - !!int "1"
"speed": "20 ft."
"saves":
  - "strength": !!int "11"
  - "constitution": !!int "11"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+11"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 9"
"languages": "understands Dwarvish but can't speak"
"cr": "12"
"traits":
  - "desc": "The builder is immune to any power, spell, or effect that would alter\
      \ their form."
    "name": "Immutable Form"
  - "desc": "The builder deals double damage to objects and structures."
    "name": "Siege Monster"
  - "desc": "The builder has advantage on saving throws against powers, spells, and\
      \ other supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "The builder makes two attacks using Wrecking Ball, Stone, or both, and\
      \ can use Lay the Foundation, if available."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 15 ft., one target. Hit: 26\
      \ (3d12 + 7) bludgeoning damage.\n\nEach enemy within 5 feet of the target must\
      \ succeed on a DC 19 Dexterity saving throw or take 13 (2d12) bludgeoning damage."
    "name": "Wrecking Ball"
  - "desc": "Melee  or Ranged Weapon Attack: +11 to hit, reach 10 ft. or range 60/240\
      \ ft., one target. Hit: 23 (3d10 + 7) bludgeoning damage. If the target is\
      \ a Medium or smaller creature, they are knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Stone"
  - "desc": "The builder pours wet concrete on the ground in a 20-foot square starting\
      \ from a point within 5 feet of the builder. Until the foundation dries in 1\
      \ hour, that area is difficult terrain, and when a creature with a Strength\
      \ score of 20 or less starts their turn in that area, they must succeed on a\
      \ DC 19 Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics)) check or\
      \ be [restrained](/3-Mechanics/CLI/conditions.md#Restrained) until the start\
      \ of their next turn."
    "name": "Lay the Foundation (Recharge 6)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/construct/token/servok-builder-fleemortals.png"
```
^statblock