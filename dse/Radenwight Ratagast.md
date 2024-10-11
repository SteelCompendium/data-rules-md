# Radenwight Ratagast

```ds-statblock
name: Radenwight Ratagast
ancestry:
- Humanoid
- Radenwight
roles:
- Defender
- Minion
level: 1
ev: 7
stamina: 12
speed: 6 (climb)
size: 1S
stability: 0
free_strike: 2
agility: 1
reason: 0
intuition: 0
presence: 1
abilities:
- name: Stinky Glissando
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Magic
  - Melee
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
  effect: The ratagast makes a [[Free Strike|free strike]] against the target.

```
