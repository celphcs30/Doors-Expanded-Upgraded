# Doors Expanded - Upgraded

A fork of [Doors Expanded](https://github.com/jecrell/DoorsExpanded) updated for RimWorld 1.6.

## About

Adds new types and sizes of doors to RimWorld and an extensible framework for other mods to add such doors.

Currently included:
* Doors (2x1, 3x1) - Double/triple sized vanilla doors.
* Curtains (Tribal) (1x1, 2x1, 3x1) - Fragile, flammable, and made of fabric, these curtains provide fast movement through buildings.
* Jail Door (1x1) - Stronger door to keep prisoners inside.
* Gates (2x1) - Stylized doors perfect for meeting pre-industrial needs.
* Remote Doors (1x1, 2x1, 3x1) - Garage-style doors that can be opened by remote buttons or levers.
* Blast Doors (1x1, 2x1, 3x2) - Incredibly tough and secure doors used to keep greater threats at bay. Also can be opened by remote buttons or levers.
* Autodoors (2x1, 3x2) - Double/triple sized autodoors. All autodoors (including vanilla 1x1 autodoor) also can be opened by remote buttons or levers.

## Requirements

* RimWorld 1.6
* [Harmony](https://github.com/pardeike/HarmonyRimWorld) (mod dependency)

## Changes from Original

* Updated for RimWorld 1.6 only (removed support for older versions)
* Fixed inheritance to use `Building_Door` instead of removed `Building_MultiTileDoor`
* Cleaned up project structure
* Added optional Anomaly expansion support with containment stats on secure doors

## Anomaly Expansion Support

If you have the **Anomaly** expansion installed, certain doors will automatically receive containment strength stats for use in containment facilities:

* **Jail Door** (1x1): 100 containment strength
* **Blast Door** (1x1): 140 containment strength
* **Blast Door** (2x1): 180 containment strength
* **Blast Door** (3x2): 300 containment strength

The containment stats are added automatically via a conditional patch that only applies when Anomaly is installed. If you don't have Anomaly, the mod works normally without these stats.

## Installation

1. Download or clone this repository
2. Place the `Doors-Expanded-Upgraded` folder in your RimWorld `Mods` directory:
   - Steam: `C:\Program Files (x86)\Steam\steamapps\common\RimWorld\Mods\`
   - Or your RimWorld installation's `Mods` folder
3. Enable the mod in RimWorld's mod menu

## Credits

Original mod by Jecrell and lbmaian  
Commissioned by CMDR Toss Antilles

## License

See LICENSE file for details.
