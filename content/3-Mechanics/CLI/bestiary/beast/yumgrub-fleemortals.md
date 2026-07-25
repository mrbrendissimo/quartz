---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/beast/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Yumgrub
---
# [Yumgrub](3-Mechanics\CLI\bestiary\beast/yumgrub-fleemortals.md)
*Source: Flee, Mortals! p. 297*  

```statblock
"name": "Yumgrub (FleeMortals)"
"size": "Tiny"
"type": "beast"
"subtype": "Minion"
"alignment": "Unaligned"
"ac": !!int "9"
"hp": !!int "2"
"modifier": !!int "-1"
"stats":
  - !!int "6"
  - !!int "9"
  - !!int "5"
  - !!int "4"
  - !!int "7"
  - !!int "1"
"speed": "10 ft., climb 10 ft."
"senses": "darkvision 30 ft., passive Perception 8"
"languages": ""
"cr": "0"
"traits":
  - "desc": "When the yumgrub dies, they let out a distressing screech. Each creature\
      \ within 15 feet who can hear the yumgrub takes 1 psychic damage. Yumgrubs and\
      \ creatures who have eaten a yumgrub within the last minute are immune to this\
      \ damage."
    "name": "Death Wail"
  - "desc": "If the yumgrub takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the yumgrub takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "The yumgrub can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "A Small or larger creature can use an action to consume a living yumgrub\
      \ within 5 feet of them. The yumgrub dies, and for 1 minute, the consuming creature's\
      \ speed is doubled and they gain a +4 bonus to their Strength score and a +2\
      \ bonus to AC. When the effect ends, the creature gains two levels of [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)."
    "name": "Yum"
"actions":
  - "desc": "Melee Weapon Attack: -1 to hit, reach 5 ft., one target. Hit: 1 piercing\
      \ damage."
    "name": "Bite (Group Attack)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/yumgrub-fleemortals.png"
```
^statblock