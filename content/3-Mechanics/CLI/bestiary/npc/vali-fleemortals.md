---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/ambusher
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
- Vali
---
# [Vali](3-Mechanics\CLI\bestiary\npc/vali-fleemortals.md)
*Source: Flee, Mortals! p. 371*  

```statblock
"name": "Vali (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf, Ambusher"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "[leather armor](/3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"modifier": !!int "5"
"stats":
  - !!int "11"
  - !!int "20"
  - !!int "12"
  - !!int "11"
  - !!int "20"
  - !!int "10"
"speed": "35 ft., climb 35 ft."
"saves":
  - "dexterity": !!int "7"
  - "wisdom": !!int "7"
  - "charisma": !!int "2"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+9"
"senses": "darkvision 60 ft., passive Perception 19"
"languages": "Common, Elvish, Sylvan"
"cr": "4"
"traits":
  - "desc": "While Vali is hidden, he doesn't give away his location if he makes a\
      \ weapon attack and misses."
    "name": "Cloak and Dagger"
  - "desc": "Vali leaves no tracks or other traces of his presence unless he wants\
      \ to."
    "name": "Deft-Footed"
  - "desc": "When a creature targets Vali with an attack, power, or spell, the creature\
      \ must succeed on a DC 15 Wisdom saving throw or be [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ by him until the end of his next turn (no action required)."
    "name": "Elf Glamour (1/Day)"
"actions":
  - "desc": "Vali makes two Shortsword attacks, or he makes two Waning Moon attacks\
      \ and uses Waning Moon Fade, if available."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d6\
      \ + 5) piercing damage."
    "name": "Shortsword"
  - "desc": "Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. Hit:\
      \ 9 (1d8 + 5) piercing damage. If the target is a creature who can't see Vali,\
      \ the target takes an extra 7 (2d6) force damage."
    "name": "Waning Moon"
  - "desc": "Vali becomes [invisible](/3-Mechanics/CLI/conditions.md#Invisible) for\
      \ 1 minute and takes the Hide action. This invisibility ends if Vali makes an\
      \ attack, casts a spell, or manifests a power."
    "name": "Waning Moon Fade (1/Day)"
"bonus_actions":
  - "desc": "Vali takes the Disengage or Hide action."
    "name": "Nimble Escape"
"source":
  - "FleeMortals"
```
^statblock