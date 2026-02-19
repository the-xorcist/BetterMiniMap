# BetterMinimap

**Version:** 1.0.0  
**Author:** noone  
**Release Date:** 2026-02-18

## Description

BetterMinimap enhances Erenshor's minimap with quality-of-life improvements including drag-and-drop repositioning, quick resize toggling, persistent settings, and a full-screen area map overlay for detailed zone navigation.

## Features

- **Always Moveable** - Drag the minimap anywhere without entering UI Edit Mode using the diamond-shaped handle
- **Quick Resize Toggle** - Right-click the minimap buttons to instantly switch between small and large sizes
- **Position Persistence** - Minimap position and size preferences are automatically saved between sessions
- **Area Map Overlay** - Press **M** to open a full-screen map showing detailed zone layouts for overworld areas
- **Smart Map Fallback** - Automatically displays the world map for dungeons and instances without area maps
- **Map Toggle Button** - Switch between Area Map and World Map views with a single click

## Installation

1. Install [BepInEx 5](https://github.com/BepInEx/BepInEx/releases) for Erenshor
2. Copy `BetterMinimap.dll` to `BepInEx/plugins/` folder
3. Copy the `Assets` folder to `BepInEx/plugins/BetterMinimap/` folder
4. Launch the game

## Configuration

Settings are automatically saved to `BepInEx/config/the-xorcist.betterminimap.cfg`:

- **PositionX/PositionY** - Saved minimap position
- **IsBigMap** - Minimap size preference (small/large)
- **AreaMapKey** - Keybind for area map overlay (default: M)

## Source Code

Source code is included in the `-source.zip` archive.
