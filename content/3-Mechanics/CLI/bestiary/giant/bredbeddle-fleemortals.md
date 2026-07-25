---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/brute
- ttrpg-cli/monster/type/giant/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bredbeddle
---
# [Bredbeddle](3-Mechanics\CLI\bestiary\giant/bredbeddle-fleemortals.md)
*Source: Flee, Mortals! p. 316*  

```statblock
"name": "Bredbeddle (FleeMortals)"
"size": "Huge"
"type": "giant"
"subtype": "shapechanger, Brute"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "157"
"hit_dice": "15d12 + 60"
"modifier": !!int "0"
"stats":
  - !!int "24"
  - !!int "10"
  - !!int "18"
  - !!int "12"
  - !!int "12"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3"
"senses": "blindsight 60 ft. (blind beyond this radius in true form), passive Perception\
  \ 14"
"languages": "Common, Giant (can't speak in true form)"
"cr": "8"
"traits":
  - "desc": "The bredbeddle can't be [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ or [deafened](/3-Mechanics/CLI/conditions.md#Deafened)."
    "name": "Headless (True Form Only)"
  - "desc": "If the bredbeddle dies, they return to life in d6 months with all their\
      \ hit points. If their body was destroyed, it reforms in an unoccupied space\
      \ nearest to where they died. Only a [wish](/3-Mechanics/CLI/spells/wish-xphb.md)\
      \ spell or finding and destroying the bredbeddle's true head can prevent this\
      \ trait from functioning."
    "name": "Rejuvenation"
"actions":
  - "desc": "The bredbeddle makes two Executioner's Axe attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 23\
      \ (3d10 + 7) slashing damage."
    "name": "Executioner's Axe"
  - "desc": "Melee Weapon Attack: +10 to hit, reach 15 ft., one Large or smaller\
      \ Giant or Humanoid with a head. Hit: 40 (6d10 + 7) slashing damage, and the\
      \ target must make a DC 15 Constitution saving throw. On a failed save, the\
      \ bredbeddle cuts off the target's head, which lands at the target's feet. A\
      \ creature beheaded in this way remains alive unless reduced to 0 hit points,\
      \ but they are [blinded](/3-Mechanics/CLI/conditions.md#Blinded) and [deafened](/3-Mechanics/CLI/conditions.md#Deafened),\
      \ and they can't speak. A creature can use an action to place a beheaded creature's\
      \ head back on their neck, reattaching the head and ending the effect. A beheaded\
      \ creature dies if they are separated from their head for more than 24 hours."
    "name": "Beheading Strike (Recharge 5-6)"
"bonus_actions":
  - "desc": "The bredbeddle picks up a severed Giant or Humanoid head within 15 feet\
      \ of them and places it on the bredbeddle's neck. The bredbeddle then polymorphs\
      \ into that Giant or Humanoid creature. While polymorphed, the bredbeddle's\
      \ statistics change as follows:\n\n- They can speak.  \n- They lose their Headless\
      \ trait.  \n- Their size changes to match the creature whose head they bear.\
      \  \n- They can see normally, and they gain any special senses the creature's\
      \ head had.  \n- Any equipment they are wearing or carrying temporarily changes\
      \ to match their size, but the equipment's statistics do not change.  \n\nThe\
      \ bredbeddle reverts to their true form if they die, if their head is removed,\
      \ or after 24 hours. When they revert, the head falls off and can't be reattached\
      \ to the bredbeddle.\n\nA creature who can reach the bredbeddle can use an action\
      \ to make a DC 18 Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics))\
      \ check, removing the head from the bredbeddle on a success."
    "name": "Get a Head"
  - "desc": "The bredbeddle removes their head, reverting to their true form, and\
      \ throws the head at a creature they can see within 60 feet of them.\n\nThe\
      \ head lands in the target's space, and the target must succeed on a DC 18 Dexterity\
      \ saving throw or take 18 (2d10 + 7) bludgeoning damage."
    "name": "Toss Head (Polymorphed Form Only)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/giant/token/bredbeddle-fleemortals.png"
```
^statblock