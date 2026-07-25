---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/beast/leader
statblock: inline
statblock-link: "#^statblock"
aliases:
- Ancient Lightning Eel
---
# [Ancient Lightning Eel](3-Mechanics\CLI\bestiary\beast/ancient-lightning-eel-fleemortals.md)
*Source: Flee, Mortals! p. 40*  

```statblock
"name": "Ancient Lightning Eel (FleeMortals)"
"size": "Gargantuan"
"type": "beast"
"subtype": "Leader"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "203"
"hit_dice": "14d20 + 56"
"modifier": !!int "2"
"stats":
  - !!int "21"
  - !!int "15"
  - !!int "18"
  - !!int "7"
  - !!int "13"
  - !!int "6"
"speed": "20 ft., swim 50 ft."
"saves":
  - "strength": !!int "9"
  - "dexterity": !!int "6"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+10"
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "cold, thunder"
"damage_immunities": "lightning"
"senses": "passive Perception 19"
"languages": ""
"cr": "12"
"traits":
  - "desc": "The eel can breathe air and water. They can survive out of water for\
      \ up to 24 hours."
    "name": "Amphibious"
  - "desc": "When the eel fails a saving throw, they can succeed instead. When they\
      \ do, they can't take the Multiattack action on their next turn."
    "name": "Foudroyant Majesty (3/Day)"
  - "desc": "The eel has advantage on ability checks and saving throws made to avoid\
      \ or end the [grappled](/3-Mechanics/CLI/conditions.md#Grappled) condition on\
      \ themself."
    "name": "Slippery"
  - "desc": "Other lightning eels within 30 feet of the ancient eel deal an extra\
      \ 4 (d8) lightning damage with their weapon attacks and Electric Pulse."
    "name": "Stormsurge"
"actions":
  - "desc": "The eel makes one Bite attack and uses Electric Pulse."
    "name": "Multiattack"
  - "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12\
      \ (2d6 + 5) piercing damage plus 9 (2d8) lightning damage, and the target is\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape DC 17). While\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ and the eel can't make a Bite attack against another target."
    "name": "Bite"
  - "desc": "The eel channels energy toward a creature within 60 feet of them. The\
      \ creature must make a DC 16 Constitution saving throw, made with disadvantage\
      \ if the target is touching the eel. On a failed save, a creature takes 27 (6d8)\
      \ lightning damage and is [dazed](/3-Mechanics/CLI/conditions.md#Dazed) until\
      \ the end of their next turn. On a successful save, a creature takes half as\
      \ much damage and isn't [dazed](/3-Mechanics/CLI/conditions.md#Dazed)."
    "name": "Electric Pulse"
"bonus_actions":
  - "desc": "The eel coils around a creature within 5 feet of them. The target must\
      \ succeed on a DC 17 Dexterity saving throw or be [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ (escape DC 17)."
    "name": "Coiling Storm"
"reactions":
  - "desc": "When another lightning eel that the ancient eel can see within 30 feet\
      \ of them is reduced to 0 hit points, the ancient eel releases a crackling filament\
      \ of lightning in their direction. The target is restored to life with 10 hit\
      \ points. Each lighting eel can be restored to life only once with this reaction."
    "name": "Heart of the Storm"
"legendary_actions":
  - "desc": "The eel has three villain actions. They can take each action once during\
      \ an encounter after an enemy's turn. They can take these actions in any order\
      \ but can use only one per round."
    "name": ""
  - "desc": "Every other lightning eel within 30 feet of the ancient eel can use their\
      \ Electric Pulse action as a reaction."
    "name": "Action 1: Call to the Storm"
  - "desc": "The eel surges with lightning, moves up to their speed, then makes a\
      \ Bite attack. On a hit, the Bite attack deals an extra 18 (4d8) lightning damage.\
      \ A creature who hits the eel with a melee attack during this movement takes\
      \ 9 (2d8) lightning damage."
    "name": "Action 2: Electric Rush"
  - "desc": "The eel releases a crackling wave of electricity and uses Electric Pulse\
      \ against each enemy within 30 feet of them."
    "name": "Action 3: Fulminous Wave"
"source":
  - "FleeMortals"
```
^statblock