# Time Raider Tyrannis

```ds-statblock
name: [[Time Raider]] Tyrannis
ancestry:
- Humanoid
- [[Time Raider]]
roles:
- Boss
level: 3
ev: 54
stamina: 120
immunities:
- Psychic 7
speed: 10 ([[Fly|fly]], [[Teleport|teleport]])
size: '2'
stability: 0
free_strike: 5
traits:
- name: End Effect
  effect: At the end of their turn, the tyrannis can take 5 damage to end one EoE
    effect affecting them. This damage can’t be reduced in any way.
- name: Foresight
  effect: The tyrannis doesn’t take a bane on attacks against concealed creatures.
- name: 'Keywords**: Area'
  effect: '**Distance**: 10 burst **Target**: Each ally **Effect**: Each target can
    end one effect or condition affecting them or can move up to their speed.'
- name: 'Keywords**: Area'
  effect: '**Distance**: 5 burst **Target**: Special **Effect**: The tyrannis fires
    a sensor mine into each unoccupied square in the burst and a gravity well into
    one of their own squares. Whenever an enemy moves into a square with a sensor
    mine, the mine explodes, dealing 3 damage to the enemy.'
abilities:
- name: Gatling Blaster
  type: Action
  roll: 2d10 + 3
  cost: Signature
- name: Air Raid!
  type: Maneuver
  roll: 3 VP
- name: Precog Reflexes
  type: Triggered Action
- name: We Will Won!
  type: Villain Action
  cost: 1 VP
- name: Stick To The Plan!
  type: Villain Action
  cost: 2 VP
- name: Armageddon
  type: Villain Action
  cost: 3 VP

```
