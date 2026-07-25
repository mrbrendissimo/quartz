---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Basilisk
---
# [Basilisk](3-Mechanics\CLI\bestiary\monstrosity/basilisk-fleemortals.md)
*Source: Flee, Mortals! p. 48*  

```statblock
"name": "Basilisk (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "2"
  - !!int "8"
  - !!int "7"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": ""
"cr": "3"
"traits":
  - "desc": "After the basilisk dies, a creature can make a DC 12 Wisdom ([Medicine](/3-Mechanics/CLI/skills.md#Medicine))\
      \ check using an herbalism kit and the basilisk's gullet, destroying the gullet\
      \ in the process. On a success, the creature creates three doses of a salve.\
      \ One dose of this salve can be applied to a [petrified](/3-Mechanics/CLI/conditions.md#Petrified)\
      \ creature as an action, and 1 minute after the salve is applied, the [petrified](/3-Mechanics/CLI/conditions.md#Petrified)\
      \ condition ends for that creature."
    "name": "Alchemical Ingredients"
  - "desc": "A creature who deals piercing or slashing damage to the basilisk while\
      \ within 5 feet of them takes 2 (d4) poison damage."
    "name": "Toxic Ichor"
"actions":
  - "desc": "The basilisk uses Petrifying Eye Beams and makes one Bite attack or uses\
      \ Poison Fumes, if available."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
      \ + 3) piercing damage plus 5 (2d4) poison damage."
    "name": "Bite"
  - "desc": "The basilisk targets one or two creatures they can see within 30 feet\
      \ of them. Each target must succeed on a DC 12 Constitution saving throw or\
      \ be [restrained](/3-Mechanics/CLI/conditions.md#Restrained) as they magically\
      \ begin to turn to stone. Until the end of the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ creature's next turn, they or an ally within 5 feet of them can use an action\
      \ to cut the encroaching stone from the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ creature's body using a weapon that deals slashing damage. When they do, the\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained) creature takes 13\
      \ (2d12) slashing damage, which can't be reduced in any way, and they are no\
      \ longer [restrained](/3-Mechanics/CLI/conditions.md#Restrained).\n\nA creature\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained) in this way must repeat\
      \ the saving throw at the end of their turn. On a successful save, the effect\
      \ ends. On a failed save, this creature is [petrified](/3-Mechanics/CLI/conditions.md#Petrified)\
      \ until freed by a cure ailment power of 4th order or higher, a [greater restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md)\
      \ spell, or a similar supernatural effect."
    "name": "Petrifying Eye Beams"
  - "desc": "The basilisk exhales poisonous fumes in a 15-foot cone. Each creature\
      \ in this area must make a DC 12 Constitution saving throw, taking 10 (4d4)\
      \ poison damage on a failed save, or half as much damage on a successful one."
    "name": "Poison Fumes (Recharge 4-6)"
"reactions":
  - "desc": "When the basilisk takes piercing or slashing damage, their wound spews\
      \ poison. Each creature within 10 feet of the basilisk must succeed on a DC\
      \ 12 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ for 1 minute (save ends at end of turn)."
    "name": "Poison Splash"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/basilisk-fleemortals.png"
```
^statblock