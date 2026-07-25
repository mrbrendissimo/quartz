---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/leader
statblock: inline
statblock-link: "#^statblock"
aliases:
- Zenith Aastrika
---
# [Zenith Aastrika](3-Mechanics\CLI\bestiary\giant/zenith-aastrika-fleemortals.md)
*Source: Flee, Mortals! p. 107*  

```statblock
"name": "Zenith Aastrika (FleeMortals)"
"size": "Huge"
"type": "giant"
"subtype": "Leader"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "225"
"hit_dice": "18d12 + 108"
"modifier": !!int "3"
"stats":
  - !!int "25"
  - !!int "16"
  - !!int "23"
  - !!int "10"
  - !!int "23"
  - !!int "14"
"speed": "50 ft."
"saves":
  - "strength": !!int "11"
  - "dexterity": !!int "7"
  - "constitution": !!int "10"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+11"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+6"
"damage_immunities": "fire"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "passive Perception 20"
"languages": "Giant, Primordial"
"cr": "12"
"traits":
  - "desc": "When Aastrika fails a saving throw, she can choose to succeed instead.\
      \ When she does so, she can't use Sweltering Heat until the end of her next\
      \ turn."
    "name": "Battle Tranquility (3/Day)"
  - "desc": "The first time a creature other than a fire giant touches Aastrika or\
      \ hits her with a melee attack on a turn, that creature takes 7 (2d6) fire damage."
    "name": "Molten Flesh"
"actions":
  - "desc": "Aastrika takes the Disengage action and makes up to three attacks using\
      \ Unarmed Strike, Hurl Flame, or both."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 21\
      \ (4d6 + 7) bludgeoning damage plus 7 (2d6) fire damage. If the target is a\
      \ creature, they are outlined in red light until the start of Aastrika's next\
      \ turn, and for the duration, attack rolls against them have advantage."
    "name": "Unarmed Strike"
  - "desc": "Ranged Spell Attack: +10 to hit, range 180 ft., one target. Hit:\
      \ 20 (4d6 + 6) fire damage."
    "name": "Hurl Flame"
  - "desc": "Aastrika causes a 20-foot-radius, 60-foot-high cylinder of lava to erupt\
      \ from the ground at a point she can see within 120 feet of her. Each creature\
      \ in that area must make a DC 18 Dexterity saving throw, taking 38 (11d6) fire\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Lava Pillar (Recharge 5-6)"
"bonus_actions":
  - "desc": "Aastrika's inner flame pulses harshly. Each creature within 20 feet of\
      \ her who doesn't have resistance or immunity to fire damage must succeed on\
      \ a DC 18 Constitution saving throw or gain a level of [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)."
    "name": "Sweltering Heat"
"reactions":
  - "desc": "When another fire giant Aastrika can see within 60 feet of her misses\
      \ with a weapon attack, Aastrika causes flame to trail from the attacker. The\
      \ attacker rolls damage for the attack as if they had hit, and the target takes\
      \ half that amount as fire damage instead of taking the full amount of normal\
      \ damage."
    "name": "Power of Flame"
"legendary_actions":
  - "desc": "Aastrika has three villain actions. She can take each action once during\
      \ an encounter after an enemy's turn. She can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Aastrika and up to three creatures she can see can move up to their speed\
      \ without provoking opportunity attacks and make one melee attack each."
    "name": "Action 1: Forward!"
  - "desc": "Aastrika disappears in a flash of light and teleports, reappearing in\
      \ an unoccupied space she can see within 30 feet of her. At the same time, five\
      \ [fire giant trooper](/3-Mechanics/CLI/bestiary/giant/fire-giant-trooper-fleemortals.md)s\
      \ appear in unoccupied spaces within 30 feet of the space she teleported from.\
      \ The troopers act immediately after this villain action is taken and on the\
      \ same initiative count in subsequent rounds."
    "name": "Action 2: The Manifold Self"
  - "desc": "Aastrika and each willing fire giant within 60 feet of her unleashes\
      \ a burst of heat. Each creature within 10 feet of Aastrika or one of these\
      \ fire giants must make a DC 18 Dexterity saving throw, taking 55 (10d10) fire\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Action 3: This. Ends. Now"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/giant/token/zenith-aastrika-fleemortals.png"
```
^statblock