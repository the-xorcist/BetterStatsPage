# BetterStatsPage

**Version:** 1.0.1  
**Author:** the-xorcist  
**Release Date:** 2026-02-17

## Description

BetterStatsPage is an enhanced stats and reputation UI mod for Erenshor. It replaces the default stats display with a modern tabbed interface that provides comprehensive character information at a glance. View detailed stats, faction reputation, and more through an intuitive draggable window with smooth animations.

## Features

- **Tabbed Interface** - Switch between Stats and Reputation views with a single click
- **Comprehensive Stats Display** - View all character attributes including:
  - Level and Ascension Level
  - Experience progress
  - All attributes (Str, Dex, End, Agi, Int, Wis, Cha) with item bonuses shown separately
  - Combat stats: Crit Chance, Dodge Chance, Physical Attack
  - Magic stats: Spell Damage Bonus, Healing Bonus
  - Special stats: Life Steal, Damage Shield, Attack Speed, Move Speed, Resonance Proc Chance
- **Reputation Tab** - View all faction standings in one place
- **Draggable Window** - Reposition the panel anywhere on screen using the drag handle
- **Auto-Update** - Stats refresh automatically when they change
- **Smooth Animations** - Fade in/out transitions for a polished experience
- **Extensible Tab System** - Other mods can register custom tabs via TabRegistry API

## Installation

1. Install [BepInEx](https://github.com/BepInEx/BepInEx) for Erenshor (if not already installed)
2. Copy `BetterStatsPage.dll` to `BepInEx/plugins/` folder
3. Launch the game

## Usage

- Press **P** (default) to toggle the stats window
- Click tabs to switch between different views
- Drag the window by the diamond-shaped handle to reposition
- Configure the toggle key and colors in `BepInEx/config/the-xorcist.betterstatspage.cfg`

## Changelog

### v1.0.1 (2026-02-17)
- Initial release
- Tabbed stats and reputation interface
- Draggable, auto-updating window
- Configurable keybinds and colors

## Source Code

Source code is included in the `-source.zip` archive.
