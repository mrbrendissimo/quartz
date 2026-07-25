---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/minotaur
- ttrpg-cli/monster/type/monstrosity/retainer
statblock: inline
statblock-link: "#^statblock"
aliases:
- Minotaur Devastator
---
# [Minotaur Devastator](3-Mechanics\CLI\bestiary\monstrosity/minotaur-devastator-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 107, Flee, Mortals! p. 197*  

> [!note] Medium Minotaur
> 
> The minotaur devestator originally appeared in *Flee, Mortals! The MCDM Monster Book.* In that book, the retainer is Large. However, Worjo, the minotaur devestator in Lady Emer's lair, is Medium. The stat block here reflects Worjo's size.
^medium-minotaur

```statblock
"name": "Minotaur Devastator (WhereEvilLives)"
"size": "Medium"
"type": "monstrosity"
"subtype": "minotaur, Retainer"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "light armor"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "name": "Strength"
    "desc": "+PB"
  - "name": "Dexterity"
    "desc": "+PB"
  - "name": "Constitution"
    "desc": "+PB"
  - "name": "Intelligence"
    "desc": "+PB"
  - "name": "Wisdom"
    "desc": "+PB"
  - "name": "Charisma"
    "desc": "+PB"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+3 plus PB"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+0 plus PB"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common"
"actions":
  - "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
      \ 1d10 plus PB piercing damage. Beginning at 7th level, the devastator can make\
      \ this attack twice, instead of once, when they take the Attack action on their\
      \ turn."
    "name": "Signature Attack (Goring Horns)"
  - "desc": "As an action, the devastator moves up to their speed. At the end of this\
      \ movement, they can make a signature attack. If that attack hits a Large or\
      \ smaller creature, the target is pushed up to 10 feet away from the devastator,\
      \ and the devastator and their allies have advantage on attack rolls against\
      \ the target until the end of the devastator's next turn."
    "name": "3rd Level: Furious Charge (3/Day)"
  - "desc": "As an action, the devastator makes a signature attack against a creature\
      \ within 5 feet of them. On a hit, the attack deals an extra PBd10 piercing\
      \ damage, and the target must succeed on a DC 10 plus PB Wisdom saving throw\
      \ or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened) of the devastator\
      \ until the end of the devastator's next turn."
    "name": "5th Level: Fearsome Gore (3/Day)"
  - "desc": "When a creature the devastator can see within 40 feet of them deals damage\
      \ to the devastator, the devastator can use a reaction to move up to their speed\
      \ toward the creature. If the devastator ends this movement within 5 feet of\
      \ the creature, they can make two signature attacks against the creature with\
      \ a +PB bonus to those attack and damage rolls."
    "name": "7th Level: Retaliatory Charge (1/Day)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
```
^statblock