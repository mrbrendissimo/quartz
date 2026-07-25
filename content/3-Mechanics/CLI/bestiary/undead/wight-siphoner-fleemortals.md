---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Wight Siphoner
---
# [Wight Siphoner](3-Mechanics\CLI\bestiary\undead/wight-siphoner-fleemortals.md)
*Source: Flee, Mortals! p. 255*  

```statblock
"name": "Wight Siphoner (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Minion"
"alignment": "typically  Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "10"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "13"
  - !!int "14"
  - !!int "12"
  - !!int "12"
  - !!int "15"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "the languages they knew in life"
"cr": "3"
"traits":
  - "desc": "If the siphoner takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the siphoner takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Spell Attack: +4 to hit, reach 5 ft., one target. Hit: 3 necrotic\
      \ damage. If three or more siphoners joined the attack, they can restore the\
      \ remains of a destroyed Undead minion within 15 feet of the target. That Undead\
      \ minion returns to life with all their hit points. If five or more siphoners\
      \ joined the group attack, they can either choose to increase the range of this\
      \ effect from 15 to 30 feet or to restore two Undead minions instead of one."
    "name": "Grasping Resurrection (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock