---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/soldier
- ttrpg-cli/monster/type/humanoid/time-raider
statblock: inline
statblock-link: "#^statblock"
aliases:
- Time Raider Armiger
---
# [Time Raider Armiger](3-Mechanics\CLI\bestiary\humanoid/time-raider-armiger-fleemortals.md)
*Source: Flee, Mortals! p. 230*  

```statblock
"name": "Time Raider Armiger (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "time raider, Soldier"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[breastplate](/3-Mechanics/CLI/items/breastplate-xphb.md)"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "16"
  - !!int "12"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "5"
  - "constitution": !!int "4"
  - "intelligence": !!int "5"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+2"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"damage_resistances": "psychic"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Common, Kuran'zoi"
"cr": "3"
"traits":
  - "desc": "The armiger is immune to any effect that would sense their emotions,\
      \ read their thoughts, reveal they are lying, or reveal their alignment or location."
    "name": "Psychic Scar"
"actions":
  - "desc": "The armiger makes two attacks using Blaster, Serrated Saber, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
      \ + 3) slashing damage, and the target has disadvantage on their next attack\
      \ roll made before the start of the armiger's next turn."
    "name": "Serrated Saber"
  - "desc": "Ranged Weapon Attack: +4 to hit, range 30/90 ft., one target. Hit:\
      \ 5 (1d6 + 2) radiant damage."
    "name": "Blaster"
  - "desc": "The armiger rains down telekinetic force on a creature they can see within\
      \ 30 feet of them. The target must succeed on a DC 13 Strength saving throw\
      \ or take 7 (3d4) force damage and be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Concussive Slam (1st-Order Power)"
"reactions":
  - "desc": "When another creature the armiger can see within 30 feet of them is hit\
      \ with an attack, the armiger floods the attacker's mind with the nauseous pain\
      \ of their target. The attacker must succeed on a DC 13 Constitution saving\
      \ throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) until the\
      \ end of their next turn."
    "name": "Sickening Sympathy (2nd-Order Power)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/time-raider-armiger-fleemortals.png"
```
^statblock