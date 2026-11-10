---
title: "Hunting: stalk, pounce, charge, bite"
parent: "Fox settings"
nav_order: 9
---

# Hunting: stalk, pounce, charge, bite

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `bite_damage` | `1.1` |  |  |
| `bite_stun_bonus` | `45` | ticks | Extra stun added to a bite. |
| `bite_radius` | `45` | px | How close prey must be to the head's center before a bite. |
| `bite_cooldown` | `60` | ticks | Wait after a bite before the next bite. |
| `pounce_enabled` | `true` |  | Enables pouncing. |
| `pounce_distance` | `170` | px | Farthest distance from the head to prey at which a hunting pounce may start. |
| `pounce_min_distance` | `40` | px | Closest distance from the head to prey at which a hunting pounce may start. |
| `pounce_cooldown` | `110` | ticks | Wait after a pounce ends before the next one can start. |
| `pounce_recovery_stun` | `18` | ticks | Recovery time after a pounce lands. |
| `pounce_chance` | `0.6` | 0-1 | Chance a hunting pounce starts once every other check passes. |
| `pounce_attack_enabled` | `true` |  | Enables pouncing at prey. |
| `pounce_gather_frames` | `22` | ticks | Wind-up before a full-power pounce launches. |
| `pounce_launch_speed` | `9.0` | px/tick | Full launch speed of a pounce, which sets how far and high pounces go. |
| `pounce_boost` | `2.0` | px/tick | Upward speed added to the whole body on each boost tick, tapering off. |
| `pounce_align_rate` | `0.25` | 0-1 | Share of the angle between body and flight direction corrected each tick. 0 disables. |
| `pounce_align_max_deg` | `7.0` | degrees |  |
| `pounce_hind_release_ticks` | `4` | ticks | How long after launch the hind legs keep reaching for the ground. |
| `charge_enabled` | `false` |  | Enables charge. |
| `charge_distance` | `260.0` | px | Farthest distance to the target at which a charge may start. |
| `charge_min_distance` | `70.0` | px | Closest distance to the target at which a charge may start. |
| `charge_chance` | `0.5` | 0-1 | Chance a charge starts once every other check passes. 1: always. |
| `charge_windup_frames` | `14` | ticks | Wind-up before a charge launches. |
| `charge_windup_pull` | `0.25` | px/tick |  |
| `charge_thrust` | `1.1` | px/tick | How hard they push forward each tick of a charge. |
| `charge_thrust_frames` | `26` | ticks | How long they keep pushing forward during a charge. |
| `charge_max_frames` | `34` | ticks | Longest a charge can last, wind-up included. |
| `charge_max_speed` | `14.0` | px/tick | Top speed during a charge. |
| `charge_recovery_stun` | `34` | ticks | Recovery time after a charge ends. |
| `charge_cooldown` | `150` | ticks |  |
| `stalk_enabled` | `true` |  |  |
| `stalk_distance` | `400.0` | px | Farthest distance to prey at which a stalk may start. |
| `stalk_break_distance` | `180.0` | px | Closer to prey than this, they stop stalking and hunt. |
| `land_safe_speed` | `12.0` | px/tick | Fastest fall they land from cleanly. |
| `land_damage_speed` | `20.0` | px/tick | Fall speed above which a bad landing also hurts them. |
| `land_damage_per_speed` | `0.06` | game damage units per px/tick | Damage per unit of fall speed above land_damage_speed. 0: none. |
| `land_soft_fac` | `1.0` | 0 to 8 | Scales both landing speeds. 1: full soft landing. 0: every landing is clumsy. |
| `pounce_route_enabled` | `true` |  | Enables pounces along a route, as shortcuts or to reach new places. |
| `pounce_route_goal_seed_radius_tiles` | `6.0` | tiles | How far out they look for launch spots toward the destination. |

## Drawing only

These change only what is drawn. Movement and behavior are not affected.

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `stalk_crouch_drop` | `5.0` | px | How low they crouch while stalking. |
