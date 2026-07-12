# Build Journal — Entry 01

## The Frame

I started by completely dismantling both printers. Then I used a bolt cutter to create a double-sided screw and used that to join together 3 pieces of 4040. Then I drilled the new mounting holes in this piece of 4040 and assembled the Y-axis.

<img src="drilling-aluminum-extrusion.jpg" width="500" alt="Drilling into aluminum extrusion">

*Drilling center holes*

<img src="lead-screws-bracket.jpg" width="500" alt="Lead screws and bracket">

Y-axis next to normal-sized print bed.

Originally, I only wanted to extend the y-axis, but then I realized I don't feel like ever doing this again, so I decided to also extend the x-axis with the same double-sided screw trick. And I figured it would be a waste if I didn't also use two lead screws since I had them. Those were wired in parallel.

Here you can see the v1:

<img src="v1-printer-build.jpg" width="500" alt="V1 build">

---

## The Bed

Now came the actual hard part: making a bed that big. Originally my idea was to take a basketball backboard and put some aluminum over it, but that was nowhere near level enough or stable enough to actually be used, so I ended up ditching it for a piece of plywood reinforced with some scrap metal I found on the side of the road.

<img src="bed-sheet-metal.jpg" width="500" alt="Sheet metal on frame">

I also added some supports on either end of the y-axis to help it not tilt. And some pieces on the boundary between the 4040s to lock it in place.

<img src="bed-plywood-supports.jpg" width="500" alt="Plywood bed supports">

<img src="bed-base-assembly.jpg" width="500" alt="Bed base assembly">

It was during this time I also added a second motor on the y-axis to help it move such a large bed, wiring them in series to regulate current.

---

## Firmware

Now came another very difficult step: writing custom firmware. This took me several days to get the bed leveling working, but I finally figured it out. It uses a **12×18 probe point arrangement**.

📹 [IMG_0472.MOV](IMG_0472.MOV) — first test print

Here you can see the very first test print I did.

📹 [IMG_0479.MOV](IMG_0479.MOV) — printing

Between the clearance holes cut for screws and the gaps between the pieces of 4040, the y-axis is rather bumpy, and every time it crosses over a gap, it jumps a little, leading to some pretty bad artifacts on the prints. But I'm going to try to remedy those at a later time with some JB Weld.

📹 [IMG_0483.MOV](IMG_0483.MOV) — final result

**Final build volume: 585mm (X) × 775mm (Y) × 230mm (Z)**

The Z-axis got cut down because the bed is thicker than the original.
