# Orbital Station Escape
Takes place in a sci-fi orbital station where a small ball of energy is trying to survive its encounters against an enemy AI drone. To stay alive, it has to collect energy crystals floating around the station to power itself. But there is a broken AI security drone moving around, trying to destroy it. Your job is to grab all the energy cores while avoiding the drone.

## Game Demo

[Itch.io Upload](https://doovinci.itch.io/orbital-station-escape)

[Video Demo](https://drive.google.com/file/d/1jUljLYaRVL8SjjMptQK6VvMkjWvLm8az/view?usp=sharing)

[Google Drive Repository (Alternative -- includes `Assets` folder)](https://drive.google.com/drive/folders/1Z4OjWLcNmZEtB6SyIOwykhKwl9H9QFpA?usp=sharing))

## Genre
Arcade / Casual Survival

## Platform
Desktop -- Browser Website

## Controls

| Action | Input |
| --- | --- |
| Move | `W` `A` `S` `D` or Arrow Keys |
| Look around | Mouse |
| Zoom in / out | Mouse Scroll Wheel |
| Restart after Win/Lose | `R` |

## How to Play

- Roll around the orbital station and collect every glowing **Energy Crystal**.
- Avoid the **Security Drone** at all costs — one hit and it's over.
- Look out for power-ups:
  - **Speed Boost** — temporarily increases your movement speed.
  - **Shield** — absorbs one drone collision before breaking.
- Collect every core to win. Get caught by the drone to lose.

## Prerequisites
The assets folder for the Unity project is too large for a Git commit. A Google Drive link below with the entire "Assets" folder is included. It needs to be extracted and placed inside the same directory. https://drive.google.com/file/d/1MPAAzm_JFViIdMnaJEAMcbS42aReB8u3/view?usp=sharing

## Project Setup

- **Engine:** Unity 2022.3.62f3 (LTS)
- **Render Pipeline:** Universal Render Pipeline
- **Input:** Unity Input System package

To open the project:

1. Clone the repository.
2. Download the Assets folder from the Google Drive link.
3. Extract the Assets folder into the same directory as the repository (Project Structure below).
4. Open Unity Hub and add the folder as an existing project.
5. Open with Unity 2022.3.62f3.
6. Open the scene `Assets/Scenes/MiniGame.unity`.
7. Press Play.

## Project Structure

```
Assets/
├── Scenes/             # MiniGame.unity
├── Scripts/            # Gameplay scripts
│   ├── PlayerController.cs    # Ball movement, pickup, win/lose, restart
│   ├── EnemyMovement.cs       # Drone chase mechanics
│   ├── CameraController.cs    # Mouse orbit, zoom, wall collision
│   ├── Rotator.cs             # Rotating script for pick-up items
│   ├── SpeedBoost.cs          # Speed boost pickup component
│   ├── Shield.cs              # Shield pickup component
│   └── AlarmLightPulse.cs     # Red/white alarm lights
├── Prefabs/            # Unity prefabs
├── Materials/          # Materials for environment
├── Imported Assets/    # Custom assets made for the game, including 3D models, materials, textures, etc.
└── _GameDev/           # Fonts, textures
```

## Credits
Vincent Do, 
Govil Monga
