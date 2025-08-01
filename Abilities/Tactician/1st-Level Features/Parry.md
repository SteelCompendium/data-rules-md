---
class: tactician
feature_type: trait
file_dpath: Tactician/1st-Level Features
item_id: parry
item_index: '01'
item_name: Parry
level: 1
scc:
  - mcdm.heroes.v1:feature.trait.tactician.1st-level-feature:parry
scdc:
  - 1.1.1:7.1.4.1:01
source: mcdm.heroes.v1
type: feature/trait/tactician/1st-level-feature
---

###### Parry

*Your quick reflexes cost an enemy the precision they seek.*

| **Melee, Weapon** |           **Triggered** |
| ----------------- | ----------------------: |
| **📏 Melee 2**    | **🎯 Self or one ally** |

**Trigger:** A creature deals damage to the target.

**Effect:** You can shift 1 square. If the target is you, or if you end this shift adjacent to the target, the target takes half the damage. If the damage has any potency effect associated with it, the potency is decreased by 1.

**Spend 1 Focus:** This ability's distance becomes Melee 1 + your Reason score, and you can shift up to a number of squares equal to your Reason score instead of 1 square.
