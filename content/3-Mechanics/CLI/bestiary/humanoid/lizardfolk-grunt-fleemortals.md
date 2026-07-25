---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/lizardfolk
- ttrpg-cli/monster/type/humanoid/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lizardfolk Grunt
---
# [Lizardfolk Grunt](3-Mechanics\CLI\bestiary\humanoid/lizardfolk-grunt-fleemortals.md)
*Source: Flee, Mortals! p. 183*  

```statblock
"name": "Lizardfolk Grunt (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "lizardfolk, Minion"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "7"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "30 ft., swim 30 ft."
"senses": "passive Perception 11"
"languages": "Common, Draconic"
"cr": "1/2"
"traits":
  - "desc": "The grunt can breathe air and water."
    "name": "Amphibious"
  - "desc": "If the grunt takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the grunt takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 1 piercing\
      \ damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by each grunt who joined the attack (escape DC 10 plus the number of grunts\
      \ grappling; on a success, the target escapes every grunt grappling them). Until\
      \ this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ and the grunts who joined the attack can't bite another target."
    "name": "Bite (Group Attack)"
  - "desc": "Melee  or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. Hit: 1 piercing damage."
    "name": "Javelin (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock