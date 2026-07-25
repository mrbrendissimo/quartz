---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/minion
- ttrpg-cli/monster/type/humanoid/orc
statblock: inline
statblock-link: "#^statblock"
aliases:
- Orc Blitzer
---
# [Orc Blitzer](3-Mechanics\CLI\bestiary\humanoid/orc-blitzer-fleemortals.md)
*Source: Flee, Mortals! p. 206*  

```statblock
"name": "Orc Blitzer (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Minion"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "7"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "11"
  - !!int "11"
"speed": "35 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Orc"
"cr": "1/2"
"traits":
  - "desc": "If an enemy the blitzer can see starts their turn within 5 feet of three\
      \ or more blitzers, the enemy takes 1 piercing damage for each blitzer within\
      \ 5 feet of them."
    "name": "Gnashing Horde"
  - "desc": "If the blitzer takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the blitzer takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "When the blitzer is reduced to 0 hit points while they aren't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ they can deal 1 piercing damage to an enemy within 5 feet of them."
    "name": "Relentless Minion"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 1 piercing damage."
    "name": "Spear (Group Attack)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/orc-blitzer-fleemortals.png"
```
^statblock