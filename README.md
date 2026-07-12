# Ender3-2

> What if you took an Ender 3, and squared it.

Two Ender 3 printers dismantled and merged into one large-format Cartesian printer with a **585 × 775 × 230mm** build volume.

## Specs

| Axis | Travel | Notes |
|------|--------|-------|
| X | 585mm | Extended with double-sided screw join on 4040 extrusion |
| Y | 775mm | Dual lead screws (wired parallel), dual motors (wired series) |
| Z | 230mm | Reduced from stock — thicker bed eats the clearance |

- **Frame:** 3× 4040 aluminum extrusion, bolt-cutter double-sided screw joints
- **Bed:** Plywood reinforced with scrap metal, steel plate surface
- **Bed leveling:** Custom firmware, 12×18 probe mesh
- **Controller:** STM32F103RC, BLTouch (X=-41.5 Y=-7 offset)
- **Baud:** 115200

## Build Journal

| Entry | Description |
|-------|-------------|
| [01 — The Build](journal/01-build/build.md) | Frame extension, bed construction, firmware, first prints |

## Gallery

<img src="journal/01-build/drilling-aluminum-extrusion.jpg" width="400" alt="Drilling aluminum extrusion">
<img src="journal/01-build/v1-printer-build.jpg" width="400" alt="V1 build">
<img src="journal/01-build/bed-sheet-metal.jpg" width="400" alt="Bed construction">
<img src="journal/01-build/bed-plywood-supports.jpg" width="400" alt="Bed supports">

## Videos

- [First test print](journal/01-build/IMG_0472.MOV)
- [Printing](journal/01-build/IMG_0479.MOV)
- [Final result](journal/01-build/IMG_0483.MOV)
