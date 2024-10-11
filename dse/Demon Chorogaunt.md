# Demon Chorogaunt

```ds-statblock
name: Demon Chorogaunt
ancestry:
- Demon
- Planar
roles:
- Boss
level: 3
ev: 36
stamina: 90
weakness: Holy 3
speed: '5'
size: 1M
stability: 2
free_strike: 4
might: 2
agility: 2
reason: 2
intuition: 2
presence: 2
traits:
- name: End Effect
  effect: At the end of their turn, the chorogaunt can take 5 damage to end one EoE
    effect affecting them. This damage can’t be reduced in any way.
- name: Lethe
  effect: While winded, the chorogaunt has an edge on attacks, and attacks have an
    edge against them.
- name: Soulsight
  effect: Each creature within 2 squares of the chorogaunt can’t be hidden from them.
abilities:
- name: Agonizing Harmony
  type: Action
  roll: 2d10 + 2
  cost: Signature
  keywords:
  - Area
  - Weapon
  distance: 5 burst
  target: Each enemy
- name: Chaotic Entrancing Harmony
  type: Maneuver
  keywords:
  - Area
  distance: 10 burst
  target: Each enemy
  effect: Each target slides 3, ignoring their stability.
- name: I Thrive on Pain
  type: Triggered Action
  roll: 3 VP
  keywords:
  - Magic
  distance: Self
  target: Self
  trigger: The chorogaunt is targeted by an attack.
  effect: Any damage from the attack is halved, and the chorogaunt gains an edge on
    all ability rolls until the end of their next turn.
- name: Frightening Tones
  type: Villain Action
  cost: 1 VP
  keywords:
  - Ranged
  distance: Ranged 10
  target: Three enemies
  effect: Each target either takes 5 psychic damage or is [[Frightened|frightened]] of the chorogaunt
    (EoT). Each target gets to choose which to do.
- name: Bully the Weak
  type: Villain Action
  cost: 2 VP
  keywords:
  - Magic
  - Ranged
  distance: Ranged 10
  target: One ally
  effect: The chorogaunt kills the target, and each other ally gains an edge on attacks
    until the end of the round. You gain VP equal to the number of heroes.
- name: Running Cacophony
  type: Villain Action
  cost: 3 VP
  keywords:
  - Magic
  distance: Self
  target: Self
  effect: The chorogaunt shifts up to their speed, makes an Agonizing Harmony attack,
    shifts up to their speed, and makes a second Agonizing Harmony attack.

```
