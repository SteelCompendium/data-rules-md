# Radenwight Redeye

```ds-statblock
name: Radenwight Redeye
ancestry:
- Humanoid
- Radenwight
roles:
- Artillery
- Minion
level: 1
ev: 6
stamina: 8
speed: 5 (climb)
size: 1S
stability: 0
free_strike: 2
might: 1
agility: 1
intuition: 0
presence: 0
abilities:
- name: Eyes-On-Me Shot
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Ranged
  - Weapon
  distance: Ranged 10
  target: One creature or object per minion
- name: Ready Rodent
  type: Triggered Action
  keywords:
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature
  trigger: An ally deals damage to the target.
  effect: The redeye makes a [[Free Strike|free strike]] against the target.

```
