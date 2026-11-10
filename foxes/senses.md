---
title: "Senses"
parent: "Fox settings"
nav_order: 3
---

# Senses

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `visual_radius` | `900` | px | How far they see(20PX is ~1 tile). |
| `water_vision` | `0.3` | 0-1 | Sight strength when the creature or target is in deep water. 1: no loss. |
| `through_surface_vision` | `0.5` | 0-1 | How well sight is across the water surface. |
| `movement_based_vision` | `0.4` | 0-1 | How much a target's movement changes how easily the target is seen. 0: no effect. |
| `prey_sure_to_get_distance` | `3.0` | tiles | Prey within this distance get the most hunting interest. |
| `prey_sure_to_lose_distance` | `110.0` | tiles | Prey this far away get the least hunting interest. |
| `hearing_skill` | `1.0` |  | How far noises are heard. 0: deaf. 1: normal. |
| `prey_give_up_unreachable` | `900` | ticks | How long prey can stay unreachable before interest fades to nothing. -1: never. |
| `prey_give_up_ghost_generation` | `90` |  | How old a guess of the prey's position may get before they give up. |
| `hunt_persist_frames` | `400` | ticks | How long a hunt continues after the prey stops being top priority. 0 disables. |
| `vision_perfect_angle` | `0.8` | -1 to 1 | How wide the clear forward view is. 1: straight ahead only. |
| `vision_peripheral_angle` | `-0.25` | -1 to 1 | Edge of the field of view. -1: vision reaches straight behind(scroll down on here there's some visuals on how this works as its nearly the same as lizards https://rainworld.miraheze.org/wiki/Lizards). |
| `sense_radius` | `500` | px | How far the all-round near sense reaches. |
| `scent_enabled` | `true` |  |  |
| `scent_radius_tiles` | `75` | tiles | How far away creatures can be smelled. |
| `hunt_forget_frames` | `900` | ticks | How long prey may stay unseen or unreachable without progress before the hunt ends. |
| `prey_persistence_bias` | `2.0` |  | How strongly the current prey is favored over other prey. |
