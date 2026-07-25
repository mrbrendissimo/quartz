---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/chondathan-human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Darathra Shendrel
---
# [Darathra Shendrel](3-Mechanics\CLI\bestiary\npc/darathra-shendrel-skt.md)
*Source: Storm King's Thunder p. 253*  

As the Lord Protector of Triboar and a secret agent of the Harpers, Darathra has sworn an oath to defend the town. She takes her duty very seriously. In addition to her gear, Darathra has an unarmored warhorse named Buster.

Ideal:"Good people should be given every chance to prosper, free of tyranny."

Bond:"I'll lay down my life to protect Triboar and its citizens."

Flaw:"I refuse to back down. Push me, and I'll push back."

```statblock
"name": "Darathra Shendrel (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Chondathan human"
"alignment": "Lawful Good"
"ac": !!int "14"
"ac_class": "[breastplate](/3-Mechanics/CLI/items/breastplate-xphb.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "14"
  - !!int "11"
  - !!int "11"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+2"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Investigation](/3-Mechanics/CLI/skills.md#Investigation)"
    "desc": "+2"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+4"
"senses": "passive Perception 12"
"languages": "Common"
"traits":
  - "desc": "Darathra has advantage on saving throws against being [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
    "name": "Brave"
  - "desc": "As the Lord Protector of Triboar and a secret agent of the Harpers, Darathra\
      \ has sworn an oath to defend the town. She takes her duty very seriously. In\
      \ addition to her gear, Darathra has an unarmored warhorse named Buster.\n\n\
      Ideal: \"Good people should be given every chance to prosper, free of tyranny.\"\
      \n\nBond: \"I'll lay down my life to protect Triboar and its citizens.\"\n\n\
      Flaw: \"I refuse to back down. Push me, and I'll push back.\""
    "name": "Roleplaying Information"
"actions":
  - "desc": "Darathra makes two melee attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10\
      \ (2d6 + 3) slashing damage"
    "name": "Greatsword"
  - "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
      \ 5 (d10) piercing damage. Darathra carries twenty crossbow bolts."
    "name": "Heavy Crossbow"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/darathra-shendrel-skt.webp"
```
^statblock