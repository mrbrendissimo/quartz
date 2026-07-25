---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/artillery
- ttrpg-cli/monster/type/humanoid/goblin
statblock: inline
statblock-link: "#^statblock"
aliases:
- Goblin Sniper
---
# [Goblin Sniper](3-Mechanics\CLI\bestiary\humanoid/goblin-sniper-fleemortals.md)
*Source: Flee, Mortals! p. 127*  

```statblock
"name": "Goblin Sniper (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "goblin, Artillery"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[leather armor](/3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "13"
"hit_dice": "3d6 + 3"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "12"
  - !!int "10"
  - !!int "12"
  - !!int "8"
"speed": "30 ft., climb 20 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Goblin"
"cr": "1/2"
"traits":
  - "desc": "The sniper doesn't provoke opportunity attacks when they move out of\
      \ an enemy's reach."
    "name": "Crafty"
  - "desc": "If the sniper misses with a ranged weapon attack while they are hidden,\
      \ they remain hidden. Additionally, if the sniper hits a target with a ranged\
      \ weapon attack while they have advantage on the attack roll, the attack deals\
      \ an extra 3 (d6) damage."
    "name": "Sniper"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. Hit: 5 (1d4 + 3) piercing damage."
    "name": "Dagger"
  - "desc": "Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. Hit:\
      \ 6 (1d6 + 3) piercing damage."
    "name": "Shortbow"
"bonus_actions":
  - "desc": "The sniper takes the Hide action."
    "name": "Sneak"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/goblin-sniper-fleemortals.webp"
```
^statblock