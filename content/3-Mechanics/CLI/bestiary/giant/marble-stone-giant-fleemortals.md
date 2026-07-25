---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/artillery
statblock: inline
statblock-link: "#^statblock"
aliases:
- Marble Stone Giant
---
# [Marble Stone Giant](3-Mechanics\CLI\bestiary\giant/marble-stone-giant-fleemortals.md)
*Source: Flee, Mortals! p. 112*  

```statblock
"name": "Marble Stone Giant (FleeMortals)"
"size": "Huge"
"type": "giant"
"subtype": "Artillery"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "92"
"hit_dice": "8d12 + 40"
"modifier": !!int "2"
"stats":
  - !!int "21"
  - !!int "15"
  - !!int "21"
  - !!int "10"
  - !!int "14"
  - !!int "10"
"speed": "30 ft., climb 30 ft."
"saves":
  - "constitution": !!int "8"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks that aren't\
  \ adamantine"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Giant"
"cr": "6"
"traits":
  - "desc": "Being within 5 feet of an enemy doesn't impose disadvantage on the giant's\
      \ ranged attack rolls."
    "name": "Agility Rune"
  - "desc": "While motionless, the giant is indistinguishable from a statue."
    "name": "False Appearance"
  - "desc": "When a creature attacks the giant with a melee weapon that isn't adamantine\
      \ and rolls a 1 on the d20 for that attack, that weapon is destroyed if it is\
      \ mundane. If that weapon is supernatural, it loses all supernatural properties\
      \ for 1 hour."
    "name": "Stone Flesh"
"actions":
  - "desc": "The giant makes two Greatsling attacks."
    "name": "Multiattack"
  - "desc": "Ranged Weapon Attack: +8 to hit, range 60/240 feet, one target. Hit:\
      \ 15 (3d6 + 5) bludgeoning damage."
    "name": "Greatsling"
  - "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 27\
      \ (4d10 + 5) bludgeoning damage, and if the target is a creature, they must\
      \ succeed on a DC 16 Strength saving throw or be pushed 10 feet away from the\
      \ giant."
    "name": "Slam"
  - "desc": "The giant bowls a boulder in a 10-foot-wide, 30-foot-long line along\
      \ the ground. Each creature in this line must make a DC 16 Dexterity saving\
      \ throw. On a failed save, a creature takes 27 (5d10) bludgeoning damage and\
      \ falls [prone](/3-Mechanics/CLI/conditions.md#Prone). On a successful save,\
      \ the creature takes half as much damage and doesn't fall [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ Each object in this line that isn't supernatural or worn or carried by a creature\
      \ takes 27 (5d10) bludgeoning damage. At the end of its roll, the boulder crumbles,\
      \ creating a 10-foot square of difficult terrain."
    "name": "Boulder Roll (Recharge 5-6)"
"bonus_actions":
  - "desc": "The giant digs their heels into the ground, reducing their speed to 0.\
      \ While in this stance, the normal and long ranges of the giant's Greatsling\
      \ attack are doubled, and when this attack hits, each other creature within\
      \ 5 feet of the target must succeed on a DC 17 Dexterity saving throw or take\
      \ 10 (3d6) bludgeoning damage. The giant's stance lasts until they become [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
      \ [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
      \ or [restrained](/3-Mechanics/CLI/conditions.md#Restrained), or until the giant\
      \ ends it as a bonus action."
    "name": "Siege Stance"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/giant/token/marble-stone-giant-fleemortals.png"
```
^statblock