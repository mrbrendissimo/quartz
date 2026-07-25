---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/monstrosity/minion
- ttrpg-cli/monster/type/monstrosity/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mimic Mimiature
---
# [Mimic Mimiature](3-Mechanics\CLI\bestiary\monstrosity/mimic-mimiature-fleemortals.md)
*Source: Flee, Mortals! p. 194*  

```statblock
"name": "Mimic Mimiature (FleeMortals)"
"size": "Small"
"type": "monstrosity"
"subtype": "shapechanger, Minion"
"alignment": "typically  Neutral"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "8"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "5"
  - !!int "11"
  - !!int "10"
"speed": "15 ft., climb 15 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The mimiature can occupy another creature's space and vice versa, and\
      \ the mimiature can move through any opening at least 1 inch wide without squeezing."
    "name": "In Your Space"
  - "desc": "If the mimiature takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the mimiature takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 1 bludgeoning\
      \ damage. Until the end of the target's next turn, they have disadvantage on\
      \ ability checks and saving throws made to escape a grapple, and they have advantage\
      \ on ability checks made to initiate or maintain a grapple. Additionally, if\
      \ three or more mimiatures joined the attack, the target's appendages become\
      \ so sticky that until the end of the target's next turn, they can't cast spells\
      \ with somatic components, they can't drop objects, and they can't interact\
      \ with objects other the ones they are already holding."
    "name": "Sticky Swarm (Group Attack)"
  - "desc": "The mimiature polymorphs into a Tiny object or back into their true amorphous\
      \ form. If four mimiatures within 5 feet of each other use this action together,\
      \ they can join together to become one Small object. Anything a mimiature is\
      \ wearing or carrying isn't transformed. A mimiature in object form reverts\
      \ to their true form if any mimiature in the group moves, takes an action, or\
      \ dies."
    "name": "Group Shapechanger"
"source":
  - "FleeMortals"
```
^statblock