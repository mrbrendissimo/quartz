---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Human Apprentice Mage
---
# [Human Apprentice Mage](3-Mechanics\CLI\bestiary\humanoid/human-apprentice-mage-fleemortals.md)
*Source: Flee, Mortals! p. 159*  

```statblock
"name": "Human Apprentice Mage (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Minion"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "13"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "14"
  - !!int "10"
  - !!int "14"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+5"
"senses": "passive Perception 10"
"languages": "Common plus any two languages"
"cr": "6"
"traits":
  - "desc": "A non-minion creature serves as the mage's patron in exchange for the\
      \ mage's protective magic. At the start of the patron's turn, the patron gains\
      \ temporary hit points equal to twice the number of apprentice mages within\
      \ 60 feet of them who chose them as a patron and can see them."
    "name": "Empower Patron"
  - "desc": "When the mage makes or joins an attack that's made with advantage, the\
      \ attack deals an extra 1 damage per mage who made or joined the attack."
    "name": "Exploit Weakness"
  - "desc": "If the mage takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the mage takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Ranged Spell Attack: +5 to hit, range 120 ft., one creature. Hit:\
      \ 2 lightning damage, and if this attack was made by more than one mage, each\
      \ mage who joined the attack picks one creature within 30 feet of the original\
      \ target. Each creature picked takes 2 lightning damage for each mage who targeted\
      \ them; the mage's Exploit Weakness trait does not increase this damage."
    "name": "Lightning Strike (Group Attack)"
  - "desc": "Melee Spell Attack: +5 to hit, reach 5 ft., one target. Hit: 4 thunder\
      \ damage, and the target can't make opportunity attacks until the start of their\
      \ next turn."
    "name": "Thunder Crack (Group Attack)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/human-apprentice-mage-whereevillives.png"
```
^statblock