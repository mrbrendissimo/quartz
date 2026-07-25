---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/19
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental/brute
- ttrpg-cli/monster/type/elemental/earth
- ttrpg-cli/monster/type/elemental/fire
- ttrpg-cli/monster/type/elemental/water
statblock: inline
statblock-link: "#^statblock"
aliases:
- Force of Blood
---
# [Force of Blood](3-Mechanics\CLI\bestiary\elemental/force-of-blood-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 94*  

```statblock
"name": "Force of Blood (WhereEvilLives)"
"size": "Large"
"type": "elemental"
"subtype": "earth, fire, water, Brute"
"alignment": "Any alignment"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "230"
"hit_dice": "20d10 + 120"
"modifier": !!int "5"
"stats":
  - !!int "24"
  - !!int "20"
  - !!int "22"
  - !!int "19"
  - !!int "18"
  - !!int "20"
"speed": "50 ft."
"saves":
  - "constitution": !!int "12"
  - "wisdom": !!int "10"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+11"
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+10"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+11"
"damage_resistances": "fire, necrotic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Common, Dwarvish, Elvish, Giant, Primordial"
"cr": "19"
"traits":
  - "desc": "The force of blood can see any creature within 120 feet of them who isn't\
      \ a Construct or an Undead. This sight ignores effects that obscure sight."
    "name": "Visceral Sight"
"actions":
  - "desc": "The force of blood makes three Scarlet Longspear attacks. They can replace\
      \ one attack with a Rend from Within attack."
    "name": "Multiattack"
  - "desc": "Melee  or Ranged Weapon Attack: +13 to hit, reach 15 ft. or range 30/60\
      \ ft., one target. Hit: 18 (2d10 + 7) piercing damage. If the target is a\
      \ creature, the force of blood regains 5 hit points."
    "name": "Scarlet Longspear"
  - "desc": "Melee Spell Attack: +12 to hit, reach 5 ft., one creature. Hit: 13\
      \ (2d6 + 6) slashing damage plus 26 (4d12) necrotic damage, and the target spends\
      \ 1 Hit Die with no effect and can't take reactions until the start of their\
      \ next turn. Miss: 13 (2d12) necrotic damage."
    "name": "Rend from Within"
"bonus_actions":
  - "desc": "The force of blood imbues the power of blood in themself or another Elemental\
      \ they can see within 30 feet of them, granting one of the following effects\
      \ of that Elemental's choice:\n\n- Boiling Blood. The Elemental boils the\
      \ blood of a creature within 5 feet of them who isn't a Construct or an Undead.\
      \ The target must make a DC 19 Constitution saving throw. On a failed save,\
      \ the target must choose to either take 27 (5d10) fire damage or make an attack\
      \ with a weapon that has a damage die of d4 or greater against a creature of\
      \ the Elemental's choice. If the attack hits, it deals an extra 11 (2d10) fire\
      \ damage.  \n- Essence Thief. The Elemental steals the essence of two creatures\
      \ the Elemental can see within 30 feet of them. Each target must make a DC 19\
      \ Constitution saving throw, taking 19 (3d12) necrotic damage on a failed save,\
      \ or half as much damage on a successful one. The Elemental can then teleport\
      \ to an unoccupied space they can see within 5 feet of one of the targets.  "
    "name": "Convocation of Blood"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/force-of-blood-fleemortals.png"
```
^statblock