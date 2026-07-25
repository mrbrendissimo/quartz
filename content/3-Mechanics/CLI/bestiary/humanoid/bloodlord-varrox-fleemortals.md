---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/hobgoblin
- ttrpg-cli/monster/type/humanoid/leader
statblock: inline
statblock-link: "#^statblock"
aliases:
- Bloodlord Varrox
---
# [Bloodlord Varrox](3-Mechanics\CLI\bestiary\humanoid/bloodlord-varrox-fleemortals.md)
*Source: Flee, Mortals! p. 157*  

```statblock
"name": "Bloodlord Varrox (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "hobgoblin, Leader"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate](/3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "119"
"hit_dice": "14d8 + 56"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "11"
  - !!int "18"
  - !!int "11"
  - !!int "14"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "5"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+3"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+5"
"damage_resistances": "fire, necrotic"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Goblin, Infernal"
"cr": "8"
"traits":
  - "desc": "When Varrox dies, his corpse unleashes a spray of burning orange ichor.\
      \ Each creature within 5 feet of him takes 5 fire damage."
    "name": "Infernal Ichor"
  - "desc": "When Varrox fails a saving throw, he can call on Hell to succeed instead.\
      \ When he does, each ally within 60 feet of him takes 5 necrotic damage."
    "name": "Infernal Sacrifice (3/Day)"
"actions":
  - "desc": "Varrox makes three attacks using Soulsword, Death Skulls, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
      \ (2d6 + 4) slashing damage plus 10 (3d6) necrotic damage. If the target is\
      \ a creature, they can't regain hit points until the start of Varrox's next\
      \ turn."
    "name": "Soulsword"
  - "desc": "Ranged Weapon Attack: +7 to hit, range 80/320 ft., one target. Hit:\
      \ 8 (1d8 + 4) piercing damage plus 9 (2d8) fire damage, and Varrox can teleport\
      \ to an unoccupied space he can see within 5 feet of the target."
    "name": "Death Skulls"
"bonus_actions":
  - "desc": "Varrox barks orders at one ally within 60 feet of him who can hear him.\
      \ That ally can use their reaction to move up to their speed and make a weapon\
      \ attack."
    "name": "Advance and Attack"
"reactions":
  - "desc": "When a non-minion hobgoblin who Varrox can see within 60 feet of him\
      \ takes damage, Varrox magically summons three hobgoblin recruits who appear\
      \ in unoccupied spaces nearest to the damaged hobgoblin."
    "name": "An Army from Blood"
"legendary_actions":
  - "desc": "Varrox has three villain actions. He can take each action once during\
      \ an encounter after an enemy's turn. He can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Varrox chooses up to six non-minion allies within 60 feet of him who\
      \ can see or hear him. Varrox and each chosen creature gain 10 temporary hit\
      \ points and can move up to their speed."
    "name": "Action 1: Uncanny Leadership"
  - "desc": "Varrox and each ally within 60 feet of him can teleport up to 60 feet\
      \ to an unoccupied space they can see."
    "name": "Action 2: Hellish Transport"
  - "desc": "Each enemy within 20 feet of Varrox must make a DC 15 Constitution saving\
      \ throw, taking 11 (2d10) fire damage plus 11 (2d10) necrotic damage on a failed\
      \ save, or half as much damage on a successful one. After the explosion, a shroud\
      \ of black flame covers Varrox for 1 minute. For the duration, each time another\
      \ creature hits Varrox with an attack while within 5 feet of him or touches\
      \ him, that creature takes 5 (d10) fire damage plus 5 (d10) necrotic damage."
    "name": "Action 3: I Am Fire and Death"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/bloodlord-varrox-whereevillives.png"
```
^statblock