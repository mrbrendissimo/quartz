---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/hobgoblin
- ttrpg-cli/monster/type/humanoid/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hobgoblin Death Captain
---
# [Hobgoblin Death Captain](3-Mechanics\CLI\bestiary\humanoid/hobgoblin-death-captain-fleemortals.md)
*Source: Flee, Mortals! p. 148*  

```statblock
"name": "Hobgoblin Death Captain (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "hobgoblin, Support"
"alignment": "Any alignment"
"ac": !!int "20"
"ac_class": "[plate](/3-Mechanics/CLI/items/plate-armor-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "17"
  - !!int "15"
  - !!int "12"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "constitution": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+5"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
"damage_resistances": "fire"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Common, Goblin, Infernal"
"cr": "6"
"traits":
  - "desc": "The captain and each ally within 60 feet of them who can hear them have\
      \ advantage on initiative rolls and can't be surprised, provided the captain\
      \ isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)."
    "name": "Battle Ready"
  - "desc": "When the captain dies, their corpse unleashes a spray of burning orange\
      \ ichor. Each creature within 5 feet of the captain takes 5 fire damage."
    "name": "Infernal Ichor"
"actions":
  - "desc": "The captain makes two Blightblade or two Eye Fire attacks. They can replace\
      \ one attack with a use of On My Mark."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
      \ + 4) slashing damage plus 7 (2d6) necrotic damage."
    "name": "Blightblade"
  - "desc": "Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 14\
      \ (4d6) fire damage."
    "name": "Eye Fire"
  - "desc": "The captain commands an ally within 60 feet of them who can hear them\
      \ to attack. That ally can make a weapon attack (no action required), dealing\
      \ an extra 3 (d6) necrotic damage on a hit."
    "name": "On My Mark"
"bonus_actions":
  - "desc": "The captain and each ally within 30 feet of them who can see them can\
      \ move up to their speed without provoking opportunity attacks."
    "name": "Lead the Charge (1/Day)"
"reactions":
  - "desc": "When an ally the captain can see within 30 feet of them takes damage,\
      \ the captain magically turns that ally [invisible](/3-Mechanics/CLI/conditions.md#Invisible).\
      \ The ally remains [invisible](/3-Mechanics/CLI/conditions.md#Invisible) until\
      \ the end of their next turn or until they attack, deal damage, or force another\
      \ creature to make a saving throw."
    "name": "Hidden Gift (3/Day)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/hobgoblin-death-captain-whereevillives.png"
```
^statblock