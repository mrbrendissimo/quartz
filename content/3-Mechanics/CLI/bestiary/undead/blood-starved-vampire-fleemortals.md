---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Blood-Starved Vampire
---
# [Blood-Starved Vampire](3-Mechanics\CLI\bestiary\undead/blood-starved-vampire-fleemortals.md)
*Source: Flee, Mortals! p. 269*  

```statblock
"name": "Blood-Starved Vampire (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "Minion"
"alignment": "typically  Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "16"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "15"
  - !!int "14"
  - !!int "18"
"speed": "30 ft., climb 30 ft."
"senses": "blindsight 30 ft., darkvision 90 ft., passive Perception 12"
"languages": "the languages they knew in life"
"cr": "9"
"traits":
  - "desc": "If the vampire takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the vampire takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "The vampire has disadvantage on saving throws against effects that deal\
      \ radiant damage."
    "name": "Radiant Weakening"
"actions":
  - "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 2 piercing\
      \ damage plus 3 necrotic damage. If two or more vampires joined the attack,\
      \ the target's hit point maximum is reduced by a number equal to the necrotic\
      \ damage dealt. The reduction lasts until the target finishes a long rest or\
      \ is targeted by a cure ailment power, a [lesser restoration](/3-Mechanics/CLI/spells/lesser-restoration-xphb.md)\
      \ spell, or a similar supernatural effect. The target dies if this attack reduces\
      \ their hit point maximum to 0."
    "name": "Feeding Frenzy (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock