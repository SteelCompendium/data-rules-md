# Goblin Assassin

```ds-statblock
name: Goblin Assassin
ancestry:
- Goblin
- Humanoid
roles:
- Ambusher
level: 1
ev: 11
stamina: 20
speed: 6 (climb)
size: 1S
stability: 0
free_strike: 3
agility: 1
reason: 0
intuition: 0
traits:
- name: Crafty
  effect: The assassin doesn’t provoke opportunity attacks by moving.
- name: [[Hide]] While Observed
  effect: The assassin can take the [[Hide]] maneuver even while observed, though they
    still must have cover or concealment.
abilities:
- name: Sword
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature or object
- name: Shadow Chains
  type: Action
  roll: AGL RR
  cost: 3 VP
  keywords:
  - Magic
  - Ranged
  - Resistance
  distance: Ranged 10
  target: Three creatures

```
