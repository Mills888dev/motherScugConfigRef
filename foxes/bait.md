---
title: "Mushroom: bait and camouflage"
parent: "Fox settings"
nav_order: 14
---

# Mushroom: bait and camouflage

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `camo_enabled` | `false` |  | Enables camouflage. |
| `camo_visibility_bonus` | `0.8` | 0-1 | How much harder they are to see when fully hidden. 1: invisible. |
| `camo_blend_max` | `0.85` | 0-1 | How far their colors blend into the camouflage color when fully hidden. |
| `bait_item_types` | `Spear`<br>`DangleFruit`<br>`ScavengerBomb`<br>`DataPearl`<br>`FlareBomb`<br>`PuffBall`<br>`BubbleGrass`<br>`EggBugEgg`<br>`FirecrackerPlant`<br>`FlyLure`<br>`JellyFish`<br>`Lantern`<br>`Mushroom`<br>`SlimeMold`<br>`VultureMask`<br>`WaterNut` |  | Items they can use as bait, comma-separated and case-sensitive. |
| `bait_wait_max_ticks` | `2400` | ticks | Longest they wait in ambush before giving up. 0: no limit. |
| `bait_cooldown_ticks` | `400` | ticks | Wait after a bait setup ends before they look for bait again. |
| `bait_holds_against_hunt` | `false` |  | On: they keep setting bait while hunting. Off: hunting stops the setup. |
| `bait_wait_holds_against_hunt` | `false` |  | On: they keep waiting when prey shows up. Off: seeing prey ends the ambush. |
| `bait_enabled` | `false` |  |  |
