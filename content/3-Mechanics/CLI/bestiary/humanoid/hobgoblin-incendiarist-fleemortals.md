---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/artillery
- ttrpg-cli/monster/type/humanoid/hobgoblin
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hobgoblin Incendiarist
---
# [Hobgoblin Incendiarist](3-Mechanics\CLI\bestiary\humanoid/hobgoblin-incendiarist-fleemortals.md)
*Source: Flee, Mortals! p. 150*  

```statblock
"name": "Hobgoblin Incendiarist (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "hobgoblin, Artillery"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "12"
  - !!int "10"
  - !!int "16"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"damage_resistances": "fire"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Goblin, Infernal"
"cr": "1"
"traits":
  - "desc": "When the incendiarist dies, their corpse unleashes a spray of burning\
      \ orange ichor. Each creature within 5 feet of the incendiarist takes 3 fire\
      \ damage."
    "name": "Infernal Ichor"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
      \ + 3) piercing damage."
    "name": "Shortsword"
  - "desc": "Ranged Weapon Attack: +5 to hit, range 100/400 ft., one target. Hit:\
      \ 8 (1d10 + 3) piercing damage, and if the target is a creature, they are set\
      \ on fire. While on fire, the target takes 3 (d6) fire damage at the end of\
      \ each of their turns, and the target or another creature who can reach them\
      \ can use an action to put out the flames. A creature who is already on fire\
      \ suffers no additional effect from being set on fire in this way again."
    "name": "Blazing Crossbow"
  - "desc": "The incendiarist shoots an explosive mote of fire at a creature they\
      \ can see within 100 feet of them. The target must succeed on a DC 13 Dexterity\
      \ saving throw or take 7 (2d6) fire damage and, if they are Large or smaller,\
      \ fall [prone](/3-Mechanics/CLI/conditions.md#Prone). All other creatures within\
      \ 15 feet of the target must succeed on a DC 13 Dexterity saving throw or take\
      \ 3 (d6) fire damage."
    "name": "Fire Mote (Recharge 6)"
"source":
  - "FleeMortals"
```
^statblock