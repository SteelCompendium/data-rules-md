# Radenwight Piper

```ds-statblock
name: Radenwight Piper
ancestry:
- Humanoid
- Radenwight
roles:
- Support
level: 1
ev: 13
stamina: 30
speed: 5 (climb)
size: 1S
stability: 0
free_strike: 2
might: 0
agility: 0
reason: 0
intuition: 1
presence: 1
abilities:
- name: Piercing Trill
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Magic
  - Melee
  - Ranged
  distance: Reach 1 or Ranged 10
  target: One creature or object
- name: Vivace Vivace!
  type: Maneuver
  roll: 3 VP
  keywords:
  - Area
  - Magic
  distance: 5 burst
  target: Each ally
  effect: Each target who has used their Ready Rodent ability since their last turn
    regains the use of their triggered action.
- name: Ready Rodent
  type: Triggered Action
  keywords:
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature
  trigger: An ally deals damage to the target.
  effect: The piper makes a [[Free Strike|free strike]] against the target.

```
