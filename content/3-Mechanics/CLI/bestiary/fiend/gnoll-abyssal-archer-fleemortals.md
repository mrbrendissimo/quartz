---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/artillery
- ttrpg-cli/monster/type/fiend/gnoll
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gnoll Abyssal Archer
---
# [Gnoll Abyssal Archer](3-Mechanics\CLI\bestiary\fiend/gnoll-abyssal-archer-fleemortals.md)
*Source: Flee, Mortals! p. 116*  

```statblock
"name": "Gnoll Abyssal Archer (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "gnoll, Artillery"
"alignment": "typically  Chaotic Evil"
"ac": !!int "14"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "18"
"hit_dice": "4d8"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "13"
  - !!int "8"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Abyssal, Gnoll"
"cr": "1/2"
"traits":
  - "desc": "The abyssal archer knows the location of each creature who doesn't have\
      \ all their hit points within 60 feet of them."
    "name": "Bloodscent"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
      \ + 2) piercing damage."
    "name": "Bite"
  - "desc": "Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. Hit:\
      \ 6 (1d8 + 2) piercing damage, and the target's walking speed is reduced by\
      \ a cumulative 5 feet until they regain at least 1 hit point."
    "name": "Longbow"
"reactions":
  - "desc": "When an ally the abyssal archer can see within 30 feet of them is reduced\
      \ to 0 hit points, the abyssal archer moves up to half their speed and makes\
      \ a Bite attack."
    "name": "Death Frenzy"
"source":
  - "FleeMortals"
```
^statblock