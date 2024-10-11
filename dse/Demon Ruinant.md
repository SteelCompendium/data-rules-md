# Demon Ruinant

```ds-statblock
name: Demon Ruinant
ancestry:
- Demon
- Planar
roles:
- Harrier
level: 1
ev: 10
stamina: 20
weakness: Holy 3
speed: '6'
size: 1M
stability: 0
free_strike: 2
might: 0
agility: 1
reason: 0
intuition: 0
presence: 1
traits:
- name: Lethe
  effect: While winded, the ruinant has an edge on attacks, and attacks have an edge
    against them.
- name: Soulsight
  effect: Each creature within 2 squares of the ruinant can’t be hidden from them.
abilities:
- name: Bloodletting Claws
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1
  target: Two creatures or objects
- name: Salt Wounds
  type: Maneuver
  roll: MGT RR
  cost: 3 VP
  keywords:
  - Magic
  - Ranged
  - Resistance
  distance: Ranged 10
  target: Three creatures without full Stamina

```
