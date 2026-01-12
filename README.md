# Blox3D Portrait (Godot 4)

A free, 3D, portrait-friendly Bloxorz-like puzzle game made with Godot 4.

## Controls
- Mobile: swipe or use on-screen arrows
- Desktop: arrow keys
- Restart: R

## Levels
`levels/levels.json`

Legend:
- . normal tile
- # void/hole
- S start
- G goal (must land upright on it)
- F fragile (breaks if upright)

## Build APK in the cloud (no local installs)
Push to GitHub, then:
Actions → **Build Android APK (Godot)** → **Run workflow** → download artifact `Blox3D-debug-apk`.
