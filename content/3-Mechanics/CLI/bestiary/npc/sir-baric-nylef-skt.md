---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/illuskan-human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Sir Baric Nylef
---
# [Sir Baric Nylef](3-Mechanics\CLI\bestiary\npc/sir-baric-nylef-skt.md)
*Source: Storm King's Thunder p. 249*  

As a knight of the Order of the Gauntlet, Sir Baric has sworn oaths to catch evildoers and bring them to justice. His current quarry is a dwarf brigand, Worvil "the Weevil" Forkbeard, who is rumored to be hiding in Icewind Dale. In addition to his gear, Sir Baric has an unarmored warhorse, Henry.

Ideal:"Evil must not be allowed to thrive in this world."

Bond:"Tyr is my lord; the order, my family. Through my actions, I shall honor both."

Flaw:"I'm not afraid to die. When Tyr finally calls me, I'll go to him happily."

```statblock
"name": "Sir Baric Nylef (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Illuskan human"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "[plate armor](/3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "11"
  - !!int "14"
  - !!int "11"
  - !!int "15"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Investigation](/3-Mechanics/CLI/skills.md#Investigation)"
    "desc": "+2"
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+4"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+4"
"senses": "passive Perception 12"
"languages": "Common"
"traits":
  - "desc": "Baric has advantage on saving throws against being [frightened](/3-Mechanics/CLI/conditions.md#Frightened)."
    "name": "Brave"
  - "desc": "As a knight of the Order of the Gauntlet, Sir Baric has sworn oaths to\
      \ catch evildoers and bring them to justice. His current quarry is a dwarf brigand,\
      \ Worvil \"the Weevil\" Forkbeard, who is rumored to be hiding in Icewind Dale.\
      \ In addition to his gear, Sir Baric has an unarmored warhorse, Henry.\n\nIdeal:\
      \ \"Evil must not be allowed to thrive in this world.\"\n\nBond: \"Tyr is my\
      \ lord; the order, my family. Through my actions, I shall honor both.\"\n\n\
      Flaw: \"I'm not afraid to die. When Tyr finally calls me, I'll go to him happily.\""
    "name": "Roleplaying Information"
"actions":
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 11\
      \ (2d6 + 4) bludgeoning damage."
    "name": "Maul"
  - "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
      \ 5 (d10) piercing damage. Baric carries twenty crossbow bolts."
    "name": "Heavy Crossbow"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/sir-baric-nylef-skt.webp"
```
^statblock