---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental/fire
- ttrpg-cli/monster/type/elemental/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Fire Spark
---
# [Fire Spark](3-Mechanics\CLI\bestiary\elemental/fire-spark-fleemortals.md)
*Source: Flee, Mortals! p. 93*  

```statblock
"name": "Fire Spark (FleeMortals)"
"size": "Medium"
"type": "elemental"
"subtype": "fire, Minion"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "12"
"modifier": !!int "1"
"stats":
  - !!int "9"
  - !!int "12"
  - !!int "11"
  - !!int "12"
  - !!int "10"
  - !!int "16"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+6"
"damage_immunities": "fire"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Ignan"
"cr": "5"
"traits":
  - "desc": "The spark sheds bright light in a 15-foot radius and dim light for an\
      \ additional 15 feet. If an enemy starts their turn within 5 feet of three or\
      \ more fire sparks, they take 6 fire damage."
    "name": "Little Flames"
  - "desc": "If the spark takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the spark takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Spell Attack: +6 to hit, reach 5 ft., one target. Hit: 4 fire\
      \ damage."
    "name": "Ember Claw (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock