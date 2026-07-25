---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/soldier
statblock: inline
statblock-link: "#^statblock"
aliases:
- Hellhound
---
# [Hellhound](3-Mechanics\CLI\bestiary\fiend/hellhound-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 144*  

```statblock
"name": "Hellhound (WhereEvilLives)"
"size": "Medium"
"type": "fiend"
"subtype": "Soldier"
"alignment": "typically  Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor; 18 with Hardened by Flame"
"hp": !!int "76"
"hit_dice": "9d8 + 36"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "17"
  - !!int "19"
  - !!int "11"
  - !!int "8"
  - !!int "10"
"speed": "50 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+3"
"damage_immunities": "fire"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "understands Common and Infernal but can't speak"
"cr": "3"
"traits":
  - "desc": "When the hound is subjected to fire damage, they take no damage. Instead,\
      \ their skin darkens and hardens, and their AC increases to 18 until the end\
      \ of their next turn."
    "name": "Hardened by Flame"
  - "desc": "The hound has advantage on Wisdom ([Survival](/3-Mechanics/CLI/skills.md#Survival))\
      \ checks to track other creatures and on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth))\
      \ checks to hide from creatures who are unaware of their presence."
    "name": "Stealthy Hunter"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
      \ + 3) piercing damage plus 4 (d8) fire damage."
    "name": "Hellish Bite"
  - "desc": "The hound exhales flame in a 15-foot cone. Each creature in that area\
      \ must make a DC 14 Dexterity saving throw, taking 14 (3d6 + 4) fire damage\
      \ on a failed save, or half as much damage on a successful one. A creature who\
      \ isn't a hellhound who fails the saving throw is lit on fire for 1 minute (save\
      \ ends at end of turn), or until the target or another creature who can reach\
      \ them uses an action to extinguish the flames. A creature who is on fire at\
      \ the start of their turn takes 7 (2d6) fire damage. If a creature who is already\
      \ on fire is set on fire again on a subsequent turn, the damage isn't cumulative,\
      \ but the duration of the fire resets to 1 minute."
    "name": "Hellfire Breath (Recharge 5-6)"
"reactions":
  - "desc": "When an enemy within 5 feet of the hound hits the hound with a melee\
      \ attack, the hound can make a Hellish Bite attack against that enemy. If the\
      \ hound's attack hits, the enemy is also [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 12), and if the triggering attack was a weapon attack, the weapon\
      \ used in the triggering attack can't be used to make any more attacks while\
      \ the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled). The grapple\
      \ ends if the hound attacks a different target with Hellish Bite."
    "name": "Tug of War"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/hellhound-fleemortals.png"
```
^statblock