---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/dragon/companion
statblock: inline
statblock-link: "#^statblock"
aliases:
- Drangolin Companion
---
# [Drangolin Companion](3-Mechanics\CLI\bestiary\dragon/drangolin-companion-fleemortals.md)
*Source: Flee, Mortals! p. 179*  

```statblock
"name": "Drangolin Companion (FleeMortals)"
"size": "Large"
"type": "dragon"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "15 plus PB (natural armor)"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "13"
  - !!int "14"
  - !!int "4"
  - !!int "10"
  - !!int "8"
"speed": "30 ft., burrow 30 ft."
"saves":
  - "name": "Strength"
    "desc": "+3 plus PB"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+0 plus PB"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+0 plus PB"
"damage_resistances": "fire"
"senses": "tremorsense 60 ft., passive Perception 0"
"languages": ""
"traits":
  - "desc": "The drangolin can burrow through solid rock at half their burrow speed\
      \ and leaves behind a 3-foot-diameter tunnel when they burrow. Tiny and Small\
      \ creatures can move through this tunnel normally, and Medium and Large creatures\
      \ can squeeze through it. This tunnel collapses after 10 minutes."
    "name": "Tunneler"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d6 plus PB slashing damage."
    "name": "Signature Attack (Claws)"
  - "desc": "The drangolin breathes fire at their foe. This attack uses the statistics\
      \ for their signature attack, except the fire is a ranged weapon with a normal\
      \ range of 30 feet and a long range of 60 feet. On a hit, the attack deals an\
      \ extra PB damage, and all the damage dealt by the attack is fire damage instead\
      \ of piercing damage."
    "name": "1st Level: Spit Breath (2 Ferocity)"
  - "desc": "The drangolin moves up to their walking speed in a straight line without\
      \ provoking opportunity attacks. The drangolin can end this movement in a space\
      \ that contains another creature. If they do, that creature takes 2 × PB bludgeoning\
      \ damage for every 10 feet the drangolin traveled, and they must make a DC 10\
      \ plus PB Strength saving throw. On a failed save, the creature is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ On a successful save, the creature is pushed 5 feet out of the drangolin's\
      \ space into an unoccupied space of the creature's choice."
    "name": "3rd Level: Roll Out (5 Ferocity)"
  - "desc": "The drangolin makes two signature attacks against the same target, then\
      \ breathes fire on them. The target must make a DC 10 plus PB Dexterity saving\
      \ throw, taking PBd6 fire damage on a failed save, or half as much damage on\
      \ a successful one."
    "name": "5th Level: Rend and Roast (8 Ferocity)"
"reactions":
  - "desc": "When an enemy the drangolin can see moves within 5 feet of the drangolin's\
      \ caregiver, the drangolin sprays the enemy with ash. If the drangolin is within\
      \ 30 feet of their caregiver, the target must succeed on a DC 10 plus PB Dexterity\
      \ saving throw or be [blinded](/3-Mechanics/CLI/conditions.md#Blinded) until\
      \ the start of the drangolin's next turn."
    "name": "Ash Shot (Recharges after a Long Rest)"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/dragon/token/drangolin-companion-fleemortals.png"
```
^statblock