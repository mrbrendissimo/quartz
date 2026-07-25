---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hill Giant Flunky
---
# [Hill Giant Flunky](3-Mechanics\CLI\bestiary\giant/hill-giant-flunky-fleemortals.md)
*Source: Flee, Mortals! p. 110*  

```statblock
"name": "Hill Giant Flunky (FleeMortals)"
"size": "Huge"
"type": "giant"
"subtype": "Minion"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "12"
"modifier": !!int "-1"
"stats":
  - !!int "21"
  - !!int "8"
  - !!int "18"
  - !!int "8"
  - !!int "9"
  - !!int "7"
"speed": "30 ft., climb 20 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
"senses": "passive Perception 12"
"languages": "Giant"
"cr": "5"
"traits":
  - "desc": "When the flunky targets a creature with an attack, another creature within\
      \ range of the attack can use their reaction to distract each flunky joining\
      \ in the attack. Each flunky who can see or hear the distracting creature joins\
      \ a group attack targeting that creature instead. If one or more flunkies can't\
      \ see or hear the distracting creature, those flunkies join a separate group\
      \ attack on the original target instead."
    "name": "Distracted"
  - "desc": "If the flunky takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the flunky takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "A Large or smaller creature who ends their turn within 10 feet of two\
      \ or more flunkies must succeed on a DC 16 Strength saving throw or fall [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "The Hills Are Alive"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +8 to hit, reach 10 ft. or range 60/240\
      \ ft., one target. Hit: 4 bludgeoning damage, or 5 bludgeoning damage if the\
      \ target is [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Rock (Group Attack)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/giant/token/hill-giant-flunky-fleemortals.png"
```
^statblock