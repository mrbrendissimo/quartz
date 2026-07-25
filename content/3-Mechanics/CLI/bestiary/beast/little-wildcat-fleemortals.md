---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/unknown
- ttrpg-cli/monster/type/beast/ambusher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Little Wildcat
---
# [Little Wildcat](3-Mechanics\CLI\bestiary\beast/little-wildcat-fleemortals.md)
*Source: Flee, Mortals! p. 43*  

```statblock
"name": "Little Wildcat (FleeMortals)"
"size": "Unknown"
"type": "beast"
"subtype": "Ambusher"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "18"
"hit_dice": "4d6 + 4"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "15"
  - !!int "12"
  - !!int "6"
  - !!int "14"
  - !!int "8"
"speed": "40 ft., climb 30 ft."
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The wildcat takes no damage from falling 40 feet or less, provided they\
      \ aren't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Agile Landing"
  - "desc": "If the wildcat hits a Small or smaller target and had advantage on the\
      \ attack roll, the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 12). While grappling the target in this way, the wildcat can't\
      \ attack another creature."
    "name": "Hunter's Pounce"
  - "desc": "The wildcat has advantage on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth))\
      \ checks made in their native terrain."
    "name": "Natural Camouflage"
  - "desc": "When the wildcat moves on their turn in combat, they can triple their\
      \ speed until the end of their turn."
    "name": "Sprint (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
      \ + 2) piercing damage, plus an extra 2 (d4) piercing damage if the target is\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) or [restrained](/3-Mechanics/CLI/conditions.md#Restrained)."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
      \ + 2) slashing damage, plus an extra 2 (d4) slashing damage if the wildcat\
      \ had advantage on the attack roll."
    "name": "Claw"
"bonus_actions":
  - "desc": "The wildcat takes the Hide action."
    "name": "Sneak"
"source":
  - "FleeMortals"
```
^statblock