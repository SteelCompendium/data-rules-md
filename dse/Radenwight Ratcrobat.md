# Radenwight Ratcrobat

```ds-statblock
name: Radenwight Ratcrobat
ancestry:
- Humanoid
- Radenwight
roles:
- Harrier
level: 1
ev: 13
stamina: 30
speed: 7 (climb)
size: 1S
stability: 0
free_strike: 5
agility: 1
reason: 0
intuition: 0
presence: 1
traits:
- name: Gymratstics
  effect: The ratcrobat gains an edge on attacks against larger creatures.
abilities:
- name: En Garde!
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1
  target: Two creatures or objects
- name: Over Here, Thanks
  type: Maneuver
  keywords:
  - Melee
  distance: Reach 1
  target: One enemy
  effect: Slide 1; the ratcrobat can then shift into the square the target left.
- name: Ready Rodent
  type: Triggered Action
  keywords:
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature
  trigger: An ally deals damage to the target.
  effect: The ratcrobat makes a [[Free Strike|free strike]] against the target.

```
