---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/artillery
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Human Trickshot Slime Servant
---
# [Human Trickshot Slime Servant](3-Mechanics\CLI\bestiary\humanoid/human-trickshot-slime-servant-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 135*  

If a creature spends 1 continuous minute under the effect of the slime from an olothec's Devolving Tentacle attack, that effect ends and their flesh devolves into a translucent primordial state. The creature loses their memories and sense of self, becoming a slime servant NPC who is loyal to the olothec.

```statblock
"name": "Human Trickshot Slime Servant (WhereEvilLives)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Artillery"
"alignment": "Any alignment"
"ac": !!int "14"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "14"
  - !!int "10"
  - !!int "14"
  - !!int "14"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "passive Perception 14"
"languages": "Common"
"cr": "2"
"traits":
  - "desc": "The trickshot can breathe air and water."
    "name": "Amphibious"
  - "desc": "When the trickshot makes an attack, they have advantage on the attack\
      \ roll."
    "name": "Exploit Opening (3/Day)"
  - "desc": "When the trickshot hits a creature within 30 feet of them with a ranged\
      \ weapon attack, they deal an extra 7 (2d6) piercing damage. Additionally, being\
      \ within 5 feet of an enemy doesn't impose disadvantage on the trickshot's ranged\
      \ attack rolls."
    "name": "Point Blank Shooting"
  - "desc": "Ithu'rath can sense anything the trickshot senses, and Ithu'rath can\
      \ speak through their body."
    "name": "Servant Senses"
"actions":
  - "desc": "Ranged Weapon Attack: +6 to hit, range 100/400 ft., one target. Hit:\
      \ 9 (1d10 + 4) piercing damage."
    "name": "Heavy Crossbow"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
      \ + 4) piercing damage."
    "name": "Bayonet"
  - "desc": "The trickshot uses a special ricocheting bolt to make one Heavy Crossbow\
      \ attack against a target within 100 feet of them, then a second Heavy Crossbow\
      \ attack against a different target within 30 feet of the first target."
    "name": "Ricochet Bolt (Recharge 5-6)"
"source":
  - "WhereEvilLives"
```
^statblock