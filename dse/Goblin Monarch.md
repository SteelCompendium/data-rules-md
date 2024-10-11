# Goblin Monarch

```ds-statblock
name: Goblin Monarch
ancestry:
- Goblin
- Humanoid
roles:
- Boss
level: 1
ev: 24
stamina: 50
speed: 6 (climb)
size: 1S
stability: 1
free_strike: 3
might: 2
agility: 1
intuition: 0
traits:
- name: End Effect
  effect: At the end of their turn, the monarch can take 5 damage to end one EoE effect
    affecting them. This damage can’t be reduced in any way.
- name: Crafty
  effect: The monarch doesn’t provoke opportunity attacks by moving.
abilities:
- name: Handaxe
  type: Action
  roll: 2d10 + 2
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Ranged
  - Weapon
  distance: Reach 1 or Ranged 5
  target: Two creatures or objects
- name: Get in Here
  type: Maneuver
  roll: 1 VP
  keywords:
  - Ranged
  distance: Ranged 20
  target: Special
  effect: Two [[Goblin Runner|goblin runners]] appear in unoccupied spaces.
- name: Meat Shield
  type: Triggered Action
  keywords:
  - Melee
  distance: Reach 1
  target: One ally
  trigger: A creature targets the monarch with an attack.
  effect: The ally becomes the target of the triggering attack instead.
- name: What Are You Waiting For?
  type: Villain Action
  cost: 1 VP
  keywords:
  - Area
  distance: 10 burst
  target: Each ally
  effect: Each target can move up to their speed or make a [[Free Strike|free strike]].
- name: Focus Fire
  type: Villain Action
  cost: 2 VP
  keywords:
  - Ranged
  distance: Ranged 10
  target: One enemy
  effect: Each ally within 10 squares of the enemy can move up to their speed toward
    the enemy.
- name: Kill!
  type: Villain Action
  cost: 3 VP
  keywords:
  - Area
  distance: 10 burst
  target: Each ally
  effect: Each target can make a [[Free Strike|free strike]] that deals an extra 1 damage.

```
