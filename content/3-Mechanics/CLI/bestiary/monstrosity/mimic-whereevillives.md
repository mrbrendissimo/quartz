---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/ambusher
- ttrpg-cli/monster/type/monstrosity/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mimic
---
# [Mimic](3-Mechanics\CLI\bestiary\monstrosity/mimic-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles p. 37, Flee, Mortals! p. 193*  

```statblock
"name": "Mimic (WhereEvilLives)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger, Ambusher"
"alignment": "typically  Neutral"
"ac": !!int "11"
"hp": !!int "65"
"hit_dice": "10d8 + 20"
"modifier": !!int "1"
"stats":
  - !!int "17"
  - !!int "12"
  - !!int "15"
  - !!int "5"
  - !!int "12"
  - !!int "10"
"speed": "15 ft., climb 15 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+2"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_immunities": "acid; bludgeoning damage from falling"
"condition_immunities": "[prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "2"
"traits":
  - "desc": "While the mimic remains motionless, they are indistinguishable from an\
      \ ordinary object."
    "name": "False Appearance (Object Form Only)"
  - "desc": "The mimic can imitate any sounds they have heard, including voices. A\
      \ creature who hears the sounds can tell they are imitations with a successful\
      \ DC 12 Wisdom ([Insight](/3-Mechanics/CLI/skills.md#Insight)) check."
    "name": "Mimicry"
"actions":
  - "desc": "Melee Weapon Attack: +5 to hit, reach 10 ft., one target. Hit: 7\
      \ (1d8 + 3) bludgeoning damage. If the target is a Large or smaller creature,\
      \ they are [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 13)."
    "name": "Pseudopod"
  - "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
      \ + 3) piercing damage plus 3 (d6) acid damage. If the target is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by the mimic, they take an extra 3 (d6) acid damage."
    "name": "Gnashing Maw"
  - "desc": "The mimic polymorphs into a Small, Medium, or Large object or back into\
      \ their true amorphous form. Other than size, the mimic's statistics are the\
      \ same in each form. Anything they are wearing or carrying isn't transformed.\
      \ They revert to their true form if they die."
    "name": "Shapechanger"
  - "desc": "While grappling a creature, the mimic uses their Shapechanger action\
      \ to polymorph into an object that is the same size or bigger than the [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ creature (if the mimic isn't already in such a form). The creature is then\
      \ enveloped by the mimic. An enveloped creature is no longer [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
      \ but they can't breathe, are [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ and [restrained](/3-Mechanics/CLI/conditions.md#Restrained), have total cover\
      \ against attacks and other effects outside the mimic, and take 10 (3d6) acid\
      \ damage at the start of each of the mimic's turns. When the mimic moves, the\
      \ enveloped creature moves with them. The mimic can envelop one creature at\
      \ a time.\n\nAn enveloped creature can use their action to try to escape by\
      \ making a DC 13 Strength check. On a successful check, the creature is no longer\
      \ enveloped and is shunted to an unoccupied space of their choice within 5 feet\
      \ of the mimic. The creature automatically escapes if the mimic uses Shapechanger\
      \ or Panic Shift, becomes [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ or dies."
    "name": "Envelop"
"reactions":
  - "desc": "When the mimic takes damage, they release any [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ or enveloped creatures and then polymorph into a Small dense object with spikes,\
      \ such as an iron ball or helm. While in this form, the mimic's walking and\
      \ climbing speeds are doubled, they have resistance to bludgeoning, piercing,\
      \ and slashing damage from mundane attacks, they can only take the Dash, Disengage,\
      \ or Shapechanger action, and a creature who touches the mimic or hits them\
      \ with a melee attack while within 5 feet of them takes 10 (3d6) piercing damage.\
      \ This effect ends when the mimic dies or uses their Shapechanger action to\
      \ polymorph into another form."
    "name": "Panic Shift (1/Day)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/mimic-fleemortals.png"
```
^statblock