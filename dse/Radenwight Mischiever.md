# Radenwight Mischiever

```ds-statblock
name: Radenwight Mischiever
ancestry:
- Humanoid
- Radenwight
roles:
- Ambusher
- Minion
level: 1
ev: 7
stamina: 10
speed: 7 (climb)
size: 1S
stability: 0
free_strike: 2
agility: 1
reason: 0
intuition: 1
presence: 0
abilities:
- name: Dagger Dance
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1 or Ranged 5
  target: One creature per minion
- name: Ready Rodent
  type: Triggered Action
  keywords:
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature
  trigger: An ally deals damage to the target.
  effect: The mischiever makes a [[Free Strike|free strike]] against the target.

```
