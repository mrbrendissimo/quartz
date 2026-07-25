---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/brute
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Human Brawler Slime Servant
---
# [Human Brawler Slime Servant](3-Mechanics\CLI\bestiary\humanoid/human-brawler-slime-servant-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 134*  

If a creature spends 1 continuous minute under the effect of the slime from an olothec's Devolving Tentacle attack, that effect ends and their flesh devolves into a translucent primordial state. The creature loses their memories and sense of self, becoming a slime servant NPC who is loyal to the olothec.

```statblock
"name": "Human Brawler Slime Servant (WhereEvilLives)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Brute"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "52"
"hit_dice": "7d8 + 21"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "14"
  - !!int "16"
  - !!int "10"
  - !!int "10"
  - !!int "12"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+3"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "2"
"traits":
  - "desc": "The brawler can breathe air and water."
    "name": "Amphibious"
  - "desc": "When the brawler makes an attack, they have advantage on the attack roll."
    "name": "Exploit Opening (3/Day)"
  - "desc": "Ithu'rath can sense anything the brawler senses, and Ithu'rath can speak\
      \ through their body."
    "name": "Servant Senses"
"actions":
  - "desc": "The brawler makes two attacks using Grab, Haymaker, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one Medium or smaller\
      \ creature. Hit: 5 (1d4 + 3) bludgeoning damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 13). Until this grapple ends, the brawler can't grab another creature."
    "name": "Grab"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
      \ + 3) bludgeoning damage, or 10 (3d4 + 3) bludgeoning damage against a [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ target."
    "name": "Haymaker"
  - "desc": "The brawler throws one Medium or smaller creature they are grappling\
      \ or object they are holding up to 30 feet horizontally. If the thrown target\
      \ is a creature, they fall [prone](/3-Mechanics/CLI/conditions.md#Prone) after\
      \ this throw. If the thrown target would enter the space of a creature or solid\
      \ object that is no more than one size smaller than it, the thrown target collides\
      \ with it and stops in the nearest unoccupied space, taking 3 (d6) bludgeoning\
      \ damage for every 10 feet it was thrown. A Large or smaller creature hit by\
      \ this thrown target must succeed on a DC 13 Dexterity saving throw or take\
      \ the same amount of damage and fall [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Throw"
"reactions":
  - "desc": "When the brawler is grappling a target and is hit by a ranged attack\
      \ made by another creature the brawler can see, the brawler gains a +2 bonus\
      \ to AC against the triggering attack. If this bonus causes the attack to miss\
      \ the brawler, it hits the [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ target instead."
    "name": "Meat Shield"
"source":
  - "WhereEvilLives"
```
^statblock