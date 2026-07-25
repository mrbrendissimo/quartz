---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Purple Wormling
---
# [Purple Wormling](3-Mechanics\CLI\bestiary\monstrosity/purple-wormling-skt.md)
*Source: Storm King's Thunder p. 242*  

A purple wormling is a baby purple worm no more than six weeks old. Its rubbery body is 9 feet long and weighs 1,500 pounds. Its mouth and musculature aren't yet strong enough to allow the wormling to burrow through rock. The poison in its tail stinger and the acid in its gullet are still relatively weak as well. Nevertheless, the wormling is a voracious feeder and attacks just about anything it can wrap its mouth around. A wormling's gullet can hold up to four Small creatures.

```statblock
"name": "Purple Wormling (SKT)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"modifier": !!int "-2"
"stats":
  - !!int "16"
  - !!int "7"
  - !!int "16"
  - !!int "1"
  - !!int "6"
  - !!int "2"
"speed": "20 ft."
"senses": "blindsight 30 ft., tremorsense 30 ft., passive Perception 8"
"languages": ""
"cr": "2"
"actions":
  - "desc": "The wormling makes two attacks: one with its bite and one with its stinger."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
      \ + 5) piercing damage. If the target is a Small or smaller creature, it must\
      \ succeed on a DC 13 Dexterity saving throw or be swallowed by the worm. A swallowed\
      \ creature is [blinded](/3-Mechanics/CLI/conditions.md#Blinded) and [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ it has total cover against attacks and other effects outside the wormling,\
      \ and it takes 3 (d6) acid damage at the start of each of the wormling's turns.\n\
      \nIf the wormling takes 10 damage or more on a single turn from a creature inside\
      \ it, the wormling must succeed on a DC 21 Constitution saving throw at the\
      \ end of that turn or regurgitate all swallowed creatures, which fall [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ in a space within 10 feet of the wormling. If the wormling dies, a swallowed\
      \ creature is no longer [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ by it and can escape from the corpse by using 5 feet of movement, exiting\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 5\
      \ (1d4 + 3) piercing damage, and the target must make a DC 13 Constitution saving\
      \ throw, taking 10 (3d6) poison damage on a failed save, or half as much damage\
      \ on a successful one."
    "name": "Tail Stinger"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/purple-wormling-skt.webp"
```
^statblock