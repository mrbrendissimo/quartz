---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/minion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Minotaur Lackey Slime Servant
---
# [Minotaur Lackey Slime Servant](3-Mechanics\CLI\bestiary\monstrosity/minotaur-lackey-slime-servant-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 136*  

If a creature spends 1 continuous minute under the effect of the slime from an olothec's Devolving Tentacle attack, that effect ends and their flesh devolves into a translucent primordial state. The creature loses their memories and sense of self, becoming a slime servant NPC who is loyal to the olothec.

```statblock
"name": "Minotaur Lackey Slime Servant (WhereEvilLives)"
"size": "Medium"
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
"speed": "40 ft., swim 40 ft."
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "The lackey can breathe air and water."
    "name": "Amphibious"
  - "desc": "If the lackey moves at least 20 feet straight toward an enemy and then\
      \ ends their movement within 5 feet of the enemy, the enemy takes 1 piercing\
      \ damage."
    "name": "Goring Run"
  - "desc": "If the lackey takes damage from an attack or as the result of a failed\
      \ saving throw, their hit points are reduced to 0. If the lackey takes damage\
      \ from another effect, they die if the damage equals or exceeds their hit point\
      \ maximum; otherwise they take no damage."
    "name": "Minion"
  - "desc": "Ithu'rath can sense anything the lackey senses, and Ithu'rath can speak\
      \ through their body."
    "name": "Servant Senses"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 3 piercing\
      \ damage. If this attack was made by more than one lackey, the target must succeed\
      \ on a Strength saving throw or be moved 5 feet horizontally for each minion\
      \ who joined the attack. The DC for this saving throw equals 10 plus the number\
      \ of lackeys who joined the attack."
    "name": "Goring Horns (Group Attack)"
"source":
  - "WhereEvilLives"
```
^statblock