---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/controller
- ttrpg-cli/monster/type/undead/incorporeal
statblock: inline
statblock-link: "#^statblock"
aliases:
- Wraith
---
# [Wraith](3-Mechanics\CLI\bestiary\undead/wraith-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 248*  

```statblock
"name": "Wraith (WhereEvilLives)"
"size": "Medium"
"type": "undead"
"subtype": "incorporeal, Controller"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "14"
  - !!int "15"
  - !!int "12"
  - !!int "14"
  - !!int "17"
"speed": "0 ft., fly 60 ft. (hover)"
"damage_resistances": "acid; cold; fire; lightning; necrotic; thunder; bludgeoning,\
  \ piercing, slashing from mundane attacks"
"damage_immunities": "poison, psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [dazed](/3-Mechanics/CLI/conditions.md#Dazed),\
  \ [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained), [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "the languages they knew in life"
"cr": "5"
"traits":
  - "desc": "The wraith can move through other creatures and objects as if they were\
      \ difficult terrain. The wraith takes 5 (d10) force damage if they end their\
      \ turn inside an object. A creature takes 5 (d10) psychic damage the first time\
      \ a wraith passes through them on a turn."
    "name": "Agonizing Phasing"
  - "desc": "When the wraith dies, they collapse inward, creating a burst of painful\
      \ psychic energy. Each creature within 20 feet of the wraith must make a DC\
      \ 14 Constitution saving throw, taking 18 (4d8) psychic damage on a failed save,\
      \ or half as much damage on a successful one."
    "name": "Throes of Oblivion"
"actions":
  - "desc": "Melee Spell Attack: +6 to hit, reach 5 ft., one creature. Hit: 14\
      \ (4d6) psychic damage, and the target must succeed on a DC 14 Wisdom saving\
      \ throw or be [dazed](/3-Mechanics/CLI/conditions.md#Dazed) (save ends at end\
      \ of turn).\n\nEach time a target [dazed](/3-Mechanics/CLI/conditions.md#Dazed)\
      \ in this way fails a saving throw to end the condition, their hit point maximum\
      \ is halved. This effect is cumulative, and the reduction lasts until the target\
      \ finishes a short or long rest.\n\nIf a Humanoid dies within 1 minute of being\
      \ hit by this attack, their spirit rises as a specter under the wraith's control\
      \ in an unoccupied space nearest to where that Humanoid died."
    "name": "Agonizing Touch"
  - "desc": "Ranged Spell Attack: +6 to hit, range 60 ft., one creature. Hit:\
      \ 10 (3d6) psychic damage, and the target must succeed on a DC 14 Wisdom saving\
      \ throw or fall [prone](/3-Mechanics/CLI/conditions.md#Prone) and be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of the wraith for 1 minute (save ends at end of turn). While [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ in this way, the target can't stand up."
    "name": "Psychic Enervation"
"reactions":
  - "desc": "When a creature who the wraith can see within 30 feet of them regains\
      \ hit points, the wraith can attempt to sap the life energy restoring the creature.\
      \ The creature must succeed on a DC 14 Constitution saving throw or only regain\
      \ half the number of hit points they otherwise would regain."
    "name": "Denied Vitality"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
  - "WhereEvilLives"
  - "WhereEvilLives"
  - "WhereEvilLives"
"image": "/3-Mechanics/CLI/bestiary/undead/token/wraith-fleemortals.png"
```
^statblock