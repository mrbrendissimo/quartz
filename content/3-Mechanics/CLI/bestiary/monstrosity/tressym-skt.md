---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Tressym
---
# [Tressym](3-Mechanics\CLI\bestiary\monstrosity/tressym-skt.md)
*Source: Storm King's Thunder p. 242*  

A tressym is a mischievous winged cat as big as a house cat, with a wingspan of 3 feet.

Thought to be the results of wizardly experimentation on house cats, tressym are intelligent and have been known to form strong friendships with humanoids, particularly rangers and wizards. Tressym get along well with others of their kind, but they rarely lair or hunt together. They peacefully ignore bats, faerie dragons, and the like, but they hate stirges and evil flying monsters such as manticores. They also enjoy teasing dogs.

Tressym feed on small rodents, birds, and insects, stalking and pouncing on prey much as normal cats do, but with the added advantage of flight. Tressym don't, however, attack nestlings or despoil eggs.

Tressym mate with others of their kind, but they don't mate for life. A tressym can also mate with a normal cat, though only one out of every ten of their offspring will be a tressym; the others will be normal cats.

Tressym have good memories, particularly when it comes to danger. For example, a tressym that sees a human use a [wand of lightning bolts](/3-Mechanics/CLI/items/wand-of-lightning-bolts-xdmg.md) remembers the danger of "sticks of wood held by humans" for the rest of its life. A lucky, healthy tressym can live to be 20 years old.

With the DM's permission, a person who casts the [find familiar](/3-Mechanics/CLI/spells/find-familiar-xphb.md) spell can choose to conjure a tressym instead of a normal cat.

```statblock
"name": "Tressym (SKT)"
"size": "Tiny"
"type": "monstrosity"
"alignment": "Any alignment"
"ac": !!int "12"
"hp": !!int "5"
"hit_dice": "2d4"
"modifier": !!int "2"
"stats":
  - !!int "3"
  - !!int "15"
  - !!int "10"
  - !!int "11"
  - !!int "12"
  - !!int "12"
"speed": "40 ft., climb 30 ft., fly 40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "understands Common but can't speak"
"cr": "0"
"traits":
  - "desc": "Within 60 feet of the tressym, magical invisibility fails to conceal\
      \ anything from the tressym's sight."
    "name": "Detect Invisibility"
  - "desc": "The tressym has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "The tressym can detect whether a substance is poisonous by taste, touch,\
      \ or smell."
    "name": "Poison Sense"
  - "desc": "With the DM's permission, a person who casts the [find familiar](/3-Mechanics/CLI/spells/find-familiar-xphb.md)\
      \ spell can choose to conjure a tressym instead of a normal cat."
    "name": "Familiar"
"actions":
  - "desc": "Melee Weapon Attack: +0 to hit, reach 5 ft., one target. Hit: 1 slashing\
      \ damage."
    "name": "Claws"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/tressym-skt.webp"
```
^statblock