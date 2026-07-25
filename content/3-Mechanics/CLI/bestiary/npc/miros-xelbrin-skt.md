---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/skt
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/damaran-human
statblock: inline
statblock-link: "#^statblock"
aliases:
- Miros Xelbrin
---
# [Miros Xelbrin](3-Mechanics\CLI\bestiary\npc/miros-xelbrin-skt.md)
*Source: Storm King's Thunder p. 251*  

Innkeeper Miros is a retired carnival attraction, dubbed "the Yeti" because of his barrel-shaped body and the thick, white hair covering his arms, chest, back, and head. When Goldenfields suffers, so does his business, so he takes strides to protect the compound.

Ideal:"As does the Emerald Enclave, I believe that civilization and the wilderness need to learn to coexist."

Bond:"Make fun of me all you like, but don't speak ill of my inn or my employees!"

Flaw:"When something upsets me, I have a tendency to fly into a rage."

```statblock
"name": "Miros Xelbrin (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "Damaran human"
"alignment": "Neutral Good"
"ac": !!int "10"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "11"
  - !!int "12"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "Common"
"traits":
  - "desc": "Innkeeper Miros is a retired carnival attraction, dubbed \"the Yeti\"\
      \ because of his barrel-shaped body and the thick, white hair covering his arms,\
      \ chest, back, and head. When Goldenfields suffers, so does his business, so\
      \ he takes strides to protect the compound.\n\nIdeal: \"As does the Emerald\
      \ Enclave, I believe that civilization and the wilderness need to learn to coexist.\"\
      \n\nBond: \"Make fun of me all you like, but don't speak ill of my inn or my\
      \ employees.\"\n\nFlaw: \"When something upsets me, I have a tendency to fly\
      \ into a rage.\""
    "name": "Roleplaying Information"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. Hit: 5\
      \ (1d4 + 3) bludgeoning damage, and the target [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 13) and takes 5 (1d4 + 3) bludgeoning damage at the start of each\
      \ of Miros's turns until the grapple ends. Miros cannot make attacks while grappling\
      \ a creature."
    "name": "Bear Hug"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
      \ + 1) bludgeoning damage"
    "name": "Club"
  - "desc": "Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. Hit:\
      \ 5 (d10) piercing damage. Miros carries ten crossbow bolts."
    "name": "Heavy Crossbow"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/miros-xelbrin-skt.webp"
```
^statblock