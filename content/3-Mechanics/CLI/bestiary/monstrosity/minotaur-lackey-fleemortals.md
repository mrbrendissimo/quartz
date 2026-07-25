---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Minotaur Lackey
---
# [Minotaur Lackey](3-Mechanics\CLI\bestiary\monstrosity/minotaur-lackey-fleemortals.md)
*Source: Flee, Mortals! p. 197*  

```statblock
"name": "Minotaur Lackey (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Minion"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "12"
"hp": !!int "10"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "14"
  - !!int "15"
  - !!int "10"
  - !!int "13"
  - !!int "8"
"speed": "40 ft."
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "If the lackey moves at least 20 feet straight toward an enemy and then\
      \ ends their movement within 5 feet of the enemy, the enemy takes 1 piercing\
      \ damage."
    "name": "Goring Run"
  - "desc": "If the lackey takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the lackey takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 3 piercing\
      \ damage. If this attack was made by more than one lackey, the target must succeed\
      \ on a Strength saving throw or be moved 5 feet horizontally for each minion\
      \ who joined the attack. The DC for this saving throw equals 10 plus the number\
      \ of lackeys who joined the attack."
    "name": "Goring Horns (Group Attack)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/minotaur-lackey-fleemortals.png"
```
^statblock