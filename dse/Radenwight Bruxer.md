# Radenwight Bruxer

```ds-statblock
name: Radenwight Bruxer
ancestry:
- Humanoid
- Radenwight
roles:
- Brute
level: 1
ev: 16
stamina: 40
speed: 5 (climb)
size: 1M
stability: 2
free_strike: 5
might: 1
agility: 1
intuition: 0
presence: 0
abilities:
- name: Lockjaw
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature or object
- name: Flurry of Bites
  type: Action
  roll: 2d10 + 1
  cost: 3 VP
  keywords:
  - Area
  - Weapon
  distance: 1 burst
  target: Each enemy
- name: Ready Rodent
  type: Triggered Action
  keywords:
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature
  trigger: An ally deals damage to the target.
  effect: The bruxer makes a [[Free Strike|free strike]] against the target.

```
