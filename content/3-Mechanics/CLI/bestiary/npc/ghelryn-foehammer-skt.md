---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/shield-dwarf
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ghelryn Foehammer
---
# [Ghelryn Foehammer](3-Mechanics\CLI\bestiary\npc/ghelryn-foehammer-skt.md)
*Source: Storm King's Thunder p. 255*  

The blacksmith Ghelryn has a good heart, but he hates orcs and giants-hates them with a fiery passion. He considers it the solemn duty of all dwarves to cave in their skulls!

Ideal:"It is incumbent upon every dwarf to forge a legacy."

Bond:"I stand for Clan Foehammer and all dwarvenkind."

Flaw:"I never run from a fight, especially if it involves killing orcs or giants."

```statblock
"name": "Ghelryn Foehammer (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Shield dwarf"
"alignment": "Lawful Good"
"ac": !!int "14"
"ac_class": "[breastplate](/3-Mechanics/CLI/items/breastplate-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "30"
"hit_dice": "4d8 + 12"
"modifier": !!int "-2"
"stats":
  - !!int "18"
  - !!int "7"
  - !!int "17"
  - !!int "10"
  - !!int "11"
  - !!int "11"
"speed": "25 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+2"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
"damage_resistances": "poison"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Dwarvish"
"traits":
  - "desc": "Ghelryn has advantage on saving throws against poison."
    "name": "Dwarven Resilience"
  - "desc": "Any weapon attack that Ghelryn makes against a giant deals an extra 7\
      \ (2d6) damage on a hit."
    "name": "Giant Slayer"
  - "desc": "The blacksmith Ghelryn has a good heart, but he hates orcs and giants—\
      hates them with a fiery passion. He considers it the solemn duty of all dwarves\
      \ to cave in their skulls!\n\nIdeal: \"It is incumbent upon every dwarf to forge\
      \ a legacy.\"\n\nBond: \"I stand for Clan Foehammer and all dwarvenkind.\"\n\
      \nFlaw: \"I never run from a fight, especially if it involves killing orcs or\
      \ giants.\""
    "name": "Roleplaying Information"
"actions":
  - "desc": "Ghelryn makes two battleaxe attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
      \ + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands."
    "name": "Battleaxe"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/ghelryn-foehammer-skt.webp"
```
^statblock