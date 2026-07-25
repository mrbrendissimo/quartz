---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/monstrosity/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Stirge Broodling
---
# [Stirge Broodling](3-Mechanics\CLI\bestiary\monstrosity/stirge-broodling-fleemortals.md)
*Source: Flee, Mortals! p. 227*  

```statblock
"name": "Stirge Broodling (FleeMortals)"
"size": "Tiny"
"type": "monstrosity"
"subtype": "Minion"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "2"
"modifier": !!int "1"
"stats":
  - !!int "2"
  - !!int "13"
  - !!int "8"
  - !!int "1"
  - !!int "9"
  - !!int "2"
"speed": "10 ft., fly 30 ft."
"senses": "darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "1/8"
"traits":
  - "desc": "If the broodling takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the broodling takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "If the broodling is reduced to 0 hit points by any damage other than\
      \ psychic while attached to another creature, that creature takes 1 damage of\
      \ the same type."
    "name": "Tiny Target"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +3 to hit, reach 5 ft., one creature.\
      \ Hit: 1 piercing damage, and each broodling who joined the attack can attach\
      \ to the target and enter their space. While attached, a broodling moves with\
      \ the target and can't make Proboscis attacks. The target or a creature who\
      \ can reach them can use an action or bonus action to detach all broodlings,\
      \ shunting them into the nearest unoccupied space of each broodling's choice.\
      \ The broodling also detaches if they become [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
      \ [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
      \ or [restrained](/3-Mechanics/CLI/conditions.md#Restrained)."
    "name": "Proboscis (Group Attack)"
  - "desc": "The broodling sips the life essence of a creature they're attached to\
      \ who isn't a Construct or an Undead. The creature loses 1 hit point."
    "name": "Drain Essence"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/stirge-broodling-fleemortals.png"
```
^statblock