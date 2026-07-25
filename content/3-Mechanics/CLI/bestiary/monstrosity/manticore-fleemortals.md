---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/skirmisher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Manticore
---
# [Manticore](3-Mechanics\CLI\bestiary\monstrosity/manticore-fleemortals.md)
*Source: Flee, Mortals! p. 186*  

```statblock
"name": "Manticore (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Skirmisher"
"alignment": "typically  Neutral"
"ac": !!int "13"
"hp": !!int "76"
"hit_dice": "9d10 + 27"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "7"
"speed": "30 ft., fly 50 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "understands any one language but speaks only through the use of their\
  \ Mimicry trait"
"cr": "3"
"traits":
  - "desc": "When the manticore hits a creature with an attack on the manticore's\
      \ turn, the manticore doesn't provoke opportunity attacks from that creature\
      \ for the rest of that turn."
    "name": "Agile Predator"
  - "desc": "The manticore can mimic any words or phrases they have heard in a language\
      \ they understand. A creature who hears the speech can tell it is an imitation\
      \ with a successful DC 10 Wisdom ([Insight](/3-Mechanics/CLI/skills.md#Insight))\
      \ check."
    "name": "Mimicry"
"actions":
  - "desc": "The manticore makes one Bite and one Claw attack, or two Tail Spike attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d8\
      \ + 4) piercing damage. If the target is a creature who is [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the manticore, they take an extra 4 (d8) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 9 (1d10\
      \ + 4) slashing damage, and the manticore can move the target up to 5 feet horizontally."
    "name": "Claw"
  - "desc": "Ranged Weapon Attack: +5 to hit, range 60/120 ft., one target. Hit:\
      \ 5 (1d4 + 3) piercing damage plus 3 (d6) poison damage, and the target must\
      \ succeed on a DC 13 Constitution saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the end of their next turn."
    "name": "Tail Spike"
"bonus_actions":
  - "desc": "Each enemy within 120 feet who can hear the manticore must succeed on\
      \ a DC 13 Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the manticore for 1 minute (save ends at end of turn). If the initial saving\
      \ throw fails by 5 or more, a creature is also [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ while [frightened](/3-Mechanics/CLI/conditions.md#Frightened) in this way."
    "name": "Trumpeting Howl (1/Day)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/manticore-fleemortals.png"
```
^statblock