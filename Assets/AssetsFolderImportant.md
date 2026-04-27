# Assets Folder Information
The assets folder for the Unity project is too large for a Git commit. I pasted a Google Drive link below with the entire "Assets" folder. It needs to be extracted and placed inside the same directory.
https://drive.google.com/file/d/1MPAAzm_JFViIdMnaJEAMcbS42aReB8u3/view?usp=sharing

## Example Directory

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