---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/bugbear
- ttrpg-cli/monster/type/humanoid/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bugbear Regular
---
# [Bugbear Regular](3-Mechanics\CLI\bestiary\humanoid/bugbear-regular-fleemortals.md)
*Source: Flee, Mortals! p. 52*  

```statblock
"name": "Bugbear Regular (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "bugbear, Minion"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[leather armor](/3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "8"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "14"
  - !!int "11"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Goblin"
"cr": "1"
"traits":
  - "desc": "When a Medium or smaller enemy is within 5 feet of three or more regulars\
      \ who aren't [prone](/3-Mechanics/CLI/conditions.md#Prone) or [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ that enemy can't see beyond a range of 15 feet."
    "name": "Bodyblock"
  - "desc": "Allied Humanoids within 5 feet of the regular who can see or hear them\
      \ gain a cumulative +1 bonus to Wisdom saving throws."
    "name": "Bugbear's Encouragement"
  - "desc": "If the regular takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the regular takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 1 bludgeoning\
      \ damage."
    "name": "Bullyclub (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock