---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Crag Cat
---
# [Crag Cat](3-Mechanics\CLI\bestiary\monstrosity/crag-cat-skt.md)
*Source: Storm King's Thunder p. 240*  

The creature referred to in Northlander lore as the Hunter of Men is a sure-footed predator that can be found anywhere except deep forest, preferring ledges and cliffs in the mountains. Its cry resembles a human scream of terror. It often elicits such sounds from its victims, for it prefers human flesh to all other prey.

Crag cats blend in with natural surroundings. During the winter, their fur turns white to blend in with the snow. At other times of the year, their fur is gray, enabling them to hide among the rocks more easily.

The crag cat knows its territory and often attacks when its prey is asleep, exhausted, or otherwise weakened. Although crag cats are typically solitary, they can be found in family groups of two parents and `dice:1d4|noform|noparens|avg` (`d4`) Small noncombatant cubs in the spring, or in hungry packs in severe winter weather.

```statblock
"name": "Crag Cat (SKT)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "34"
"hit_dice": "4d10 + 12"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "17"
  - !!int "16"
  - !!int "4"
  - !!int "14"
  - !!int "8"
"speed": "40 ft., climb 30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The cat cannot be targeted or detected by any divination magic or perceived\
      \ through magical scrying sensors."
    "name": "Nondetection"
  - "desc": "If the cat moves at least 20 feet straight toward a creature then hits\
      \ it with a claw attack on the same turn, that target must succeed on a DC13\
      \ Strength saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone).\
      \ If the target is [prone](/3-Mechanics/CLI/conditions.md#Prone), the cat can\
      \ make one bite attack against it as a bonus action."
    "name": "Pounce"
  - "desc": "The cat has advantage on saving throws against any spell that targets\
      \ only the cat (not an area). If the cat's saving throw succeeds and the spell\
      \ is of 7th level or lower, the spell has no effect on the cat and instead targets\
      \ the caster."
    "name": "Spell Turning"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
      \ + 3) piercing damage."
    "name": "Bite"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
      \ + 3) slashing damage."
    "name": "Claw"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/crag-cat-skt.webp"
```
^statblock