---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Girallon Zombie
---
# [Girallon Zombie](3-Mechanics\CLI\bestiary\undead/girallon-zombie-toa.md)
*Source: Tomb of Annihilation p. 240*  

Several new zombie variants are presented below. For more information on zombies, see the Monster Manual.

## Ankylosaurus Zombie

This creature is slow and barely aware of its surroundings.

## Girallon Zombie

Girallons are four-armed apes with white fur. Girallon zombies are slower than their non-undead counterparts but no less fierce. The necromantic energy empowering them fuels their murderous hearts and their hunger for living flesh.

## Tyrannosaurus Zombie

A tyrannosaurus zombie has a gullet full of smaller zombies, which it can disgorge. These zombies aren't under the tyrannosaurus zombie's control.

```statblock
"name": "Girallon Zombie (ToA)"
"size": "Large"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "59"
"hit_dice": "7d10 + 21"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "16"
  - !!int "3"
  - !!int "7"
  - !!int "5"
"speed": "30 ft., climb 30 ft."
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": ""
"cr": "3"
"traits":
  - "desc": "As a bonus action, the zombie can move up to its speed toward a hostile\
      \ creature that it can see."
    "name": "Aggressive"
  - "desc": "If damage reduces the zombie to 0 hit points, it must make a Constitution\
      \ saving throw with a DC of 5+the damage taken, unless the damage is radiant\
      \ or from a critical hit. On a success, the zombie drops to 1 hit point instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "The zombie makes five attacks: one with its bite and four with its claws."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
      \ + 4) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d4\
      \ + 4) slashing damage."
    "name": "Claw"
"source":
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/undead/token/girallon-zombie-toa.webp"
```
^statblock