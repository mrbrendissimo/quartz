---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/unknown
- ttrpg-cli/monster/type/beast/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Wildcat Companion
---
# [Wildcat Companion](3-Mechanics\CLI\bestiary\beast/wildcat-companion-fleemortals.md)
*Source: Flee, Mortals! p. 47*  

```statblock
"name": "Wildcat Companion (FleeMortals)"
"size": "Unknown"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "12 plus PB (natural armor)"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "14"
  - !!int "6"
  - !!int "14"
  - !!int "8"
"speed": "60 ft."
"saves":
  - "name": "Strength"
    "desc": "+3 plus PB"
  - "name": "Dexterity"
    "desc": "+2 plus PB"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+2 plus PB"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+2 plus PB"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": ""
"traits":
  - "desc": "The wildcat has advantage on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth))\
      \ and Wisdom ([Survival](/3-Mechanics/CLI/skills.md#Survival)) checks made in\
      \ their native terrain (as determined by you and the GM)."
    "name": "Familiar Territory"
  - "desc": "When the wildcat hits a creature with an opportunity attack, the creature\
      \ is also [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 10\
      \ plus PB)."
    "name": "Predator's Grab (Recharges after a Short or Long Rest)"
  - "desc": "When the wildcat moves on their turn in combat, they can triple their\
      \ speed until the end of their turn."
    "name": "Sprint (Recharges after a Short or Long Rest)"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB piercing damage (Bite) or slashing damage (Claw)."
    "name": "Signature Attack (Bite or Claw)"
  - "desc": "The wildcat makes a signature Bite attack, dealing an extra PB bludgeoning\
      \ damage on a hit, or an extra 2 × PB bludgeoning damage to a target they are\
      \ grappling."
    "name": "1st Level: Crushing Jaws (2 Ferocity)"
  - "desc": "The wildcat moves up to their speed and makes a signature attack against\
      \ one target, dealing an extra PB damage on a hit. If the target is Large or\
      \ smaller, they are [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape\
      \ DC 10 plus PB), and the wildcat can't attack another creature until the grapple\
      \ ends."
    "name": "3rd Level: Pounce (5 Ferocity)"
  - "desc": "The wildcat makes three signature Claw attacks against the same target.\
      \ The target must succeed on a DC 10 plus PB Charisma saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the wildcat for 1 minute (save ends at end of turn)."
    "name": "5th Level: Shredding Claws (8 Ferocity)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/beast/token/wildcat-companion-fleemortals.png"
```
^statblock