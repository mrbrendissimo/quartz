---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Boog
---
# [Boog](3-Mechanics\CLI\bestiary\npc/boog-fleemortals.md)
*Source: Flee, Mortals! p. 357*  

```statblock
"name": "Boog (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Brute"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "16"
  - !!int "6"
  - !!int "10"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "5"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "If Boog sees another Abomination reduced to 0 hit points, Boog rampages\
      \ for 1 minute. While rampaging, Boog's melee attacks deal an extra 2 damage."
    "name": "Boog Rampage"
  - "desc": "If Boog moves at least 10 feet straight toward a Medium or smaller creature\
      \ and then hits them with a Gore attack on the same turn, the target is impaled\
      \ on Boog's horn and is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 15). While [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ in this way, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ and takes 3 (d6) piercing damage at the start of each of their turns, and\
      \ Boog can't make a Gore attack against another target."
    "name": "Boog Charge"
"actions":
  - "desc": "Boog makes two Slam attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 10\
      \ (1d10 + 5) bludgeoning damage or 12 (1d10 + 7) if rampaging."
    "name": "Slam"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d6\
      \ + 5) piercing damage or 10 (1d6 + 7) if rampaging."
    "name": "Gore"
  - "desc": "Boog throws a 3-inch-radius magic ball at a point they can see within\
      \ 60 feet of them. If that point is 30 feet or less from Boog, the ball grows\
      \ to a 5-foot radius. If that point is more than 30 feet from Boog, the ball\
      \ grows to a 10-foot radius. Each creature in the ball's area when it reaches\
      \ that point must succeed on a DC 15 Dexterity saving throw or take 14 (4d6)\
      \ bludgeoning damage. After the ball reaches that point, it shrinks back to\
      \ its 3-inch radius and teleports into the hand Boog used to throw it."
    "name": "Boog's Ball"
"source":
  - "FleeMortals"
```
^statblock