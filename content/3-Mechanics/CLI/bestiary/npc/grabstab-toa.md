---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Grabstab
---
# [Grabstab](3-Mechanics\CLI\bestiary\npc/grabstab-toa.md)
*Source: Tomb of Annihilation p. 89*  

```statblock
"name": "Grabstab (ToA)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "[chain shirt](/3-Mechanics/CLI/items/chain-shirt-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "21"
"hit_dice": "6d6"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "8"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Goblin"
"cr": "1"
"traits":
  - "desc": "Grabstab can take the Disengage or Hide action as a bonus action on each\
      \ of its turns."
    "name": "Nimble Escape"
"actions":
  - "desc": "Grabstab makes two attacks with its scimitar. The second attack has disadvantage."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
      \ + 2) slashing damage."
    "name": "Scimitar"
  - "desc": "Melee  or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. Hit: 3 (d6) piercing damage."
    "name": "Javelin"
"reactions":
  - "desc": "When a creature Grabstab can see targets it with an attack, Grabstab\
      \ chooses another goblin within 5 feet of it. The two goblins swap places, and\
      \ the chosen goblin becomes the target instead."
    "name": "Redirect Attack"
"source":
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/grabstab-toa.webp"
```
^statblock