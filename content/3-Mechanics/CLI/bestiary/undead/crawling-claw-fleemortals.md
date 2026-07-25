---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/undead/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Crawling Claw
---
# [Crawling Claw](3-Mechanics\CLI\bestiary\undead/crawling-claw-fleemortals.md)
*Source: Flee, Mortals! p. 251*  

```statblock
"name": "Crawling Claw (FleeMortals)"
"size": "Tiny"
"type": "undead"
"subtype": "Minion"
"alignment": "typically  Neutral Evil"
"ac": !!int "12"
"hp": !!int "2"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "3"
  - !!int "8"
  - !!int "5"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 9"
"languages": "understands the languages they knew in life but can't speak"
"cr": "0"
"traits":
  - "desc": "If the claw takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the claw takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 1 piercing\
      \ damage. If three or more crawling claws joined the attack, the target must\
      \ succeed on a DC 10 Constitution saving throw or contract a disease called\
      \ gravefilth. Whenever a power, a spell, or a similar supernatural effect causes\
      \ a creature with gravefilth to regain hit points, the number of hit points\
      \ they regain is halved. A creature with gravefilth can repeat the saving throw\
      \ whenever they finish a long rest. On a successful save, the disease is cured."
    "name": "Claw (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock