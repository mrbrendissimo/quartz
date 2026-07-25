---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Human Raider
---
# [Human Raider](3-Mechanics\CLI\bestiary\humanoid/human-raider-fleemortals.md)
*Source: Flee, Mortals! p. 163*  

```statblock
"name": "Human Raider (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Skirmisher"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[padded](/3-Mechanics/CLI/items/padded-armor-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md);\
  \ 12 without shield"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3"
"senses": "passive Perception 11"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "If the raider moves at least 15 feet straight toward a target and then\
      \ hits the target with a melee attack on the same turn, the target takes an\
      \ extra 3 (d6) damage."
    "name": "Charge"
  - "desc": "When the raider makes an attack, they have advantage on the attack roll."
    "name": "Exploit Opening (3/Day)"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 5 (1d6 + 2) slashing damage."
    "name": "Handaxe"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
      \ + 2) bludgeoning damage, and if the target is a Medium or smaller creature,\
      \ they must succeed on a DC 12 Strength saving throw or be pushed 5 feet away\
      \ from the raider."
    "name": "Shield Shove"
"reactions":
  - "desc": "When the raider is wielding a shield and is hit by an attack made by\
      \ a creature they can see, the raider gains a +4 bonus to AC against the triggering\
      \ attack. If this causes the attack to miss, the raider's shield breaks, and\
      \ until they get a new shield, their AC is reduced by 2 and they can't use this\
      \ reaction or make a Shield Shove attack."
    "name": "Splinter Shield"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/human-raider-whereevillives.png"
```
^statblock