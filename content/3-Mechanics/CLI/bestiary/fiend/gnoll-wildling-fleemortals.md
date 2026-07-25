---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/gnoll
- ttrpg-cli/monster/type/fiend/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gnoll Wildling
---
# [Gnoll Wildling](3-Mechanics\CLI\bestiary\fiend/gnoll-wildling-fleemortals.md)
*Source: Flee, Mortals! p. 121*  

```statblock
"name": "Gnoll Wildling (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "gnoll, Minion"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "8"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "10"
  - !!int "7"
"speed": "30 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Abyssal, Gnoll"
"cr": "1"
"traits":
  - "desc": "When an ally within 5 feet of the wildling is reduced to 0 hit points,\
      \ the wildling can deal 1 piercing damage to a creature within 5 feet of them\
      \ (no action required), provided the wildling isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Death Feast"
  - "desc": "If the wildling takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the wildling takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 1 piercing\
      \ damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by each wildling who joined the attack (escape DC 10 plus the number of wildlings\
      \ who have it [grappled](/3-Mechanics/CLI/conditions.md#Grappled)). Until this\
      \ grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ and the wildling can't make a Flail attack against another creature. A wildling\
      \ can choose to release the [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ creature while other wildlings still have them [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
      \ reducing the escape DC accordingly."
    "name": "Flail (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock