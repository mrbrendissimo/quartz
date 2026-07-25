---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/giant/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Troll Limbjumble
---
# [Troll Limbjumble](3-Mechanics\CLI\bestiary\giant/troll-limbjumble-fleemortals.md)
*Source: Flee, Mortals! p. 243*  

```statblock
"name": "Troll Limbjumble (FleeMortals)"
"size": "Small"
"type": "giant"
"subtype": "Minion"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "9"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "18"
  - !!int "3"
  - !!int "5"
  - !!int "5"
"speed": "25 ft."
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 7"
"languages": "understands Giant but can't speak"
"cr": "2"
"traits":
  - "desc": "If the limbjumble takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the limbjumble takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 2 bludgeoning\
      \ damage. If the target is Medium or smaller and if three or more limbjumbles\
      \ joined the attack, the target is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Arm and a Leg (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock