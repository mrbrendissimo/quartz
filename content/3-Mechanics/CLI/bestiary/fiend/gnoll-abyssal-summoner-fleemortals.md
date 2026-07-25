---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/gnoll
- ttrpg-cli/monster/type/fiend/support
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gnoll Abyssal Summoner
---
# [Gnoll Abyssal Summoner](3-Mechanics\CLI\bestiary\fiend/gnoll-abyssal-summoner-fleemortals.md)
*Source: Flee, Mortals! p. 117*  

```statblock
"name": "Gnoll Abyssal Summoner (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "gnoll, Support"
"alignment": "typically  Chaotic Evil"
"ac": !!int "14"
"ac_class": "[hide armor](/3-Mechanics/CLI/items/hide-armor-xphb.md)"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "16"
  - !!int "12"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Abyssal, Gnoll"
"cr": "6"
"actions":
  - "desc": "The summoner makes two attacks using Bite, Three-Tail Flail, Fire Blast,\
      \ or a combination of them. They can replace one attack with a use of Demonic\
      \ Howl, if available."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 6 (1d4\
      \ + 4) piercing damage plus 7 (2d6) necrotic damage, and if the target is a\
      \ creature, another creature the summoner can see within 30 feet of them magically\
      \ regains 7 (2d6) hit points. If this attack is made against a willing ally,\
      \ it automatically hits."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 11\
      \ (3d4 + 4) bludgeoning damage, and the target is pushed 5 feet away from the\
      \ summoner."
    "name": "Three-Tail Flail"
  - "desc": "Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 10\
      \ (3d6) fire damage."
    "name": "Fire Blast (Cantrip)"
  - "desc": "Until the beginning of the summoner's next turn, each ally within 30\
      \ feet of the summoner who can hear them has advantage on attack rolls."
    "name": "Demonic Howl (Recharge 5-6)"
  - "desc": "The gnoll magically turns an allied [abyssal hyena](/3-Mechanics/CLI/bestiary/fiend/abyssal-hyena-fleemortals.md)\
      \ into a [gnoll marauder](/3-Mechanics/CLI/bestiary/fiend/gnoll-marauder-fleemortals.md)\
      \ for 1 hour."
    "name": "Uplift (3/Day)"
"bonus_actions":
  - "desc": "The summoner summons 1d4 + 1 [abyssal hyena](/3-Mechanics/CLI/bestiary/fiend/abyssal-hyena-fleemortals.md)s,\
      \ who appear in unoccupied spaces within 30 feet of the summoner. The hyenas\
      \ act immediately after the summoner's turn and follow the summoner's commands."
    "name": "Summon Abyssal Hyenas (3/Day)"
"reactions":
  - "desc": "When an ally the summoner can see within 30 feet of them is reduced to\
      \ 0 hit points, the summoner moves up to half their speed and makes a Bite attack."
    "name": "Death Frenzy"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/gnoll-abyssal-summoner-fleemortals.png"
```
^statblock