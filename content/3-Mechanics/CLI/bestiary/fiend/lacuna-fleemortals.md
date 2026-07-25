---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lacuna
---
# [Lacuna](3-Mechanics\CLI\bestiary\fiend/lacuna-fleemortals.md)
*Source: Flee, Mortals! p. 322*  

```statblock
"name": "Lacuna (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "Skirmisher"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "26d8 + 78"
"modifier": !!int "0"
"stats":
  - !!int "5"
  - !!int "10"
  - !!int "17"
  - !!int "18"
  - !!int "16"
  - !!int "24"
"speed": "0 ft."
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "8"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+12"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+12"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "truesight 60 ft., passive Perception 13"
"languages": "Abyssal, Common, Infernal"
"cr": "15"
"traits":
  - "desc": "If the lacuna is subjected to an effect that allows them to make a saving\
      \ throw to take only half damage, they instead take no damage if they succeed\
      \ on the saving throw, and only half damage if they fail."
    "name": "Avoidance"
  - "desc": "While the lacuna remains motionless, they are indistinguishable from\
      \ a normal statue."
    "name": "False Appearance"
  - "desc": "The lacuna doesn't have a walking speed and can't benefit from any bonus\
      \ to their speed."
    "name": "Fiend Between"
  - "desc": "The lacuna has advantage on saving throws against powers, spells, and\
      \ other supernatural effects."
    "name": "Supernatural Resistance"
"actions":
  - "desc": "The lacuna makes three Grief-Eater attacks and uses Infuse Sadness, if\
      \ available."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Spell Attack: +12 to hit, reach 5 ft. or range 20\
      \ ft., one creature. Hit: 29 (4d10 + 7) psychic damage, and the target's speed\
      \ is reduced by 10 feet until the end of their next turn."
    "name": "Grief-Eater"
  - "desc": "Each enemy the lacuna can see within 30 feet of them must succeed on\
      \ a DC 20 Wisdom saving throw or be overwhelmed with grief for 1 minute (save\
      \ ends at end of turn). While a creature is overwhelmed, attacks against them\
      \ are made with advantage."
    "name": "Infuse Sadness (1/Day)"
"bonus_actions":
  - "desc": "The lacuna teleports up to 60 feet to an unoccupied space they can see."
    "name": "Slip Between"
"reactions":
  - "desc": "When a creature within 60 feet of the lacuna targets them with an attack,\
      \ the lacuna teleports up to 60 feet to an unoccupied space they can see. If\
      \ the lacuna is no longer a valid target for the triggering attack, the attacker\
      \ must choose a new target or the attack misses."
    "name": "Slip Away"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/lacuna-fleemortals.webp"
```
^statblock