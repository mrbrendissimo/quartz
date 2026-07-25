---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/goblin
- ttrpg-cli/monster/type/humanoid/retainer
statblock: inline
statblock-link: "#^statblock"
aliases:
- Goblin Sneak
---
# [Goblin Sneak](3-Mechanics\CLI\bestiary\humanoid/goblin-sneak-fleemortals.md)
*Source: Flee, Mortals! p. 132*  

```statblock
"name": "Goblin Sneak (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "goblin, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "10"
  - !!int "12"
  - !!int "10"
  - !!int "10"
"speed": "30 ft., climb 20 ft."
"saves":
  - "name": "Strength"
    "desc": "+PB"
  - "name": "Dexterity"
    "desc": "+PB"
  - "name": "Constitution"
    "desc": "+PB"
  - "name": "Intelligence"
    "desc": "+PB"
  - "name": "Wisdom"
    "desc": "+PB"
  - "name": "Charisma"
    "desc": "+PB"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+3 plus PB"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3 plus PB"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Goblin"
"actions":
  - "desc": "Melee  or Ranged Weapon Attack: +3 plus PB to hit, reach 5 ft. or range\
      \ 20/60 ft., one target. Hit: 2d4 plus PB piercing damage. Beginning at 7th\
      \ level, the sneak can make this attack twice, instead of once, when they take\
      \ the Attack action on their turn."
    "name": "Signature Attack (Daggers)"
  - "desc": "As an action, the sneak moves up to their speed without provoking opportunity\
      \ attacks. Before, during, or after the move, they can make two signature attacks."
    "name": "3rd Level: Weaving Knives (3/Day)"
  - "desc": "As a bonus action, the sneak takes the Hide action. If the sneak hits\
      \ a creature they are hidden from with an attack on the same turn, the creature\
      \ takes an extra PBd10 piercing damage, and the sneak can immediately take the\
      \ Hide action (no action required)."
    "name": "5th Level: Sneak and Stab (3/Day)"
  - "desc": "As a bonus action, the sneak covers a dagger in a special poison, which\
      \ lasts for 1 hour or until the sneak hits a creature with a signature attack.\
      \ A creature hit with the [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ dagger must make a DC 10 plus PB Constitution saving throw. On a failed save,\
      \ the target takes PBd12 poison damage and is [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ for 1 minute (save ends at the end of turn). On a successful save, the target\
      \ takes only half as much damage and isn't [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)."
    "name": "7th Level: Poisoned Blade (1/Day)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/goblin-sneak-whereevillives.webp"
```
^statblock