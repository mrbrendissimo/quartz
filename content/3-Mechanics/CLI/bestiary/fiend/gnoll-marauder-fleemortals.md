---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/gnoll
- ttrpg-cli/monster/type/fiend/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gnoll Marauder
---
# [Gnoll Marauder](3-Mechanics\CLI\bestiary\fiend/gnoll-marauder-fleemortals.md)
*Source: Flee, Mortals! p. 120*  

```statblock
"name": "Gnoll Marauder (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "gnoll, Skirmisher"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "13"
  - !!int "12"
  - !!int "10"
  - !!int "12"
  - !!int "8"
"speed": "40 ft."
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Abyssal, Gnoll"
"cr": "1/2"
"traits":
  - "desc": "If the marauder moves at least 10 feet straight toward a creature and\
      \ hits them with a Flail attack on the same turn, the marauder can make a Bite\
      \ attack against that target as a bonus action."
    "name": "Rampaging Charge"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
      \ + 2) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
      \ + 2) bludgeoning damage."
    "name": "Flail"
"reactions":
  - "desc": "When an ally the marauder can see within 30 feet of them is reduced to\
      \ 0 hit points, the marauder moves up to half their speed and makes a Bite attack."
    "name": "Death Frenzy"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/gnoll-marauder-fleemortals.png"
```
^statblock