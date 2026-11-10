---
title: "Look: body, head, tail, colour"
parent: "Fox settings"
nav_order: 18
---

# Look: body, head, tail, colour

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `body_mesh_rad_fac` | `1.15` |  | Width of the mesh body. |
| `body_profile_neck` | `0.8` |  | Mesh body width at the neck. |
| `body_profile_chest` | `1.3` |  | Mesh body width at the chest. |
| `body_profile_waist` | `0.72` |  | Mesh body width at the waist. |
| `body_profile_haunch` | `1.0` |  | Mesh body width at the but. |
| `body_ride_height` | `9.8` | px | How high the drawn body sits above the physics body. Also sets leg length. |
| `body_ride_corridor_fac` | `0.4` | 0-1 | How much of body_ride_height is kept in pipes and tunnels. 1: no sinking. |
| `head_size` | `1.0` |  | Head size. Not visible on Toby. |
| `head_sprite_scale` | `1.0` |  | Extra scale of the head art on top of head_size. |
| `head_pitch_max` | `32.0` | degrees | How far the head can tilt up or down. |
| `toby_draw` | `1` |  | How the fox is drawn. 1: parts rig. 3: whole-body frames, as on Toby. |
| `parts_prefix` | `"FoxTofu_"` |  | Name prefix of the parts art in the atlas. |
| `parts_mask` | `false` |  | On: white art tinted by the color settings. Off: the art's own colors. |
| `parts_scale_fac` | `1.0` |  |  |
| `tail_length_fac` | `1.0` |  | Tail length. Not visible on Toby. |
| `tail_thickness_fac` | `1.0` |  | Tail thickness. |
| `tail_length_vs_body` | `1.0` | times body oval length | Tail length on the parts rig. |
| `cosmetics` | list (3 entries) |  | Cosmetic layers and their settings. Layers: Ears, Snout, BrushTail, Spines. |
| `color_body` | `"2B2B2B"` | hex RRGGBB | Body color, where the art is tinted. |
| `color_tail` | `"979797"` | hex RRGGBB | Tail tip color. Also their color in shortcut pipes and on the dev-tools map. |
| `color_tail_root` | `"565656"` | hex RRGGBB | Tail color at the root, fading to color_tail at the tip. |
| `color_head` | `"979797"` | hex RRGGBB | Head color. Also the color of Potato's small hop-smoke puffs. |
| `color_legs` | `"4A4A4A"` | hex RRGGBB | Upper leg color. Needs parts_mask. |
| `color_leg_lower` | `"545454"` | hex RRGGBB | Lower leg color. Also the color of Potato's big hop-smoke puffs. |
| `color_paws` | `"5E5E5E"` | hex RRGGBB | Paw color. Needs parts_mask. |
| `color_eye` | `"1A1A1A"` | hex RRGGBB | Eye color, where the eye is tinted. |

## Fallback rig

Used only when `parts_rig` is `false` or a part sprite is missing from the atlas.

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `body_front_cap` | `4.0` | px | Half-width of the front of the mesh body, where the neck joins. |
| `head_look_fac` | `0.55` | 0-1 | How far the head turns toward what they look at. 0: stays along the neck. |
| `head_muzzle_length` | `10.0` | px times head_size | Muzzle length on the mesh head. |
| `head_muzzle_width` | `0.62` | fraction of skull radius | Muzzle width at the skull on the mesh head. |
| `head_muzzle_tip` | `0.24` | fraction of skull radius | Muzzle width at the tip on the mesh head. |
| `eye_thickness` | `1.6` | px times head_size | Eye thickness on the mesh head. |
