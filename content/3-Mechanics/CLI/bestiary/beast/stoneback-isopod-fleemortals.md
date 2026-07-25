---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/beast/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Stoneback Isopod
---
# [Stoneback Isopod](3-Mechanics\CLI\bestiary\beast/stoneback-isopod-fleemortals.md)
*Source: Flee, Mortals! p. 329*  

```statblock
"name": "Stoneback Isopod (FleeMortals)"
"size": "Medium"
"type": "beast"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "15"
  - !!int "2"
  - !!int "10"
  - !!int "3"
"speed": "30 ft., climb 20 ft., swim 20 ft."
"damage_resistances": "cold, fire"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The isopod can breathe air and water."
    "name": "Amphibious"
  - "desc": "The isopod has advantage on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth))\
      \ checks to hide in rocky terrain."
    "name": "Stone Camouflage"
"actions":
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13\
      \ (2d8 + 4) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one Medium or smaller\
      \ creature. Hit: 7 (1d6 + 4) bludgeoning damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 14). Until this grapple ends, the isopod can't make a Seize attack\
      \ against another target."
    "name": "Seize"
"reactions":
  - "desc": "When a creature within 5 feet of the isopod hits them with an attack,\
      \ the isopod defensively rolls up inside their rocky carapace. The isopod gains\
      \ a +2 bonus to AC against the triggering attack, and the attacker must succeed\
      \ on a DC 14 Strength saving throw or take 4 (d8) bludgeoning damage and be\
      \ pushed 5 feet into an unoccupied space of the isopod's choice."
    "name": "Curl"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/stoneback-isopod-fleemortals.png"
```
^statblock