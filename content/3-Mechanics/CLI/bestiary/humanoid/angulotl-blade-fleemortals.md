---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/angulotl
- ttrpg-cli/monster/type/humanoid/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Angulotl Blade
---
# [Angulotl Blade](3-Mechanics\CLI\bestiary\humanoid/angulotl-blade-fleemortals.md)
*Source: Flee, Mortals! p. 28*  

```statblock
"name": "Angulotl Blade (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "angulotl, Skirmisher"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "14"
"hit_dice": "4d6"
"modifier": !!int "2"
"stats":
  - !!int "7"
  - !!int "15"
  - !!int "11"
  - !!int "10"
  - !!int "14"
  - !!int "8"
"speed": "20 ft., climb 20 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "poison"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Angulotl"
"cr": "1/4"
"traits":
  - "desc": "The blade can breathe air and water."
    "name": "Amphibious"
  - "desc": "Opportunity attacks against the blade are made with disadvantage."
    "name": "Slippery"
  - "desc": "When a creature hits the blade with a melee attack while within 5 feet\
      \ of them or touches the blade, that creature takes 2 (d4) poison damage."
    "name": "Toxiferous"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
      \ + 2) slashing damage."
    "name": "Machete"
  - "desc": "Ranged Weapon Attack: +4 to hit, range 20/60 ft., one target. Hit:\
      \ 4 (1d4 + 2) piercing damage."
    "name": "Dart"
"bonus_actions":
  - "desc": "The blade jumps a number of feet up to their walking speed. If the blade\
      \ uses this bonus action to jump at least 10 feet straight toward a creature,\
      \ the next Machete attack the blade makes against that creature on the same\
      \ turn is made with advantage."
    "name": "Wild Hop"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/angulotl-blade-fleemortals.png"
```
^statblock