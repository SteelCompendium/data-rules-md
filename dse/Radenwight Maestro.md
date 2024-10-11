# Radenwight Maestro

```ds-statblock
name: Radenwight Maestro
ancestry:
- Humanoid
- Radenwight
roles:
- Boss
level: 1
ev: 38
stamina: 80
speed: 5 (climb)
size: 1S
stability: 1
free_strike: 5
agility: 2
reason: 0
intuition: 0
presence: 2
traits:
- name: End Effect
  effect: At the end of their turn, the maestro can take 5 damage to end one EoE effect
    affecting them. This damage can't be reduced in any way.
abilities:
- name: Cacophony
  type: Action
  roll: 2d10 + 2
  cost: Signature
  keywords:
  - Area
  - Magic
  distance: 5 burst
  target: Each enemy
- name: Tempo Change
  type: Maneuver
  roll: PRS RR
  keywords:
  - Magic
  - Ranged
  - Resistance
  distance: Ranged 10
  target: Two enemies
- name: Ranged Ready Rodent
  type: Triggered Action
  keywords:
  - Magic
  - Ranged
  distance: Ranged 10
  target: One creature
  trigger: An ally deals damage to the target.
  effect: The maestro makes a [[Free Strike|free strike]] against the target.
- name: Overture
  type: Villain Action
  cost: 1 VP
  keywords:
  - Area
  distance: 10 burst
  target: Each ally
  effect: Each target shifts up to their speed or takes the [[Defend]] action.
- name: Solo Act
  type: Villain Action
  cost: 2 VP
  keywords:
  - Ranged
  distance: Ranged 15
  target: One creature
  effect: Until the end of their next turn, the target's stamina can't be reduced
    below 1, their speed is doubled, and their next [[Power|power]] roll is automatically a
    tier 3 result.
- name: Rondo of Rat
  type: Villain Action
  cost: 3 VP
  keywords:
  - Area
  distance: 10 burst
  target: Each dead ally
  effect: Each target stands, makes a [[Free Strike|free strike]], then collapses again. Allies of
    the targets can use Ready Rodent as a free triggered action once in conjunction
    with these [[Free Strike|free strikes]].

```
