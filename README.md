<img src="./Assets/render.png" align="center" />

<br />

<h1 align="center">toomanyparts</h1>

<p align="center">
    When you have one or two (or three) too many ender 3's laying around
</p>

---

## What is this?

toomanyparts (should've picked a better name) is a fully-featured, and competent 3D printer that can take on any job you throw at it. Using recycled 3D printer parts.

---

## Why?

I mainly started it since I had most of the parts to build a working 3D printer except missing a couple of things, mainly hardware. So, I designed a hodgepodge of a Voron 2.4 frame, Voron Trident motion system, and Ender 3 parts.

---

## Features

**220mm build plate:**

From the ender 3... can this even be advertised?

**Inverted Electronics by [LoganFraser](https://mods.vorondesign.com/details/pXkXHVIUbqSWqQKJISczw):**

So you don't have to flip the printer upside down every couple of months when you want to tackle cable management again.

**AWD Gantry:**

Uses the popular [monolith gantry](https://github.com/Monolith3D/Monolith_Gantry) mod adapted to use the ender 3 motors.

**Fully Enclosed (Soon):**

Engineering filaments such as ABS/ASA.

**Wide Mod Availability:**

Since the design is heavily based around the Voron Trident, there are many mods that can be adapted to it easily.

**Automatic Bed Leveling**

No more pesky bed springs that require manual adjustment. The bed is now rigidly mounted and uses a BTT Eddy Duo to do bed leveling + meshing.

**Klipper:**

Very customizable firmware

---

## Structure

The frame is built from 2020 aluminum extrusions (doomcube probably possible), built mostly to the Voron 2.4 spec with some extra extrusions required.

---

## Toolhead

The printer uses the stock Ender 3 hotend setup but with a different toolhead design. It uses the [Xol Carriage by Armchair Heavy Industries](https://github.com/Armchair-Heavy-Industries/Xol-Toolhead/tree/main) due to it's compatibility with the monolith gantry and its wide compatibility with other toolheads if it were to be updated down the line. It uses a BigTreeTech Eddy Duo to do it's bed leveling/meshing, providing unparalleled accuracy compared to other solutions. It uses an orbiter V2(.5), providing one of the best extruders out there. Additionally, it uses a toolhead board of your choice, mounted at the back of the orbiter, reducing the amount of wires running from the toolhead to the electronics. Dual part cooling fans to allow for quicker prints.

---

## Electronics

It uses two Creality V4.2.2 connected to a SBC (such as a Raspberry Pi) running Klipper allowing for a more customizable and configurable 3D printer firmware.

---

## CAD

The CAD is fully available for every one to see. It can be found [here](https://cad.onshape.com/documents/7e037669fa182a370c2ec31a/w/a0e81e4c5776c721c1663f0b/e/defcd2cfb7a39093f38b651e) or the link in the CAD directory.

---

## BOM

If you just happen to be in the same circumstance as I am, the BOM can be found [here](./BOM.csv).
