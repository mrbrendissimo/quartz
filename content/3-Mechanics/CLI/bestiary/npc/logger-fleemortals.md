---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Logger
---
# [Logger](3-Mechanics\CLI\bestiary\npc/logger-fleemortals.md)
*Source: Flee, Mortals! p. 370*  

```statblock
"name": "Logger (FleeMortals)"
"size": "Large"
"type": "plant"
"subtype": "Brute"
"alignment": "Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "102"
"hit_dice": "12d10 + 36"
"modifier": !!int "-1"
"stats":
  - !!int "22"
  - !!int "8"
  - !!int "16"
  - !!int "6"
  - !!int "10"
  - !!int "6"
"speed": "30 ft., swim 30 ft."
"saves":
  - "strength": !!int "9"
  - "constitution": !!int "6"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "cold, fire"
"damage_immunities": "lightning"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [deafened](/3-Mechanics/CLI/conditions.md#Deafened),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": "understands Sylvan but can't speak"
"cr": "5"
"traits":
  - "desc": "Whenever Logger is subjected to lightning damage, they take no damage\
      \ and instead regain a number of hit points equal to the lightning damage dealt."
    "name": "Lightning Absorption"
"actions":
  - "desc": "Logger makes two Slam attacks. If they are in a fury (see Nature's Fury),\
      \ they instead make three Slam attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 13\
      \ (2d6 + 6) bludgeoning damage."
    "name": "Slam"
  - "desc": "Vines lash out from Logger's body.\n\nEach enemy within 30 feet of them\
      \ must succeed on a DC 17 Strength saving throw or take 9 (1d6 + 6) bludgeoning\
      \ damage and be [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape\
      \ DC 17) and pulled up to 30 feet directly toward Logger."
    "name": "Entangling Vines"
"bonus_actions":
  - "desc": "Logger enters a fury for 1 minute.\n\nWhile in a fury, Logger has advantage\
      \ on Strength checks and saving throws, and they can make an extra Slam attack\
      \ when they use Multiattack. If Logger ends their turn without damaging another\
      \ creature on that turn, the fury ends early."
    "name": "Nature's Fury (1/Day)"
"source":
  - "FleeMortals"
```
^statblock