---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Rot Angel
---
# [Rot Angel](3-Mechanics\CLI\bestiary\celestial/rot-angel-fleemortals.md)
*Source: Flee, Mortals! p. 335*  

```statblock
"name": "Rot Angel (FleeMortals)"
"size": "Medium"
"type": "celestial"
"subtype": "Skirmisher"
"alignment": "typically  Lawful Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "16"
  - !!int "17"
  - !!int "8"
  - !!int "14"
  - !!int "19"
"speed": "0 ft., fly 50 ft. (hover)"
"saves":
  - "constitution": !!int "5"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"damage_resistances": "necrotic, radiant"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), flanked,\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 16"
"languages": "understands Celestial but can't speak it, telepathy 120 ft."
"cr": "4"
"traits":
  - "desc": "The angel doesn't provoke opportunity attacks when they fly out of an\
      \ enemy's reach."
    "name": "Flyby"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 18\
      \ (4d8) necrotic damage, or if the target is a corpse or Undead, the damage\
      \ increases to 36 (8d8).\n\nAdditionally, for the next 24 hours, the target\
      \ is marked for death. A creature who drops to 0 hit points while marked for\
      \ death immediately fails one death saving throw. This effect isn't cumulative."
    "name": "Decaying Touch"
"bonus_actions":
  - "desc": "One of the angel's eyes shoots a magic ray at a creature the angel can\
      \ see within 60 feet of them. The target must succeed on a DC 14 Wisdom saving\
      \ throw or use their reaction, if available, to move as far as their speed allows\
      \ toward the angel, avoiding obviously dangerous ground."
    "name": "Hypnotic Beam"
"reactions":
  - "desc": "When the angel is hit with an attack, they release a cloud of spores.\
      \ Each creature within 10 feet of the angel must succeed on a DC 14 Constitution\
      \ saving throw or be [blinded](/3-Mechanics/CLI/conditions.md#Blinded) until\
      \ the end of the rot angel's next turn."
    "name": "Radiant Puff"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/celestial/token/rot-angel-fleemortals.png"
```
^statblock