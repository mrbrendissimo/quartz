---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/hobgoblin
- ttrpg-cli/monster/type/humanoid/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hobgoblin Brandbearer
---
# [Hobgoblin Brandbearer](3-Mechanics\CLI\bestiary\humanoid/hobgoblin-brandbearer-fleemortals.md)
*Source: Flee, Mortals! p. 148*  

```statblock
"name": "Hobgoblin Brandbearer (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "hobgoblin, Minion"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "12"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "11"
  - !!int "15"
"speed": "30 ft."
"damage_immunities": "fire"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Goblin, Infernal"
"cr": "5"
"traits":
  - "desc": "When a creature within 5 feet of the brandbearer reduces the brandbearer\
      \ to 0 hit points, the brandbearer's corpse unleashes a spray of burning orange\
      \ ichor. The creature who reduced the brandbearer to 0 hit points takes 1 fire\
      \ damage."
    "name": "Infernal Ichor"
  - "desc": "If the brandbearer takes damage from an attack or as the result of a\
      \ failed saving throw, their hit points are reduced to 0. If the brandbearer\
      \ takes damage from another effect, they die if the damage equals or exceeds\
      \ their hit point maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "Whenever an enemy takes fire damage from a non-minion creature, the enemy\
      \ takes an extra 1 fire damage for each brandbearer within 5 feet of them."
    "name": "Too Hot to Handle"
"actions":
  - "desc": "Melee Spell Attack: +5 to hit, reach 5 ft., one target. Hit: 4 fire\
      \ damage. If three or more brandbearers joined the attack, the target has disadvantage\
      \ on saving throws against powers, spells, and other supernatural effects that\
      \ deal fire damage until the start of the brandbearer's next turn."
    "name": "Searing Grasp (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock