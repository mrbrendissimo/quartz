---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/turami-human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Urgala Meltimer
---
# [Urgala Meltimer](3-Mechanics\CLI\bestiary\npc/urgala-meltimer-skt.md)
*Source: Storm King's Thunder p. 254*  

A retired adventurer, Urgala owns a respectable inn, the Northshield House, and she doesn't want to see it or her neighbors' homes destroyed. She has no tolerance for monsters or bullies.

Ideal:"We live in a violent world, and sometimes violence is necessary for survival."

Bond:"My home is my life. Threaten it, and I'll hurt you."

Flaw:"I know how treacherous and greedy adventurers can be. I don't trust them-any of them."

```statblock
"name": "Urgala Meltimer (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Turami human"
"alignment": "Lawful Good"
"ac": !!int "12"
"ac_class": "[leather armor](/3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "13"
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+3"
"senses": "passive Perception 12"
"languages": "Common, Giant"
"traits":
  - "desc": "Any weapon attack that Urgala makes against a giant deals an extra 7\
      \ (2d6) damage on a hit."
    "name": "Giant Slayer"
  - "desc": "A retired adventurer, Urgala owns a respectable inn, the North shield\
      \ House, and she doesn't want to see it or her neighbors' homes destroyed. She\
      \ has no tolerance for monsters or bullies.\n\nIdeal: \"We live in a violent\
      \ world, and sometimes violence is necessary for survival.\"\n\nBond: \"My home\
      \ is my life. Threaten it, and I'll hurt you.\"\n\nFlaw: \"I know how treacherous\
      \ and greedy adventurers can be. I don't trust them—any of them.\""
    "name": "Roleplaying Information"
"actions":
  - "desc": "Urgala makes two attacks with her morningstar or her shortbow."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
      \ + 3) piercing damage."
    "name": "Morningstar"
  - "desc": "Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target. Hit:\
      \ 5 (1d6 + 1) piercing damage. Urgala carries a quiver of twenty arrows."
    "name": "Shortbow"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/urgala-meltimer-skt.webp"
```
^statblock