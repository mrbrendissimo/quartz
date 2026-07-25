---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/dragon/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Shieldscale Drangolin
---
# [Shieldscale Drangolin](3-Mechanics\CLI\bestiary\dragon/shieldscale-drangolin-fleemortals.md)
*Source: Flee, Mortals! p. 178*  

```statblock
"name": "Shieldscale Drangolin (FleeMortals)"
"size": "Large"
"type": "dragon"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "14"
  - !!int "16"
  - !!int "4"
  - !!int "10"
  - !!int "6"
"speed": "30 ft., burrow 30 ft."
"saves":
  - "strength": !!int "5"
  - "constitution": !!int "5"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+2"
"damage_resistances": "fire"
"senses": "tremorsense 60 ft., passive Perception 12"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The drangolin can burrow through solid rock at half their burrow speed\
      \ and leaves behind a 3-foot-diameter tunnel when they burrow. Tiny and Small\
      \ creatures can move through it normally, and Medium and Large creatures can\
      \ squeeze through it. This tunnel collapses after 10 minutes."
    "name": "Tunneler"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one target. Hit: 10\
      \ (2d6 + 3) slashing damage plus 3 (d6) fire damage."
    "name": "Fiery Claws"
  - "desc": "If the drangolin is burrowing within 10 feet of the surface, they can\
      \ erupt from the ground (without spending movement) into a space that contains\
      \ one or more creatures. When they do, each creature within 10 feet of the drangolin\
      \ must make a DC 13 Dexterity saving throw. A creature directly above the drangolin\
      \ when they emerge has disadvantage on this saving throw. On a failed save,\
      \ a creature takes 14 (4d6) bludgeoning damage and is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ On a successful save, a creature takes only half as much damage and is pushed\
      \ 5 feet to an unoccupied space of their choice instead of being knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Erupt (1/Day)"
  - "desc": "The drangolin moves up to twice their walking speed in a straight line\
      \ without provoking opportunity attacks. While doing so, they can enter Large\
      \ or smaller creatures' spaces. If the drangolin enters another creature's space\
      \ during this move, that creature must succeed on a DC 13 Dexterity saving throw\
      \ or take 7 (2d6) bludgeoning damage plus 7 (2d6) fire damage. If the drangolin\
      \ enters the space of a structure or object that isn't being worn or carried,\
      \ it takes twice as much damage."
    "name": "Wrecking Ball (1/Day)"
"reactions":
  - "desc": "When a creature the drangolin can sense moves within 5 feet of them,\
      \ the drangolin sprays them with a cloud of ash. The target must succeed on\
      \ a DC 13 Dexterity saving throw or be [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ until the start of their next turn."
    "name": "Ash Shot"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/dragon/token/drangolin-companion-fleemortals.png"
```
^statblock