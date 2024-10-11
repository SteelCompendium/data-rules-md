# Demon Muceron

```ds-statblock
name: Demon Muceron
ancestry:
- Demon
- Planar
roles:
- Brute
level: 3
ev: 18
stamina: 45
weakness: Holy 3
speed: '5'
size: 1M
stability: 0
free_strike: 2
might: 1
agility: 1
reason: 0
intuition: 0
presence: 1
traits:
- name: Lethe
  effect: While winded, the muceron has an edge on attacks, and attacks have an edge
    against them.
- name: Soulsight
  effect: Each creature within 2 squares of the muceron can’t be hidden from them.
abilities:
- name: Barbed Tongues
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 2
  target: One creature
- name: Tongue Pull
  type: Maneuver
  roll: 2 VP
  keywords:
  - Attack
  - Ranged
  - Weapon
  distance: Ranged 5
  target: Three creatures
  effect: Each target is pulled 3 squares.

```
