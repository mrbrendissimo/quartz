---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/shou-human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Zi Liang
---
# [Zi Liang](3-Mechanics\CLI\bestiary\npc/zi-liang-skt.md)
*Source: Storm King's Thunder p. 251*  

Zi Liang is a devout worshiper of Chauntea, the Earth Mother. She has considerably less faith in Goldenfields' defenders, so she patrols the temple-farm during her off-duty hours.

Ideal:"If we faithfully tend to our gardens and our fields, Chauntea will smile upon us."

Bond:"Goldenfields is the breadbasket of the North. People depend on its safety and prosperity, and I'll do what must be done to protect it."

Flaw:"I don't trust authority. I do what my heart says is right."

```statblock
"name": "Zi Liang (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Shou human"
"alignment": "Chaotic Good"
"ac": !!int "15"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "15"
  - !!int "11"
  - !!int "14"
  - !!int "16"
  - !!int "11"
"speed": "30 ft."
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+4"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"senses": "passive Perception 15"
"languages": "Common, Elvish, Goblin"
"traits":
  - "desc": "While Zi is wearing no armor and wielding no shield, her AC includes\
      \ her Wisdom modifier."
    "name": "Unarmored Defense"
  - "desc": "Zi Liang is a devout worshiper of Chauntea, the Earth Mother. She has\
      \ considerably less faith in Goldenfields' defenders, so she patrols the temple-farm\
      \ during her off-duty hours.\n\nIdeal: \"If we faithfully tend to our gardens\
      \ and our fields, Chauntea will smile upon us.\"\n\nBond: \"Goldenfields is\
      \ the breadbasket of the North. People depend on its safety and prosperity,\
      \ and I'll do what must be done to protect it.\"\n\nFlaw: \"I don't trust authority.\
      \ I do what my heart says is right.\""
    "name": "Roleplaying Information"
"actions":
  - "desc": "Zi makes two melee attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
      \ + 1) bludgeoning damage, or 5 (1d8 + 1) bludgeoning damage if used with both\
      \ hands."
    "name": "Quarterstaff"
  - "desc": "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit:\
      \ 4 (1d4 + 2) bludgeoning damage. Zi carries twenty sling stones."
    "name": "Sling"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/zi-liang-skt.webp"
```
^statblock