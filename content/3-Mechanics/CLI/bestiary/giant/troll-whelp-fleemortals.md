---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/giant/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Troll Whelp
---
# [Troll Whelp](3-Mechanics\CLI\bestiary\giant/troll-whelp-fleemortals.md)
*Source: Flee, Mortals! p. 243*  

```statblock
"name": "Troll Whelp (FleeMortals)"
"size": "Medium"
"type": "giant"
"subtype": "Minion"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "12"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "20"
  - !!int "7"
  - !!int "9"
  - !!int "7"
"speed": "40 ft."
"saves":
  - "constitution": !!int "8"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Giant"
"cr": "5"
"traits":
  - "desc": "If the whelp takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the whelp takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "When the whelp is reduced to 0 hit points by any damage other than acid\
      \ or fire damage, they don't die or fall [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious),\
      \ and can continue moving and taking actions as usual. The whelp only dies if\
      \ they end their turn with 0 hit points, if acid or fire damage reduces them\
      \ to 0 hit points, or if they take acid or fire damage while they have 0 hit\
      \ points."
    "name": "Relentless Hunger"
  - "desc": "Spaces within reach of one or more whelps are difficult terrain for Medium\
      \ or smaller enemies. When an enemy leaves the reach of one or more whelps who\
      \ can see them, the enemy takes 2 slashing damage."
    "name": "Ripping Claws"
"actions":
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 4 piercing\
      \ damage, and if the target is not a Construct, an Elemental, or a Plant, each\
      \ whelp who joined this attack regains all lost hit points."
    "name": "Bite (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock