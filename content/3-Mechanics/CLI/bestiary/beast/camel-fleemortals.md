---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/beast/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Camel
---
# [Camel](3-Mechanics\CLI\bestiary\beast/camel-fleemortals.md)
*Source: Flee, Mortals! p. 39*  

```statblock
"name": "Camel (FleeMortals)"
"size": "Large"
"type": "beast"
"subtype": "Controller"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "28"
"hit_dice": "3d10 + 12"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "13"
  - !!int "19"
  - !!int "4"
  - !!int "12"
  - !!int "5"
"speed": "50 ft."
"saves":
  - "strength": !!int "5"
  - "constitution": !!int "6"
"senses": "passive Perception 11"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The camel is considered to be one size larger for the purpose of determining\
      \ their carrying capacity."
    "name": "Beast of Burden"
  - "desc": "The camel ignores difficult terrain created by dirt or sand. They can\
      \ tolerate temperatures as high as 120° Fahrenheit."
    "name": "Desert Dweller"
  - "desc": "The camel can go without water for up to 7 days, and without food for\
      \ up to 90 days."
    "name": "Metabolic Reserves"
  - "desc": "The camel has advantage on saving throws made to avoid or end the [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), or [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition on themself."
    "name": "Stubborn"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
      \ + 3) bludgeoning damage, and the target must succeed on a DC 13 Strength saving\
      \ throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Kick"
"bonus_actions":
  - "desc": "The camel vomits bile onto a creature they can see within 10 feet of\
      \ them. The target must succeed on a DC 14 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ for 1 minute (save ends at end of turn). If the target fails the save by 5\
      \ or more, they are also [blinded](/3-Mechanics/CLI/conditions.md#Blinded) while\
      \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) in this way."
    "name": "Bilious Spit (Recharge 5-6)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/camel-companion-fleemortals.png"
```
^statblock