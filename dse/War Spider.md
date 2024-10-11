# War Spider

```ds-statblock
name: War Spider
ancestry:
- Animal
- Goblin
roles:
- Mount
level: 1
ev: 28
stamina: 60
speed: 7 (climb)
size: '3'
stability: 2
free_strike: 4
might: 2
agility: 1
intuition: 0
traits:
- name: Ride Launcher
  effect: An ally who leaps off the back of the spider can [[Jump|jump]] up to 6 squares without
    a test, and takes no damage if they fall during the [[Jump|jump]]. After the [[Jump|jump]], the
    first melee attack an ally makes on the same turn gains an edge.
- name: Wide Back
  effect: Two of the spider’s size 1 allies can occupy the same space while riding
    the spider.
abilities:
- name: Bite
  type: Action
  roll: 2d10 + 2
  cost: Signature
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1
  target: One creature or object
- name: Leg Blade
  type: Action
  roll: 2d10 + 2
  keywords:
  - Attack
  - Melee
  - Weapon
  distance: Reach 1
  target: Two creatures or objects
- name: Trample
  type: Action
  roll: 5 VP
  keywords:
  - —
  distance: Self
  target: Self
  effect: The spider shifts up to their speed and makes a Leg Blade attack against
    each creature who comes within their reach during the move. The spider makes one
    [[Power|power]] roll against all targets.
- name: Web
  type: Maneuver
  roll: AGL RR
  cost: 2 VP
  keywords:
  - Area
  - Resistance
  distance: 3 cube within 1
  target: Each creature

```
