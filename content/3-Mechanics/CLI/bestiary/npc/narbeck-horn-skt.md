---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Narbeck Horn
---
# [Narbeck Horn](3-Mechanics\CLI\bestiary\npc/narbeck-horn-skt.md)
*Source: Storm King's Thunder p. 114*  

```statblock
"name": "Narbeck Horn (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral"
"ac": !!int "18"
"ac_class": "[plate armor](/3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "14"
  - !!int "11"
  - !!int "11"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "2"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "any one language (usually Common), Dwarvish"
"cr": "3"
"traits":
  - "desc": "Narbeck has advantage on saving throws against being [frightened](/3-Mechanics/CLI/conditions.md#Frightened)."
    "name": "Brave"
  - "desc": "Narbeck"
    "name": "Dwarven Resilience"
"actions":
  - "desc": "Narbeck makes two melee attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 9 (1d12\
      \ + 3) slashing damage."
    "name": "Greataxe"
  - "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
      \ 5 (d10) piercing damage."
    "name": "Heavy Crossbow"
  - "desc": "For 1 minute, Narbeck can utter a special command or warning whenever\
      \ a nonhostile creature that it can see within 30 feet of it makes an attack\
      \ roll or a saving throw. The creature can add a d4 to its roll provided it\
      \ can hear and understand Narbeck. A creature can benefit from only one Leadership\
      \ die at a time. This effect ends if Narbeck is [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Leadership (Recharges after a Short or Long Rest)"
"reactions":
  - "desc": "Narbeck adds 2 to its AC against one melee attack that would hit it.\
      \ To do so, Narbeck must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/narbeck-horn-skt.webp"
```
^statblock