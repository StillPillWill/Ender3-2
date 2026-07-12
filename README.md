# Ender3-2

> What if you took an Ender 3, and squared it.

Two Ender 3 printers dismantled and merged into one large-format Cartesian printer.

**585 × 775 × 230mm** build volume.

<img src="journal/01-build/v1-printer-build.jpg" width="600" alt="Ender3-2 v1 build">

## Specs

| | |
|---|---|
| **Build volume** | 585mm (X) × 775mm (Y) × 230mm (Z) |
| **Frame** | 3× 4040 aluminum extrusion, double-sided screw joints |
| **Bed** | Plywood + scrap metal reinforcement, steel surface |
| **Bed leveling** | Custom firmware, 12×18 probe mesh |
| **Controller** | STM32F103RC |
| **Probe** | BLTouch (X=-41.5, Y=-7) |
| **Y-axis** | Dual lead screws, dual motors |

## Build

The whole thing started with a bolt cutter and two dead Ender 3s. Extended both axes with 4040 extrusion, built a massive bed from plywood and road-found scrap metal, wrote custom firmware to level it, and somehow it works.

<img src="journal/01-build/bed-sheet-metal.jpg" width="600" alt="Bed construction">

[Full build journal →](journal/01-build/build.md)

## Videos

[First test print](journal/01-build/IMG_0472.MOV) · [Printing](journal/01-build/IMG_0479.MOV) · [Final result](journal/01-build/IMG_0483.MOV)
