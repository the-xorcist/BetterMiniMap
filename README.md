# BetterMinimap

**Version:** 1.0.4  
**Author:** the-xorcist  
**Release Date:** 2026-02-24

## Description

BetterMinimap enhances Erenshor's minimap with improved dragging, resizing, and a full-screen area map overlay. Move the minimap freely without UI Edit Mode, toggle between small and large sizes, and view detailed zone maps with the press of a key.

## Features

- **Always Moveable Minimap** - Drag the minimap anytime without entering UI Edit Mode
  - Blue diamond drag handle below the minimap
  - Click anywhere inside the circular map area to drag
- **Resize Toggle** - Right-click any minimap button to toggle between small and large sizes
- **Position & Size Persistence** - Minimap position and size are saved between sessions
- **Lock North Persistence** - Lock North button state is remembered across sessions
- **Area Map Overlay** - Press **M** to open a full-screen area map
  - Detailed area maps for overworld zones
  - Automatic fallback to world map for dungeons/instances
  - Toggle between Area Map and World Map views
  - Draggable panel with position persistence

## Installation

1. Install BepInEx for Erenshor
2. Copy the `BetterMinimap.dll` file to `BepInEx/plugins/` folder
3. Launch the game

## Changelog

### v1.0.4 (2026-02-24)
- Fixed Assets path resolution to work with versioned plugin folder names (e.g. BetterMinimap-v1.0.3)

## Source Code

Source code is included in the `-source.zip` archive.
