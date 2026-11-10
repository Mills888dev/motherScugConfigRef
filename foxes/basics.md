---
title: "Creature basics"
parent: "Fox settings"
nav_order: 1
---

# Creature basics

| Setting | Default | Unit | What it does |
|---|---|---|---|
| `body_size` | `1.6` |  | How big the body to other creatures. Physical and drawn size are unchanged. |
| `meat_points` | `6` | Food Pips | Food value of the corpse. |
| `dangerous_to_player` | `0.45` | 0-1 | How dangerous the game rates this creature to the player. 0: never a threat(IIRC this is music related). |
| `scaryness` | `1.2` |  | How strongly other creatures turn to look at this creature. |
| `toughness` | `1.0` |  | General damage resistance. Each hit's damage is divided by twice this value. |
| `stun_toughness` | `0.9` |  | stun resistance. Stun from each hit is divided by this. |
| `off_screen_speed` | `0.3` |  | Travel speed while the room is not loaded. |
| `grasps` | `1` |  | How many things can be held at once. 0: nothing can be picked up. |
| `can_swim` | `true` |  | Allows pathing through water. |
| `tiles` | object (6 entries) |  | Path cost of each terrain type and whether the pathfinder will consider it navigate-able. |
| `connections` | object (16 entries) |  | Path cost of each kind of move and whether paths may plan that move. |
| `weight_threat` | `1.0` | I would recommend keeping this above the two other weights. | How strongly threats count when choosing between fleeing, hunting and escaping rain. |
| `weight_prey` | `0.6` | I would recommend keeping this bellow the two other weights. | How strongly hunting counts against fleeing and escaping rain. Rises with hunger. |
| `weight_rain` | `0.9` | I would recommend keeping this between the two other weights(You might be able to put this above weight_threat but I've never tested and it may cause weird behavior). | How strongly the coming rain counts against fleeing and hunting. |
| `icon_color` | `"B4B0BC"` | hex RRGGBB | Tint of the arena and sandbox creature icon. |
