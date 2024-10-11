# Warg

```ds-statblock
name: Warg
ancestry:
- Animal
- Goblin
roles:
- Mount
level: 1
ev: 10
stamina: 20
speed: '7'
size: 1L
stability: 1
free_strike: 2
might: 1
agility: 1
intuition: 0
traits:
- name: Mounted Charger
  effect: If a warg used as a mount [[Charge|charges]], their rider gains an edge on melee attacks
    until the end of their turn.
- name: Shared Crafty
  effect: If the warg’s rider has the Crafty trait, the warg also has the Crafty trait.
abilities:
- name: Bite
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - [[Charge]]
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature or object
- name: Sprint
  type: Maneuver
  roll: 1 VP
  keywords:
  - —
  distance: Self
  target: Self
  effect: The warg moves up to their speed.

```
