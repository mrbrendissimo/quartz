---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Cryovain
---
# [Cryovain](3-Mechanics\CLI\bestiary\npc/cryovain-skt.md)
*Source: Storm King's Thunder p. 165*  

```statblock
"name": "Cryovain (SKT)"
"size": "Huge"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d12 + 96"
"modifier": !!int "0"
"stats":
  - !!int "22"
  - !!int "10"
  - !!int "22"
  - !!int "8"
  - !!int "12"
  - !!int "12"
"speed": "40 ft., burrow 30 ft., fly 80 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "11"
  - "wisdom": !!int "6"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+11"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_immunities": "cold"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic"
"cr": "13"
"traits":
  - "desc": "The dragon can move across and climb icy surfaces without needing to\
      \ make an ability check. Additionally, difficult terrain composed of ice or\
      \ snow doesn't cost it extra movement."
    "name": "Ice Walk"
  - "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The dragon can use its Frightful Presence. It then makes three attacks:\
      \ one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 17\
      \ (2d10 + 6) piercing damage plus 4 (d8) cold damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 13\
      \ (2d6 + 6) slashing damage."
    "name": "Claw"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 15 ft., one target. Hit: 15\
      \ (2d8 + 6) bludgeoning damage."
    "name": "Tail"
  - "desc": "Each creature of the dragon's choice that is within 120 feet of the dragon\
      \ and aware of it must succeed on a DC 14 Wisdom saving throw or become [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success. If a creature's saving\
      \ throw is successful or the effect ends for it, the creature is immune to the\
      \ dragon's Frightful Presence for the next 24 hours."
    "name": "Frightful Presence"
  - "desc": "The dragon exhales an icy blast in a 60-foot cone. Each creature in that\
      \ area must make a DC 19 Constitution saving throw, taking 54 (12d8) cold damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Cold Breath (Recharge 5-6)"
"legendary_actions":
  - "desc": "The dragon makes a Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ check."
    "name": "Detect"
  - "desc": "The dragon makes a tail attack."
    "name": "Tail Attack"
  - "desc": "The dragon beats its wings. Each creature within 10 feet of the dragon\
      \ must succeed on a DC 19 Dexterity saving throw or take 13 (2d6 + 6) bludgeoning\
      \ damage and be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone). The dragon\
      \ can then fly up to half its flying speed."
    "name": "Wing Attack (Costs 2 Actions)"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/cryovain-skt.webp"
```
^statblock