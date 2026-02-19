# Better Minimap

A BepInEx mod for Erenshor that provides improvements to the minimap functionality.

## Features

- **Always Moveable**: Drag the minimap anytime by clicking and dragging on it - no need to enter UI Edit Mode
- **Resize Toggle**: New button (+/−) on the minimap to quickly toggle between small and large sizes
- **Position Persistence**: Minimap position and size are saved and restored between game sessions
- **Area Map Overlay**: Press **M** to open a full-screen area map for the current zone
  - Shows detailed area map for overworld zones
  - Automatic fallback to world map for dungeons/instances
  - Toggle button to switch between Area Map and World Map views

## Installation

1. Install BepInEx for Erenshor
2. Copy `BetterMinimap.dll` to `BepInEx/plugins/BetterMinimap/`
3. Copy the `Assets` folder to `BepInEx/plugins/BetterMinimap/Assets/`
   - The Assets folder should contain zone map PNG images (from AreaMaps mod)

## Configuration

Edit the config file at `BepInEx/config/the-xorcist.betterminimap.cfg`:

| Setting | Default | Description |
|---------|---------|-------------|
| PositionX | 700 | Saved X position of the minimap |
| PositionY | 433 | Saved Y position of the minimap |
| IsBigMap | false | Whether the minimap is in large mode |
| AreaMapKey | M | Key to open the area map overlay |

## Usage

### Moving the Minimap
- Click and drag anywhere on the minimap to reposition it
- The position is automatically saved when you release

### Resizing the Minimap
- Click the **+** or **−** button on the minimap to toggle between small and large sizes
- The size preference is saved automatically

### Area Map
- Press **M** (default) to open the area map overlay
- If you're in a zone with a detailed area map, it shows that map
- Click "World Map" to see the full world overview
- Click "Area Map" to return to the zone map (if available)
- Click "Close" or press **M** again to close the overlay

## Assets Required

This mod requires zone map images in the `Assets` folder. These are the same images used by the AreaMaps mod:
- `Azure.png`, `Azynthi.png`, `Blight.png`, etc. (zone maps)
- `MapRoutes.png` (world map)

## Credits

This mod integrates area map functionality inspired by:
- [Area Maps by Ayloonah](https://thunderstore.io/c/erenshor/p/Ayloonah/Area_Maps/) - The original zone map overlay mod for Erenshor. Zone map images are sourced from the [Erenshor Wiki](https://erenshor.wiki.gg/).
