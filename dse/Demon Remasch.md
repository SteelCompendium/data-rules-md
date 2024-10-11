# Demon Remasch

```ds-statblock
name: Demon Remasch
ancestry:
- Demon
- Planar
roles:
- Ambusher
level: 2
ev: 13
stamina: 25
weakness: Holy 3
speed: 5 ([[Teleport|teleport]])
size: 1S
stability: 0
free_strike: 3
might: 0
agility: 1
reason: 0
intuition: 0
presence: 1
traits:
- name: Lethe
  effect: While winded, the remasch has an edge on attacks, and attacks have an edge
    against them.
- name: Soulsight
  effect: Each creature within 2 squares of the remasch can’t be hidden from them.
abilities:
- name: Abyssal Strike
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature or object
- name: Grasping Shadow
  type: Maneuver
  roll: 5 VP
  keywords:
  - Magic
  - Ranged
  distance: Ranged 10
  target: Self
  effect: The remasch can [[Teleport|teleport]] 2 squares then use Abyssal Strike.

```
