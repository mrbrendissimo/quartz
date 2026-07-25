---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/brute
- ttrpg-cli/monster/type/fiend/gnoll
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gnoll Bonesplitter
---
# [Gnoll Bonesplitter](3-Mechanics\CLI\bestiary\fiend/gnoll-bonesplitter-fleemortals.md)
*Source: Flee, Mortals! p. 118*  

```statblock
"name": "Gnoll Bonesplitter (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "gnoll, Brute"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "17"
  - !!int "10"
  - !!int "12"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Abyssal, Gnoll"
"cr": "4"
"actions":
  - "desc": "The bonesplitter makes two attacks using Bite, Spiked Flail, or both.\
      \ They can replace one attack with a use of Bloody Roar, if available."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. Hit: 7\
      \ (1d6 + 4) piercing damage, or 11 (2d6 + 4) piercing damage if the target is\
      \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13\
      \ (2d8 + 4) piercing damage. If the target is a Medium or smaller creature,\
      \ they are [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 14).\
      \ Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ and the bonesplitter can't make Spiked Flail attacks."
    "name": "Spiked Flail"
  - "desc": "The bonesplitter roars, spitting a spray of blood. Each ally within 10\
      \ feet of them who can see them can make a weapon attack (no action required),\
      \ provided that ally isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Bloody Roar (Recharge 6)"
"bonus_actions":
  - "desc": "The bonesplitter yanks a creature they are grappling. The target must\
      \ succeed on a DC 14 Strength saving throw or swap spaces with the bonesplitter."
    "name": "Over Here!"
"reactions":
  - "desc": "When an ally the bonesplitter can see within 30 feet of them is reduced\
      \ to 0 hit points, the bonesplitter moves up to half their speed and makes a\
      \ Bite attack."
    "name": "Death Frenzy"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/gnoll-bonesplitter-whereevillives.png"
```
^statblock