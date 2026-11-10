---
title: "Look: legs and gait"
parent: "Fox settings"
nav_order: 19
---

# Look: legs and gait

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `limb_length_fac` | `0.55` |  | How far a foot can reach, which sets stride size. |
| `step_arc_lift` | `2.5` | px | How high a foot lifts during a step. |
| `limb_speed` | `4.0` | px/tick | How fast the feet move. |

## Drawing only

These change only what is drawn. Movement and behavior are not affected.

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `limb_upper_fac` | `0.5` | 0-1 | How much of the leg is upper leg. 0.5: even. |

## Fallback rig

Used only when `parts_rig` is `false` or a part sprite is missing from the atlas.

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `limb_thickness` | `3.0` | px | Leg width at the shoulder. |
| `limb_paw_length` | `3.5` | px | Paw length on mesh legs. |
