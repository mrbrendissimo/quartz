---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/soldier
statblock: inline
statblock-link: "#^statblock"
aliases:
- Radlee Thugram
---
# [Radlee Thugram](3-Mechanics\CLI\bestiary\npc/radlee-thugram-fleemortals.md)
*Source: Flee, Mortals! p. 384*  

```statblock
"name": "Radlee Thugram (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Soldier"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[plate](/3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "130"
"hit_dice": "20d8 + 40"
"modifier": !!int "3"
"stats":
  - !!int "24"
  - !!int "16"
  - !!int "15"
  - !!int "11"
  - !!int "16"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "strength": !!int "10"
  - "constitution": !!int "5"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+10"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+6"
"senses": "truesight 60 ft., passive Perception 16"
"languages": "Common"
"cr": "7"
"traits":
  - "desc": "When Radlee makes an attack, she has advantage on the attack roll."
    "name": "Exploit Opening (3/Day)"
  - "desc": "Radlee has advantage on saving throws against being moved against her\
      \ will or knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Sure-Footed"
  - "desc": "Radlee has advantage on initiative checks.\n\nWhile she isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ Radlee and each ally within 30 feet of her who can see or hear her can't be\
      \ surprised."
    "name": "Tactical Vigilance"
"actions":
  - "desc": "Radlee makes three Halberd or three Longbow attacks. Alternatively, she\
      \ makes one Halberd attack and uses Backswipe."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 12\
      \ (1d10 + 7) slashing damage."
    "name": "Halberd"
  - "desc": "Ranged Weapon Attack: +6 to hit, range 150/600 ft., one target. Hit:\
      \ 7 (1d8 + 3) piercing damage."
    "name": "Longbow"
  - "desc": "Radlee swings her halberd's shaft at a creature within 5 feet of her.\
      \ The target must succeed on a DC 18 Strength saving throw or take 16 (3d10)\
      \ bludgeoning damage and be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Backswipe"
"reactions":
  - "desc": "When a creature Radlee can see within 10 feet of her attacks one of her\
      \ allies, Radlee can make a Halberd attack against the attacker."
    "name": "Protector"
"source":
  - "FleeMortals"
```
^statblock