---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant/brute
statblock: inline
statblock-link: "#^statblock"
aliases:
- Troll
---
# [Troll](3-Mechanics\CLI\bestiary\giant/troll-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 242*  

```statblock
"name": "Troll (WhereEvilLives)"
"size": "Large"
"type": "giant"
"subtype": "Brute"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "94"
"hit_dice": "9d10 + 45"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "20"
  - !!int "7"
  - !!int "9"
  - !!int "7"
"speed": "40 ft."
"saves":
  - "constitution": !!int "8"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Giant"
"cr": "5"
"traits":
  - "desc": "When the troll is reduced to 0 hit points by any damage other than acid\
      \ or fire damage, they don't die or fall [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious),\
      \ and can continue moving and taking actions as usual. The troll only dies if\
      \ they end their turn with 0 hit points, if acid or fire damage reduces them\
      \ to 0 hit points, or if they take acid or fire damage while they have 0 hit\
      \ points."
    "name": "Relentless Hunger"
  - "desc": "For 1 hour after sleep or another period of unconsciousness, the troll's\
      \ speed is halved and they can't use Multiattack."
    "name": "Sluggish"
"actions":
  - "desc": "The troll makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 14\
      \ (3d6 + 4) piercing damage. If the target is not a Construct, an Elemental,\
      \ or a Plant, the troll regains hit points equal to the damage dealt. If this\
      \ attack reduces the target to 0 hit points, the troll regains twice as many\
      \ hit points as they otherwise would with this attack."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 7\
      \ (1d6 + 4) slashing damage."
    "name": "Claw"
  - "desc": "The troll moves up to their speed in a straight line, smashing through\
      \ mundane obstacles in their path. The troll can enter the spaces of Large or\
      \ smaller creatures during this movement, forcing those creatures to make a\
      \ DC 15 Strength saving throw. On a failed save, a creature takes 14 (4d6) bludgeoning\
      \ damage and falls [prone](/3-Mechanics/CLI/conditions.md#Prone). On a successful\
      \ save, a creature takes half as much damage and doesn't fall [prone](/3-Mechanics/CLI/conditions.md#Prone).\n\
      \nDuring this move, mundane objects that aren't worn or carried by a creature\
      \ take 14 (4d6) damage when the troll enters their space. If the troll moves\
      \ into the space of a Large or larger object and this damage doesn't destroy\
      \ it, the troll's movement stops and they are [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ until the end of their next turn."
    "name": "Crash Through"
"reactions":
  - "desc": "When the troll is reduced to 0 hit points and doesn't die, they can make\
      \ a Bite attack against a creature within 5 feet of them."
    "name": "Spiteful Retort"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
  - "WhereEvilLives"
"image": "/3-Mechanics/CLI/bestiary/giant/token/troll-whereevillives.png"
```
^statblock