# Siege Hawk

```ds-statblock
name: Siege Hawk
ancestry:
- Animal
roles:
- Mount
level: 1
ev: 28
stamina: 60
speed: 7 (flying)
size: '3'
stability: 0
free_strike: 4
might: 1
agility: 1
intuition: 0
traits:
- name: Mounted Platform
  effect: Any creature riding the hawk can make a [[Free Strike|free strike]] during or after the
    hawk’s movement.
abilities:
- name: Talons
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1
  target: Two creatures or objects
- name: Bombs Away!
  type: Action
  roll: AGL RR
  cost: 7 VP
  keywords:
  - Area
  - Magic
  - Ranged
  - Resistance
  distance: 5 cube within 10
  target: Each creature and object
- name: Dive
  type: Maneuver

```
