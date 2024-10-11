# Radenwight Swiftpaw

```ds-statblock
name: Radenwight Swiftpaw
ancestry:
- Humanoid
- Radenwight
roles:
- Harrier
- Minion
level: 1
ev: 6
stamina: 10
speed: 7 (climb)
size: 1S
stability: 0
free_strike: 2
might: 0
agility: 1
reason: 1
intuition: 0
abilities:
- name: Rapier Flunge
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature or object per minion
- name: Ready Rodent
  type: Triggered Action
  keywords:
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature
  trigger: An ally deals damage to the target.
  effect: The swiftpaw makes a [[Free Strike|free strike]] against the target.

```
