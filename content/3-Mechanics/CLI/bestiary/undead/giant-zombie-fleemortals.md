---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Giant Zombie
---
# [Giant Zombie](3-Mechanics\CLI\bestiary\undead/giant-zombie-fleemortals.md)
*Source: Flee, Mortals! p. 253*  

```statblock
"name": "Giant Zombie (FleeMortals)"
"size": "Huge"
"type": "undead"
"subtype": "Brute"
"alignment": "typically  Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "84"
"hit_dice": "8d12 + 32"
"modifier": !!int "-1"
"stats":
  - !!int "19"
  - !!int "8"
  - !!int "18"
  - !!int "3"
  - !!int "5"
  - !!int "4"
"speed": "30 ft."
"damage_vulnerabilities": "radiant"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 7"
"languages": "understands the languages they knew in life but can't speak"
"cr": "4"
"traits":
  - "desc": "Whenever a creature deals 7 damage or less to the zombie, the zombie\
      \ takes no damage instead."
    "name": "Negative Nerves"
"actions":
  - "desc": "The zombie makes two Fist attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 10 ft., one target. Hit: 11\
      \ (2d6 + 4) bludgeoning damage, and if the target is Large or smaller, they\
      \ are [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 14). The\
      \ zombie has two fists, each of which can grapple one target."
    "name": "Fist"
  - "desc": "The zombie spews toxic vomit in a 15-foot cone. Each creature in that\
      \ area must make a DC 14 Constitution saving throw, taking 14 (4d6) poison damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Toxic Exhalation (Recharge 5-6)"
"reactions":
  - "desc": "When a Huge or smaller creature within 10 feet of the zombie hits them\
      \ with a melee attack, the zombie pushes the creature up to 10 feet away."
    "name": "Shove Away"
"source":
  - "FleeMortals"
```
^statblock