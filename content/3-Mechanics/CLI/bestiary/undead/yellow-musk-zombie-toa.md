---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/toa
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Yellow Musk Zombie
---
# [Yellow Musk Zombie](3-Mechanics\CLI\bestiary\undead/yellow-musk-zombie-toa.md)
*Source: Tomb of Annihilation p. 237*  

A yellow musk creeper is an unholy vine whose flowers resemble an orchid's. Bright yellow with splashes of purple, these flowers expel a musk that attracts prey. A yellow musk creeper clings to walls, pillars, gravestones, door frames, or statuary in shadowy locations, remaining motionless until it strikes.

## Humanoid Hosts

A yellow musk creeper destroys the minds of humanoids, then implants bulbs in those it kills. Twenty-four hours after being implanted, a bulb sprouts a creeper vine that magically animates the host corpse, turning it into a yellow musk zombie under the young vine's control. In addition to protecting the defenseless plant, the zombie acts as fertilizer for the young creeper vine, which grows to full size in seven days. Once it is fully grown, the new yellow musk creeper becomes mobile and bursts from its zombie host, whereupon the zombie collapses into a mound of dead offal. If the zombie is destroyed before the creeper emerges, the creeper withers and dies.

## Small Yellow Musk Zombies

A Medium humanoid transformed into a yellow musk zombie uses the stat block presented in this section. A Small humanoid transformed into a yellow musk zombie becomes a Small undead with `dice:6d6+6|noform|noparens|avg|text(27)` (`6d6 + 6`) hit points, but otherwise has the same statistics.

```statblock
"name": "Yellow Musk Zombie (ToA)"
"size": "Medium"
"type": "undead"
"alignment": "Unaligned"
"ac": !!int "9"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "-1"
"stats":
  - !!int "13"
  - !!int "9"
  - !!int "12"
  - !!int "1"
  - !!int "6"
  - !!int "3"
"speed": "20 ft."
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion)"
"senses": "blindsight 30 ft., passive Perception 8"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "If damage reduces the zombie to 0 hit points, it must make a Constitution\
      \ saving throw with a DC of 5 +the damage taken, unless the damage is fire or\
      \ from a critical hit. On a success, the zombie drops to 1 hit point instead."
    "name": "Undead Fortitude"
"actions":
  - "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
      \ + 1) bludgeoning damage."
    "name": "Slam"
"source":
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/undead/token/yellow-musk-zombie-toa.webp"
```
^statblock