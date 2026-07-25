---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Griffon Companion
---
# [Griffon Companion](3-Mechanics\CLI\bestiary\beast/griffon-companion-fleemortals.md)
*Source: Flee, Mortals! p. 135*  

```statblock
"name": "Griffon Companion (FleeMortals)"
"size": "Large"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "6"
  - !!int "12"
  - !!int "8"
"speed": "30 ft. (see learning to fly)"
"saves":
  - "name": "Constitution"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+1 plus PB"
"senses": "passive Perception 0"
"languages": ""
"traits":
  - "desc": "The griffon has a flying speed of 10 × PB feet."
    "name": "Learning to Fly"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage."
    "name": "Signature Attack (Beak)"
  - "desc": "The griffon makes a signature attack. On a hit, the attack deals an extra\
      \ PB slashing damage, and the griffon can move the target 5 feet in any direction."
    "name": "1st Level: Violent Attack (2 Ferocity)"
  - "desc": "The griffon makes a signature attack against a Medium or smaller creature.\
      \ On a hit, the target is also [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 10 plus PB) if they weren't already. While [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ in this way, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ and the griffon can't make a signature attack against another target."
    "name": "3rd Level: Grabbed from Above (5 Ferocity)"
  - "desc": "The griffon flies up to their speed without provoking opportunity attacks.\
      \ If the griffon has a creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
      \ the grapple doesn't halve the griffon's speed and the griffon can end the\
      \ grapple at any point during this movement. If the griffon ends the grapple\
      \ before the end of their turn and the target takes bludgeoning damage from\
      \ that fall, the target takes an extra PB bludgeoning damage."
    "name": "3rd Level: Bombs Away (5 Ferocity)"
  - "desc": "The griffon flies up to their speed without provoking opportunity attacks.\
      \ When the griffon ends this movement, each creature within 15 feet of them\
      \ must make a DC 10 plus PB Strength saving throw. On a failed save, a creature\
      \ takes PBd6 bludgeoning damage and is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ On a successful save, a creature takes half as much damage and isn't knocked\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "5th Level: Backdraft (8 Ferocity)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/griffon-fleemortals.png"
```
^statblock