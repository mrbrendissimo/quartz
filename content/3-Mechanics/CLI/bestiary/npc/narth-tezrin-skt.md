---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/tethyrian-human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Narth Tezrin
---
# [Narth Tezrin](3-Mechanics\CLI\bestiary\npc/narth-tezrin-skt.md)
*Source: Storm King's Thunder p. 254*  

Narth sells gear to adventurers, and he also has an adventurous spirit. The Lionshield Coster pays him well, but he longs to make a name for himself. At the same time, he runs a business with his partner Alaestra and knows she wouldn't forgive him if he ran off and never returned.

Ideal:"The bigger the risk, the greater the reward."

Bond:"I adore my colleague Alaestra, and I'd like to do something to impress her."

Flaw:"I'll risk life and limb to become a legend."

```statblock
"name": "Narth Tezrin (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Tethyrian human"
"alignment": "Chaotic Good"
"ac": !!int "12"
"hp": !!int "18"
"hit_dice": "4d8"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "10"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Investigation](/3-Mechanics/CLI/skills.md#Investigation)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+5"
"senses": "passive Perception 16"
"languages": "Common, Dwarvish"
"traits":
  - "desc": "On each of his turns, Narth can use a bonus action to take the Dash,\
      \ Disengage, or Hide action."
    "name": "Cunning Action"
  - "desc": "Narth sells gear to adventurers, and he also has an adventurous spirit.\
      \ The Lionshield Coster pays him well, but he longs to make a name for himself.\
      \ At the same time, he runs a business with his partner Alaestra and knows she\
      \ wouldn't forgive him if he ran off and never returned.\n\nIdeal: \"The bigger\
      \ the risk, the greater the reward.\"\n\nBond: \"I adore my colleague Alestra,\
      \ and I'd like to do something to impress her.\"\n\nFlaw: \"I'll risk life and\
      \ limb to become a legend.-\""
    "name": "Roleplaying Information"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
      \ + 2) piercing damage."
    "name": "Shortsword"
  - "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
      \ 5 (1d6 + 2) piercing damage. Narth carries twenty crossbow bolts."
    "name": "Hand Crossbow"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/narth-tezrin-skt.webp"
```
^statblock