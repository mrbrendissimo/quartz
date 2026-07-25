---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/gnoll
- ttrpg-cli/monster/type/fiend/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gnoll Mage-Gorger
---
# [Gnoll Mage-Gorger](3-Mechanics\CLI\bestiary\fiend/gnoll-mage-gorger-fleemortals.md)
*Source: Flee, Mortals! p. 119*  

```statblock
"name": "Gnoll Mage-Gorger (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "gnoll, Minion"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "11"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "7"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Abyssal, Gnoll"
"cr": "4"
"traits":
  - "desc": "When an enemy the mage-gorger can see within 30 feet of them regains\
      \ hit points, the mage-gorger chooses one non-minion ally they can see within\
      \ 30 feet of them. That ally regains 2 hit points."
    "name": "Life Eater"
  - "desc": "If the mage-gorger takes damage from an attack or as the result of a\
      \ failed saving throw, their hit points are reduced to 0. If the mage-gorger\
      \ takes damage from another effect, they die if the damage equals or exceeds\
      \ their hit point maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 2 slashing\
      \ damage plus 2 acid, cold, fire, or lightning damage (mage-gorger's choice),\
      \ and until the start of the mage-gorger's next turn, the target has disadvantage\
      \ on Constitution saving throws made to maintain [concentration](/3-Mechanics/CLI/conditions.md#Concentration),\
      \ including any Constitution saving throw triggered by this attack. Only one\
      \ damage type is chosen for this attack regardless of how many mage-gorgers\
      \ joined it."
    "name": "Wizard Ripper (Group Attack)"
"source":
  - "FleeMortals"
```
^statblock