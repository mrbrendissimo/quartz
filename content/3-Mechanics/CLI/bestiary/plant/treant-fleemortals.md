---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/plant/controller
statblock: inline
statblock-link: "#^statblock"
aliases:
- Treant
---
# [Treant](3-Mechanics\CLI\bestiary\plant/treant-fleemortals.md)
*Source: Flee, Mortals! p. 240*  

```statblock
"name": "Treant (FleeMortals)"
"size": "Huge"
"type": "plant"
"subtype": "Controller"
"alignment": "typically  Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "172"
"hit_dice": "15d12 + 75"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "21"
  - !!int "10"
  - !!int "19"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Nature](/3-Mechanics/CLI/skills.md#Nature)"
    "desc": "+4"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+8"
"senses": "tremorsense 60 ft., passive Perception 14"
"languages": "Common, Druidic, Sylvan"
"cr": "9"
"traits":
  - "desc": "In addition to any other spells in this stat block, the treant can cast\
      \ the following spells, using Wisdom as the spellcasting ability (spell save\
      \ DC 16):\n\nAt will: [speak with animals](/3-Mechanics/CLI/spells/speak-with-animals-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
      \ [speak with plants](/3-Mechanics/CLI/spells/speak-with-plants-xphb.md)<sup>[A](#^superscript-casting-time)</sup>\n\
      \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
      \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action\
      \ (see spell description) |\n^superscript-casting-time"
    "name": "Spellcasting (Utility)"
  - "desc": "While the treant remains motionless, they are indistinguishable from\
      \ a normal tree."
    "name": "False Appearance"
"actions":
  - "desc": "The treant makes two Thorned Tendril attacks."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit: 19\
      \ (4d6 + 5) piercing damage, and the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 15). While [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ in this way, a target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ and takes 7 (2d6) piercing damage at the start of each of their turns."
    "name": "Thorned Tendril"
  - "desc": "The treant swings the creatures they are grappling in violent circles.\
      \ Each creature [grappled](/3-Mechanics/CLI/conditions.md#Grappled) by the treant\
      \ takes 26 (4d12) bludgeoning damage, and the treant can move them into an unoccupied\
      \ space the treant can see within 15 feet of the treant.\n\nAll other creatures\
      \ within 15 feet of the treant must make a DC 17 Dexterity saving throw. On\
      \ a failed save, a creature takes 26 (4d12) bludgeoning damage per creature\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) by the treant. On a successful\
      \ save, a creature takes half as much damage."
    "name": "Swinging Tendrils (Recharge 6)"
"bonus_actions":
  - "desc": "Each creature of the treant's choice within 30 feet of them regains 17\
      \ (3d8 + 4) hit points."
    "name": "Healing Growth (1/Day)"
  - "desc": "The treant wraps one creature they have [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ in thick vines, pulling the target up to 10 feet toward them. The target can't\
      \ speak until the grapple ends."
    "name": "Reel and Wrap"
"source":
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/plant/token/treant-fleemortals.png"
```
^statblock