---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
- ttrpg-cli/monster/type/fiend/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Devil Notary
---
# [Devil Notary](3-Mechanics\CLI\bestiary\fiend/devil-notary-fleemortals.md)
*Source: Flee, Mortals! p. 69*  

```statblock
"name": "Devil Notary (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "devil, Minion"
"alignment": "typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "[chain shirt](/3-Mechanics/CLI/items/chain-shirt-xphb.md)"
"hp": !!int "13"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "15"
  - !!int "14"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"damage_immunities": "fire"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Common, Infernal"
"cr": "6"
"traits":
  - "desc": "At the start of the notary's turn, they can grant an infernal blessing\
      \ to a non-minion ally they can see within 60 feet of them (no action required).\
      \ The next time that ally makes an attack roll or saving throw before the start\
      \ of the notary's next turn, the ally can add a +1 bonus to the roll. This bonus\
      \ increases by 1 (maximum bonus of +5) for each notary who grants an infernal\
      \ blessing to the creature."
    "name": "Importunity"
  - "desc": "If the notary takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the notary takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "If a creature the notary can hear within 60 feet of them speaks the notary's\
      \ true name aloud, the notary loses their damage immunities and Importunity\
      \ trait for 24 hours."
    "name": "True Name"
"actions":
  - "desc": "Melee  or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 30 ft.,\
      \ one target. Hit: 4 fire damage."
    "name": "Brimstone (Group Attack)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/devil-notary-whereevillives.png"
```
^statblock