# Human Brawler

```ds-statblock
name: [[Human]] Brawler
ancestry:
- [[Human]]
- Humanoid
roles:
- Brute
level: 1
ev: 16
stamina: 40
immunities:
- Magic 2
- Psionic 2
speed: '5'
size: 1M
stability: 0
free_strike: 4
might: 1
agility: 0
reason: 0
intuition: 0
presence: 0
traits:
- name: Shoot the Hostage
  effect: The brawler takes half damage from attacks if they have an enemy [[Grabbed|grabbed]].
    They then apply the remaining damage to the [[Grabbed|grabbed]] enemy.
abilities:
- name: Haymaker
  type: Action
  roll: 2d10 + 1
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature or object
- name: Throw
  type: Maneuver
  roll: 1 VP
  keywords:
  - Melee
  distance: Reach 1
  target: One creature [[Grabbed|grabbed]] by the brawler
  effect: The brawler pushes the creature they have [[Grabbed|grabbed]] 5 squares. This breaks
    the [[Grab|grab]].

```
