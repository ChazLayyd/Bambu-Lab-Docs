---
layout: default
title: Preparation
parent: The Build
nav_order: 1
---

## Introduction

We will begin preparing the printed parts here, you will need:

1. Soldering Iron
2. M3X5X4 Heat Set Inserts
3. M3X6 Screws

Time Required: 20 minutes for the printed parts, up to 1 hour for the Klipper install

---

# Mainboard Klipper

We need to install Klipper onto the Pi CM4 or CB2 before we go further as it will be painful to do later on. 

Follow BigTreeTech's steps on how to flash Klipper to the Pi and the STM32G0B1 chip on the mainboard. You can find the link to that [here](https://bttwiki.com/Software%20Installation.html), if using a CB2, follow [these steps](https://github.com/bigtreetech/CB2/blob/master/BIGTREETECH%20CB2%20User%20Manual.pdf). Make sure to use the correct jumper positions if powering via USB (5V).

---

# Printed Parts

## Sanity Checks
1. Align the mainboard with the electronics box and confirm:
   - The pin in the top left aligns with the mounting hole.
   - All three other mounting holes are a perfect fit.
2. If all is aligned, proceed. Otherwise, troubleshoot the fitment or reprint the electronics box.

## Heat Set Inserts
Melt in **M3 x 5 x 4 heat set inserts** into the electronics box. There are 9 positions to fill (highlighted in the diagram). Use a metal tool with a flat edge to align them neatly.

<video width="640" height="360" preload="auto" controls>
   <source src="/videos/Electronics Heatset.mp4" type="video/mp4">
   <!-- Fallback -->
   <p style="color:red; font-weight: bold;">Your browser doesn't support embedded videos.</p>
</video>

## Testing fitment of the Mainboard

1. Place the assembled mainboard into the electronics box and secure it with **M3 x 6mm or M3 x 8mm screws**.
2. (Optional) Test the lid fitment by screwing it into place.

## Final Check
If everything fits perfectly, remove the lid and the mainboard from the electronics box for wiring and further assembly.

---

## Fan Cover

Before we continue, make sure to remove any supports on the print.

## What you will need
1. 4x **4mm x 2mm** Magnets
2. Some super glue
3. M3X4.2X3 Heat Set Inserts
4. M3X18 ULP Screws
5. A 5015 fan **(The stock Bambu Lab 5015 will not work here)**
6. BIQU Microprobe

## Magnet Installation
To match the polarity of the magnets, take your Original Fan Cover and note the direction. There are 4 magnets you will need to insert, these are designed to be a tight fit so please take your time. If your printer is not tuned well, you may have a hard time inserting these. Using the video below, position the magnets as shown on the rear of the cover. Test the fitment of the fan cover, it attaches exactly the same as the original does. You may notice that the magnets are weaker, but aslong as it alligns you will be fine.

<video width="640" height="360" preload="auto" controls>
   <source src="/videos/Toolhead Assy.mp4" type="video/mp4">
   <!-- Fallback -->
   <p style="color:red; font-weight: bold;">Your browser doesn't support embedded videos.</p>
</video>

{: .note}
> There are two versions of this fan cover, one with heat set inserts and one that is press fit. The heat set insert version is the recommended version as it is harder to damage and more secure overall.

## Press Fit Version
**I recommend installing the fan way later on in the guide, leave it off for now**. To install the 5015 fan on the press fit version allign it with the pegs and press down, it should be very snug. **Avoid reusing the original screws as they will snap the pegs**, the 3D printed pegs can be very weak and are very likely to crack, so I recommend against doing this, you have been warned.

## Heat Set Version
**I recommend installing the fan way later on in the guide, leave it off for now**. There are **2** heat set inserts that must be inserted on the front of the fan cover, these are used to secure the 5015 fan to the cover. Using a soldering iron, slowly melt them in and use a flat metal object to straighten it out. Once inserted, allign the 5015 fan with the inlet of the duct, and then use two M3X18 ULP screws to secure the 5015 fan to the fan cover.

---

## Probe
To install the BIQU Microprobe, first plug in the long provided cable, and then allign the BIQU Microprobe as shown in the video below. Using the screws provided, secure the Microprobe by threading it into the plastic. Make sure the cable is routed along the left side of the 5015 fan to avoid issues with fitment.

---

# Final Checks

Once all of the components have been installed, test the fitment again ensuring that you have routed the cables in the correct places. If everything still alligns well we are ready to proceed to disassembly.

#### Last updated 05/05/2025