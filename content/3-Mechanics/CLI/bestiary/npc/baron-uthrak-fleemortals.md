---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/leader
statblock: inline
statblock-link: "#^statblock"
aliases:
- Baron Uthrak
---
# [Baron Uthrak](3-Mechanics\CLI\bestiary\npc/baron-uthrak-fleemortals.md)
*Source: Flee, Mortals! p. 166*  

```statblock
"name": "Baron Uthrak (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Leader"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[half plate](/3-Mechanics/CLI/items/half-plate-armor-xphb.md)"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"modifier": !!int "1"
"stats":
  - !!int "19"
  - !!int "12"
  - !!int "19"
  - !!int "14"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "7"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+10"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": "Common"
"cr": "7"
"traits":
  - "desc": "When Baron Uthrak fails a saving throw while holding his magic longsword\
      \ Nine Lives, he can choose to succeed instead. If he does so, he takes 7 (2d6)\
      \ necrotic damage as one of the bloodstones set in the sword's pommel fills\
      \ with his blood."
    "name": "Bloodstones (3 Uses)"
  - "desc": "When Baron Uthrak makes an attack, he has advantage on the attack roll."
    "name": "Exploit Opening (3/Day)"
"actions":
  - "desc": "Baron Uthrak makes two attacks using Nine Lives, Whip, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 9 (1d8\
      \ + 5) slashing damage plus 3 (d6) necrotic damage."
    "name": "Nine Lives"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 15 ft., one target. Hit: 6\
      \ (1d4 + 4) slashing damage, and the target must succeed on a DC 15 Strength\
      \ saving throw or be pulled up to 15 feet toward Baron Uthrak."
    "name": "Whip"
"bonus_actions":
  - "desc": "Baron Uthrak kicks a Large or smaller creature within 5 feet of him.\
      \ The target must succeed on a DC 15 Strength saving throw or take 6 (1d4 +\
      \ 4) bludgeoning damage and be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Kneel, Peasant!"
"reactions":
  - "desc": "When a creature Baron Uthrak can see misses him with a melee attack,\
      \ Baron Uthrak makes a melee attack against that creature."
    "name": "Riposte"
"legendary_actions":
  - "desc": "Baron Uthrak has three villain actions. He can take each action once\
      \ during an encounter after an enemy's turn. He can take these actions in any\
      \ order but can use only one per round."
    "name": ""
  - "desc": "Each ally within 60 feet of Baron Uthrak who can hear him can make a\
      \ ranged weapon attack (no action required)."
    "name": "Action 1: Shoot!"
  - "desc": "Baron Uthrak and each ally within 60 feet of him who can hear him can\
      \ move up to their speed without provoking opportunity attacks. Baron Uthrak\
      \ and each ally enters a defensive stance that lasts until that creature moves\
      \ or is [restrained](/3-Mechanics/CLI/conditions.md#Restrained) or [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated).\
      \ When two or more allies in a defensive stance are within 5 feet of each other,\
      \ attack rolls against them are made with disadvantage."
    "name": "Action 2: Form Up!"
  - "desc": "Baron Uthrak moves up to twice his speed without provoking opportunity\
      \ attacks. During or after this movement, he can make up to four Nine Lives\
      \ or Whip attacks with advantage, each against a different target. After he\
      \ attacks a target in this way, each ally within 5 feet of that target can make\
      \ a melee attack with advantage against the same target (no action required)."
    "name": "Action 3: Lead from the Front"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/npc/token/baron-uthrak-whereevillives.webp"
```
^statblock