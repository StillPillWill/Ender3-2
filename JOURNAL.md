# Build Journal — Ender3-2

## June 18: Dismantling and Frame Drilling

I started by completely dismantling both printers. Then I used a bolt cutter to create a double-sided screw and used that to join together 3 pieces of 4040. Then I drilled the new mounting holes in this piece of 4040 and assembled the Y-axis.

<img src="photos/img_0391.jpg" width="500" alt="Drilling into aluminum extrusion">

*Drilling center holes*

<img src="photos/img_0392.jpg" width="500" alt="Vertical frame component">

<img src="photos/img_0393.jpg" width="500" alt="Partially assembled frame">

**Time spent this session: 8 hours**

---

## June 19: Frame Assembly

Y-axis next to normal-sized print bed.

Originally, I only wanted to extend the y-axis, but then I realized I don't feel like ever doing this again, so I decided to also extend the x-axis with the same double-sided screw trick. And I figured it would be a waste if I didn't also use two lead screws since I had them. Those were wired in parallel.

<img src="photos/img_0394.jpg" width="500" alt="Printer frame mid-assembly">

<img src="photos/img_0395.jpg" width="500" alt="Frame assembly with gantry">

<img src="photos/img_0396.jpg" width="500" alt="Top-down view of frame layout">

**Time spent this session: 8 hours**

---

## June 20: First Power-On and Electronics

Here you can see the v1:

<img src="photos/img_0405.jpg" width="500" alt="V1 powered on for first time">

Now came the wiring. I had to figure out how to connect two motors on the y-axis and wire them in series to regulate current.

<img src="photos/img_0406.jpg" width="500" alt="Exposed electronics and wiring">

<img src="photos/img_0407.jpg" width="500" alt="Wiring the control board">

<img src="photos/img_0408.jpg" width="500" alt="Near-complete with wiring">

**Time spent this session: 8 hours**

---

## June 22–23: More Assembly

<img src="photos/img_0470.jpg" width="500" alt="Frame component">

<img src="photos/img_0419.jpg" width="500" alt="Disassembled Ender 3 parts">

<img src="photos/img_0420.jpg" width="500" alt="Parts laid out">

<img src="photos/img_0421.jpg" width="500" alt="Papers and planning">

**Time spent this session: 10 hours**

---

## July 9: The Bed

Now came the actual hard part: making a bed that big. Originally my idea was to take a basketball backboard and put some aluminum over it, but that was nowhere near level enough or stable enough to actually be used, so I ended up ditching it for a piece of plywood reinforced with some scrap metal I found on the side of the road.

<img src="photos/img_0468.jpg" width="500" alt="Cutting materials for the bed">

<img src="photos/img_0469.jpg" width="500" alt="Plywood with linear rails">

I also added some supports on either end of the y-axis to help it not tilt. And some pieces on the boundary between the 4040s to lock it in place.

<img src="photos/img_0471.jpg" width="500" alt="Underside of bed with supports">

It was during this time I also added a second motor on the y-axis to help it move such a large bed, wiring them in series to regulate current.

**Time spent this session: 10 hours**

---

## July 10–11: Firmware

Now came another very difficult step: writing custom firmware. This took me several days to get the bed leveling working, but I finally figured it out. It uses a **12×18 probe point arrangement**.

<img src="photos/img_0476.jpg" width="500" alt="Top-down view of printer on bed">

<img src="photos/img_0477.jpg" width="500" alt="Printer setup with blue tape">

📹 [Building the frame](videos/IMG_0404.MOV)

Here you can see the very first test print I did.

📹 [First test print](videos/IMG_0472.MOV)

<img src="photos/img_0478.jpg" width="500" alt="Printing a blue object">

Between the clearance holes cut for screws and the gaps between the pieces of 4040, the y-axis is rather bumpy, and every time it crosses over a gap, it jumps a little, leading to some pretty bad artifacts on the prints. But I'm going to try to remedy those at a later time with some JB Weld.

<img src="photos/img_0480.jpg" width="500" alt="Printing from above">

📹 [Printing](videos/IMG_0479.MOV)

📹 [More printing](videos/IMG_0481.MOV)

<img src="photos/img_0482.jpg" width="500" alt="Printing a boat model">

📹 [Final result](videos/IMG_0483.MOV)

**Final build volume: 585mm (X) × 775mm (Y) × 230mm (Z)**

The Z-axis got cut down because the bed is thicker than the original.

**Time spent this session: 18 hours**
