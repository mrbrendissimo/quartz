---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/ambusher
- ttrpg-cli/monster/type/humanoid/angulotl
statblock: inline
statblock-link: "#^statblock"
aliases:
- Angulotl Slink
---
# [Angulotl Slink](3-Mechanics\CLI\bestiary\humanoid/angulotl-slink-fleemortals.md)
*Source: Flee, Mortals! p. 31*  

```statblock
"name": "Angulotl Slink (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "angulotl, Ambusher"
"alignment": "Any alignment"
"ac": !!int "13"
"hp": !!int "45"
"hit_dice": "10d6 + 10"
"modifier": !!int "3"
"stats":
  - !!int "7"
  - !!int "17"
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "8"
"speed": "20 ft., climb 20 ft., swim 30 ft."
"saves":
  - "dexterity": !!int "5"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+4"
"damage_immunities": "poison"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Angulotl"
"cr": "2"
"traits":
  - "desc": "The slink can breathe air and water."
    "name": "Amphibious"
  - "desc": "The slink can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "When a creature hits the slink with a melee attack while within 5 feet\
      \ of them or touches the slink, that creature takes 2 (d4) poison damage."
    "name": "Toxiferous"
"actions":
  - "desc": "The slink makes one Poison Dagger attack and one Tongue Nab attack."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 5 (1d4 + 3) piercing damage plus 10 (3d6) poison damage,\
      \ and the target can't take reactions until the start of their next turn."
    "name": "Poison Dagger"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one Medium or smaller\
      \ creature. Hit: The slink grabs one Small or Tiny object the slink can see\
      \ that the target is holding or carrying. The slink can catch the object if\
      \ they have a free hand, otherwise it lands at the slink's feet."
    "name": "Tongue Nab"
"bonus_actions":
  - "desc": "The slink jumps a number of feet up to their walking speed, then takes\
      \ the Hide action."
    "name": "Hop and Hide"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/angulotl-slink-fleemortals.png"
```
^statblock