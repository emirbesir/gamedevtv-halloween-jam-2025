<div align="center">

# The Last Jack

An atmospheric 3D platformer where you manage a dying flame to survive a haunted world.

![Last Commit](https://img.shields.io/github/last-commit/emirbesir/the-last-jack?style=flat&logo=git&logoColor=white&color=0080ff)
![Top Language](https://img.shields.io/github/languages/top/emirbesir/the-last-jack?style=flat&color=0080ff)
![Unity](https://img.shields.io/badge/Unity-FFFFFF.svg?style=flat&logo=Unity&logoColor=black)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

_Result: **#10 in Mechanics out of 286 entries** — Gamedev.tv Halloween Jam 2025 (Solo)_

_Made and tested with **Unity 6000.2.6f1**_

</div>

## Gameplay

You control a pumpkin-headed character navigating a Halloween-themed world. Your flame depletes over time — it lights your path and keeps you alive. Ghost enemies react to your flame's intensity; their attacks damage it directly. Replenish at candles and crouch to hide from ghosts as you push toward checkpoints.

## Screenshots

![Main Menu](docs/img/menu.png)
*Main Menu*

---

![In-Game](docs/img/ingame-1.png)
*In-Game*

---

![In-Game](docs/img/ingame-2.png)
*In-Game*

## Technical Highlights

- **Flame Resource System:** Time-decaying dynamic light — intensity ratio directly drives the Light component
- **Ghost AI:** State machine (Idle ↔ Chasing) — detects player by flame intensity, wind-gust attack damages the flame
- **Physics-Based Movement:** Rigidbody force application with speed clamping, camera-relative direction
- **Crouch Mechanic:** Disables movement, resets velocity/rotation — acts as a hiding mechanism
- **Screen Effects:** Glitch effect on ghost attacks (triggered via ScreenManager)
- **Checkpoint System:** Respawn points managed by CheckpointManager

## Assets Used

[Assets](docs/ASSETS.md)

## Links

- [Play (itch.io)](https://calippooo.itch.io/the-last-jack)
