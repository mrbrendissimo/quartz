---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/whereevillives
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/ooze/ambusher
statblock: inline
statblock-link: "#^statblock"
aliases:
- Blood-Borne Ooze
---
# [Blood-Borne Ooze](3-Mechanics\CLI\bestiary\ooze/blood-borne-ooze-whereevillives.md)
*Source: Where Evil Lives: The MCDM Book of Boss Battles, Flee, Mortals! p. 309*  

```statblock
"name": "Blood-Borne Ooze (WhereEvilLives)"
"size": "Tiny"
"type": "ooze"
"subtype": "Ambusher"
"alignment": "typically  Neutral Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "14"
"hit_dice": "4d4 + 4"
"modifier": !!int "2"
"stats":
  - !!int "8"
  - !!int "15"
  - !!int "13"
  - !!int "1"
  - !!int "10"
  - !!int "2"
"speed": "20 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [deafened](/3-Mechanics/CLI/conditions.md#Deafened), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ flanked, [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 10"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The ooze can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Amorphous"
  - "desc": "While the ooze remains motionless, they are indistinguishable from a\
      \ pool of blood."
    "name": "False Appearance"
"actions":
  - "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
      \ + 2) bludgeoning damage plus 2 (d4) necrotic damage. If the target is a creature\
      \ who isn't a Construct or an Undead, they must succeed on a DC 11 Constitution\
      \ saving throw or the ooze melds into the target's body.\n\nWhile inside a creature,\
      \ the ooze has total cover against attacks and other effects originating outside\
      \ that host.\n\nIf the host creature takes 5 damage or more on a single turn\
      \ from a source other than the ooze, the ooze must succeed on a DC 12 Constitution\
      \ saving throw at the end of that turn or exit the host, entering the nearest\
      \ unoccupied space of the ooze's choice. A cure ailment power, [protection from\
      \ poison](/3-Mechanics/CLI/spells/protection-from-poison-xphb.md) spell, or\
      \ [lesser restoration](/3-Mechanics/CLI/spells/lesser-restoration-xphb.md) spell\
      \ cast on the host also forces the ooze out. By spending 5 feet of their movement,\
      \ the ooze can voluntarily leave the host's body."
    "name": "Pseudopod"
  - "desc": "The ooze consumes their host creature's bodily fluids. The host must\
      \ make a DC 11 Constitution saving throw. On a failed save, the host takes 5\
      \ (2d4) necrotic damage and is [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ until the end of their next turn. On a successful save, the host takes half\
      \ as much damage and isn't [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)."
    "name": "Crimson Feast (Inside Host Only)"
"source":
  - "WhereEvilLives"
  - "FleeMortals"
  - "WhereEvilLives"
```
^statblock