---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/angulotl
- ttrpg-cli/monster/type/humanoid/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Angulotl Tadpole
---
# [Angulotl Tadpole](3-Mechanics\CLI\bestiary\humanoid/angulotl-tadpole-fleemortals.md)
*Source: Flee, Mortals! p. 31*  

```statblock
"name": "Angulotl Tadpole (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "angulotl, Minion"
"alignment": "Any alignment"
"ac": !!int "11"
"hp": !!int "6"
"modifier": !!int "1"
"stats":
  - !!int "5"
  - !!int "12"
  - !!int "9"
  - !!int "8"
  - !!int "8"
  - !!int "8"
"speed": "30 ft., climb 30 ft., swim 30 ft."
"damage_immunities": "poison"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "When the tadpole is reduced to 0 hit points, their body pops, spraying\
      \ acid around them. Each creature within 5 feet of the tadpole takes 1 acid\
      \ damage."
    "name": "Acid Burst"
  - "desc": "The tadpole can breathe air and water."
    "name": "Amphibious"
  - "desc": "If the tadpole takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the tadpole takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "When a creature starts their turn within 5 feet of three or more tadpoles,\
      \ that creature must succeed on a Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the start of their next turn. The DC for this saving throw equals 10\
      \ plus the number of tadpoles within 5 feet of the creature."
    "name": "Noxious Skin"
"actions":
  - "desc": "Melee Weapon Attack: +3 to hit, one target. Hit: 1 piercing damage."
    "name": "Bite (Group Attack)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/angulotl-tadpole-fleemortals.png"
```
^statblock