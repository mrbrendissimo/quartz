---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fiend/ambusher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lightthief
---
# [Lightthief](3-Mechanics\CLI\bestiary\fiend/lightthief-fleemortals.md)
*Source: Flee, Mortals! p. 310*  

```statblock
"name": "Lightthief (FleeMortals)"
"size": "Tiny"
"type": "fiend"
"subtype": "Ambusher"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "38"
"hit_dice": "11d4 + 11"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "17"
  - !!int "12"
  - !!int "6"
  - !!int "16"
  - !!int "5"
"speed": "20 ft., fly 30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"senses": "blindsight 60 ft., passive Perception 15"
"languages": "understands Abyssal, Common, and Infernal but can't speak"
"cr": "2"
"actions":
  - "desc": "Melee Spell Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6\
      \ + 3) necrotic damage, or 13 (3d6 + 3) necrotic damage if the target can't\
      \ see the lightthief."
    "name": "Necrotic Drain"
  - "desc": "The lightthief teleports inside a light source they can see within 15\
      \ feet of them that is emitting bright or dim light. While inside the light\
      \ source, the lightthief has total cover against attacks and other effects outside\
      \ the light source. If the light source is extinguished by any means other than\
      \ the lightthief's Steal Light action, the lightthief is forced out, appears\
      \ in an unoccupied space of their choice within 5 feet of the light source,\
      \ and is [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed) until the end\
      \ of their next turn."
    "name": "Into the Light (Recharge 6)"
  - "desc": "The lightthief can cause the light they are inside to erupt in a burst\
      \ of brilliant radiance. Each creature within 15 feet of the light source must\
      \ make a DC 13 Constitution saving throw. On a failed save, a creature takes\
      \ 14 (4d6) radiant damage and loses any darkvision they have for 1 minute. On\
      \ a successful save, a creature takes half as much damage and doesn't lose their\
      \ darkvision. After this, the light source extinguishes and the lightthief appears\
      \ in an unoccupied space of their choice within 5 feet of the light source."
    "name": "Steal Light (Inside Light Source Only)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/lightthief-fleemortals.png"
```
^statblock