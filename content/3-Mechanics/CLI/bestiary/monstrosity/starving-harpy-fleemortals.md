---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Starving Harpy
---
# [Starving Harpy](3-Mechanics\CLI\bestiary\monstrosity/starving-harpy-fleemortals.md)
*Source: Flee, Mortals! p. 143*  

```statblock
"name": "Starving Harpy (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "Minion"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "8"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "13"
  - !!int "12"
  - !!int "7"
  - !!int "10"
  - !!int "14"
"speed": "30 ft., fly 30 ft."
"senses": "blindsight 30 ft., passive Perception 10"
"languages": "Common, Giant"
"cr": "1"
"traits":
  - "desc": "If the starving harpy hears a harpy's Alluring Song, they can start harmonizing\
      \ (no action required). The starving harpy continues harmonizing until the song\
      \ ends, until they choose to stop harmonizing, or until they become [deafened](/3-Mechanics/CLI/conditions.md#Deafened)\
      \ or [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated). For each\
      \ starving harpy harmonizing, the range of the song increases by 50 feet, and\
      \ the save DCs for the singing harpy's Alluring Song action and Beckon bonus\
      \ action both increase by 1 (maximum DC increase of 5)."
    "name": "Chorus of Death"
  - "desc": "The harpy can't use their blindsight while [deafened](/3-Mechanics/CLI/conditions.md#Deafened)."
    "name": "Echolocation"
  - "desc": "If the harpy takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the harpy takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 1 piercing\
      \ damage, and if the target is a creature, the harpies can move them 5 feet\
      \ in any direction. If the attack was made by three or more harpies, they can\
      \ move the target 10 feet instead of 5."
    "name": "Grasping Talons (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock