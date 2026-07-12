# Ender3-2

> What if you took an Ender 3, and squared it.

Two Ender 3 printers dismantled and merged into one large-format Cartesian 3D printer with a **585 × 775 × 230mm** build volume.

<img src="photos/img_0482.jpg" width="600" alt="Ender3-2 printing a boat">

## What It Does

A custom large-format FDM 3D printer built from two dead Ender 3s. Extended both axes with 4040 aluminum extrusion, built a massive bed from plywood and road-found scrap metal, wrote custom firmware with a 12×18 probe mesh for bed leveling.

## How It Works

Cartesian (bed slinger) design. The Y-axis moves the entire bed on dual lead screws (wired parallel) with dual motors (wired series). The X-axis gantry rides on extended 4040 extrusion. Custom firmware on the Creality 4.2.2 board handles the non-standard bed size and BLTouch probing.

## Why I Made It

I had two broken Ender 3s and didn't want to just throw them away. I figured if I'm going to rebuild one, I might as well make it absurdly big. The goal was maximum build volume on a zero-dollar budget — almost everything was reused from the donor printers.

## Specs

| | |
|---|---|
| **Build volume** | 585mm (X) × 775mm (Y) × 230mm (Z) |
| **Frame** | 3× 4040 aluminum extrusion, double-sided screw joints |
| **Bed** | Plywood reinforced with scrap metal, steel surface |
| **Bed leveling** | Custom firmware, 12×18 probe mesh |
| **Controller** | Creality 4.2.2 (from Ender 3 V2) |
| **Probe** | BLTouch (X=-41.5, Y=-7) |
| **Y-axis** | Dual lead screws, dual motors |
| **Total cost** | ~$16 (only belt + plywood purchased) |
| **Build time** | 70 hours |

## CAD

Full STEP files in [`CAD/`](CAD/).

## BOM

See [`BOM.csv`](BOM.csv) — only bought belt and plywood (~$16 total). Everything else came from the two donor Ender 3s.

## Build Photos

<img src="photos/img_0478.jpg" width="400" alt="Printing">
<img src="photos/img_0482.jpg" width="400" alt="Printing a boat">
<img src="photos/img_0476.jpg" width="400" alt="Full setup">

## Videos

[Building the frame](videos/IMG_0404.MOV) · [First test print](videos/IMG_0472.MOV) · [Printing](videos/IMG_0479.MOV) · [More printing](videos/IMG_0481.MOV) · [Final result](videos/IMG_0483.MOV)

## Journal

See [`JOURNAL.md`](JOURNAL.md) for the full build log with dated entries and timestamps.
