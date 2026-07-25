---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/solo
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ankheg
---
# [Ankheg](3-Mechanics\CLI\bestiary\monstrosity/ankheg-fleemortals.md)
*Source: Flee, Mortals! p. 315*  

```statblock
"name": "Ankheg (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Solo"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "68"
"hit_dice": "8d10 + 24"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "16"
  - !!int "3"
  - !!int "12"
  - !!int "5"
"speed": "40 ft., burrow 20 ft."
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+6"
"damage_resistances": "acid"
"condition_immunities": "flanked"
"senses": "darkvision 60 ft., tremorsense 30 ft., passive Perception 11"
"languages": ""
"cr": "2"
"traits":
  - "desc": "When the ankheg fails a saving throw, they can succeed instead, and they\
      \ can't use bonus actions until the end of their next turn."
    "name": "Disoriented Resistance (2/Day)"
  - "desc": "Difficult terrain composed of earth and stone doesn't cost the ankheg\
      \ extra movement."
    "name": "Earth Walk"
  - "desc": "When a [prone](/3-Mechanics/CLI/conditions.md#Prone) creature within\
      \ 5 feet of the ankheg attacks the ahkheg, the attack is made with advantage\
      \ instead of disadvantage."
    "name": "Soft Underbelly"
  - "desc": "While burrowing, the ankheg leaves a 10-foot-diameter tunnel in their\
      \ wake. Each section of tunnel collapses 1 minute after the ahkheg leaves that\
      \ space."
    "name": "Unstable Tunneler"
"actions":
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
      \ + 4) slashing damage plus 2 (d4) acid damage. If the target is Large or smaller,\
      \ they are [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 14).\
      \ Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ and the ankheg can't make a Bite attack against another target."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13\
      \ (2d8 + 4) slashing damage."
    "name": "Claw"
  - "desc": "The ankheg spits acid in a 30-foot long, 5-foot-wide line. Each creature\
      \ in that area must make a DC 13 Dexterity saving throw. On a failed save, a\
      \ creature takes 7 (2d6) acid damage and is bathed in acid. On a successful\
      \ save, a creature takes half as much damage and suffers no other effect.\n\n\
      A creature who is bathed in acid takes 3 (d6) acid damage at the start of each\
      \ of their turns for 1 minute (save ends at end of turn). A creature can use\
      \ their action to wipe the acid off themself or another creature within their\
      \ reach, ending the effect early."
    "name": "Acid Spit (Recharge 6)"
"bonus_actions":
  - "desc": "While burrowing within 10 feet of the surface, the ankheg erupts (without\
      \ spending movement) into a 10-foot square on the ground directly above them.\
      \ This area becomes difficult terrain, and each creature on the ground in this\
      \ area must make a DC 14 Dexterity saving throw. On a failed save, a creature\
      \ is pushed 5 feet to an unoccupied space of the ankheg's choice and is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ by rubble. A creature can use their action to free themself or another creature\
      \ within their reach. On a successful save, a creature is moved 5 feet to an\
      \ unoccupied space of the creature's choice and is not [restrained](/3-Mechanics/CLI/conditions.md#Restrained)."
    "name": "Earth Eruption"
"reactions":
  - "desc": "When a creature attacks the ankheg, the ankheg can move up to half their\
      \ speed without provoking opportunity attacks."
    "name": "Skitter"
"legendary_actions":
  - "desc": "The ankheg has three villain actions. They can take each action once\
      \ during an encounter after an enemy's turn. The ankheg can take these actions\
      \ in any order but can use only one per round."
    "name": ""
  - "desc": "The ankheg stands on their hind legs in an impressive and terrifying\
      \ display of dominance. Each enemy within 30 feet of the ankheg who can see\
      \ them must make a DC 13 Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the ankheg for 1 minute (save ends at end of turn)."
    "name": "Action 1: Big Bug!"
  - "desc": "If the ankheg is [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
      \ the condition ends for them, and they burrow up to twice their speed without\
      \ provoking opportunity attacks. If the ankheg is grappling a Large or smaller\
      \ creature during this movement, the ankheg's speed is not halved."
    "name": "Action 2: Quick Burrow"
  - "desc": "Acid sprays from the ankheg's wounds onto each creature within 15 feet\
      \ of them. Each target must make a DC 13 Dexterity saving throw, taking 7 (2d6)\
      \ acid damage on a failed save, or half as much damage on a successful one."
    "name": "Action 3: Acid Bath"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/ankheg-fleemortals.png"
```
^statblock