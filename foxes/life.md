---
title: "Daily life: roaming, dens, food, reputation"
parent: "Fox settings"
nav_order: 10
---

# Daily life: roaming, dens, food, reputation

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `flee_max_distance` | `30` | tiles | How far away they look for a spot to flee to. |
| `roam_radius_tiles` | `30` | tiles | How far away they pick spots to wander to. |
| `den_health_threshold` | `0.5` | fraction of full health | Health below which they head to there den. |
| `carry_max_mass_ratio` | `0.3` | times own total mass | Heaviest creature they can carry to dev. |
| `grasp_dominance` | `0.8` |  | How strongly they hold prey when another creature pulls on the same prey. |
| `eats_carrion` | `true` |  | Enables eating corpses. Off: even fresh kills are ignored. |
| `roam_distance_weight` | `0.35` |  | How much they favor far-away spots when wandering. |
| `rep_enabled` | `true` |  | Enables reputation like lizards. |
| `rep_personality_amount` | `0.25` |  | How much each fox's reputation toward the player differs. 0: all the same. |
| `rep_hostile_threshold` | `-0.5` | -1 to 1 | Reputation at or below which they turn hostile to the player. Needs rep_enabled. |
| `rep_friendly_threshold` | `0.5` | -1 to 1 | Reputation at or above which they stop hunting the player. Needs rep_enabled. |
