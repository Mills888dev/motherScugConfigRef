---
title: "Walking, running and idling"
parent: "Fox settings"
nav_order: 5
---

# Walking, running and idling

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `base_speed` | `3.0` | px/tick | Top walking speed on a flat floor at max speed. |
| `acceleration` | `0.55` | px/tick per tick | How fast they can change velocity while moving. |
| `speed_floor` | `1.0` | times base_speed | Walking speed on floor tiles. |
| `speed_corridor` | `0.85` | times base_speed | Walking speed on corridor tiles. |
| `speed_climb` | `0.55` | times base_speed | Climbing speed on poles. |
| `speed_wall` | `0.6` | times base_speed | Climbing speed on wall faces. |
| `run_speed_idle` | `0.35` | times base_speed | Walking speed while wandering. |
| `run_speed_hunt` | `1.0` | times base_speed | Running speed while hunting and while carrying prey home. |
| `run_speed_flee` | `1.0` | times base_speed | Running speed while fleeing, escaping rain or returning to the den. |
| `idle_wander_chance` | `0.08` | 0-1 | Chance each tick of picking a new wandering destination. |
| `idle_stay_chance` | `0.1` | 0-1 | Chance of standing idle instead of wandering when the idle timer runs out. |
| `run_speed_stalk` | `0.3` | times base_speed | Pace while stalking distant prey. |
| `regain_footing_frames` | `10` | ticks | Time in allowed terrain before gravity switches off and footing takes hold. |
