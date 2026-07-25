---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/construct/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ashen Hoarder
---
# [Ashen Hoarder](3-Mechanics\CLI\bestiary\construct/ashen-hoarder-fleemortals.md)
*Source: Flee, Mortals! p. 308*  

```statblock
"name": "Ashen Hoarder (FleeMortals)"
"size": "Huge"
"type": "construct"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "184"
"hit_dice": "16d12 + 80"
"modifier": !!int "-1"
"stats":
  - !!int "20"
  - !!int "8"
  - !!int "20"
  - !!int "6"
  - !!int "10"
  - !!int "1"
"speed": "40 ft."
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands the languages of their creator but can't speak"
"cr": "10"
"traits":
  - "desc": "The hoarder carries 6 (1d6 + 3) corpses, which they can use with Corpse\
      \ Bomb and Create Zombies."
    "name": "Corpse Carrier"
"actions":
  - "desc": "The hoarder makes two Arm attacks. If both attacks hit the same creature,\
      \ they can use Impale on the target."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 15\
      \ (3d6 + 5) bludgeoning, piercing, or slashing damage (hoarder's choice)."
    "name": "Arm"
  - "desc": "The hoarder attempts to impale one Larger or smaller creature they can\
      \ see within 10 feet of them on their spikes. The target must succeed on a DC\
      \ 17 Strength saving throw or take 16 (3d10) piercing damage and be [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\
      \ A creature [restrained](/3-Mechanics/CLI/conditions.md#Restrained) in this\
      \ way takes 16 (3d10) necrotic damage at the start of each of their turns, and\
      \ if this damage reduces them to 0 hit points, they die and become an additional\
      \ corpse for the hoarder's Corpse Carrier. A creature can use their action to\
      \ make a DC 17 Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics))\
      \ check, and on a success, they free themself or a creature within reach who\
      \ is [restrained](/3-Mechanics/CLI/conditions.md#Restrained) by the hoarder.\
      \ If the hoarder is destroyed, each creature [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ by them is freed."
    "name": "Impale"
  - "desc": "The hoarder hurls a corpse up to 60 feet, destroying it and releasing\
      \ necrotic energy in a 20-foot-radius sphere centered on the corpse. Each creature\
      \ in this area must make a DC 17 Constitution saving throw. On a failed save,\
      \ a creature takes 33 (6d10) necrotic damage and can't regain hit points until\
      \ the start of the hoarder's next turn. On a successful save, a creature takes\
      \ half as much damage and isn't prevented from regaining hit points."
    "name": "Corpse Bomb"
"bonus_actions":
  - "desc": "The hoarder drops any number of corpses from their Corpse Carrier. Each\
      \ dropped corpse rises as a zombie in an unoccupied space within 10 feet of\
      \ the hoarder and takes their turn immediately after the hoarder's."
    "name": "Create Zombies"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/construct/token/ashen-hoarder-fleemortals.webp"
```
^statblock