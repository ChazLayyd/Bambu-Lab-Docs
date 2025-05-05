---
layout: default
title: Mainboard
parent: Wiring
---

# Manta M5P Wiring

## Introduction

Here we will prepare the mainboard for wiring by installing jumpers in the right position, and you will find the wiring diagram here for wiring later on with detailed instructions as to where to plug things in.

Time Required: 20 minutes

---

## Initial preparation

Install jumpers in the places highlighted on the image below

#### Jumpers Placement Diagram
![Manta M5P Preparation](/images/Jumper%20M5P.png)

Green - Add Jumper

Leave any other jumper spots unpopulated.

{: .note}
> The jumper positions on the stepper slots here are for UART stepper drivers, like the TMC2209, please follow BigTreeTechs wiki here for information on using SPI drivers such as the TMC2240's or TMC5160's.

## Installing the PI / Equivalent

The Manta M5P supports the Raspberry Pi CM4, aswell as the BigTreeTech CB1 & CB2. All of these options work well. Allign the Pi CM4 or equivalent with the pins of the motherboard, and secure it using four M2.5X6 screws.

## Wiring Mainboard

* Connect 24V and GND from the PSU to the M5P's input
* Connect the B motor (Right Motor from the front) to M2
* Connect the A motor (Left  Motor from the front) to M3
* Connect the Z motor to M4
* Connect the Extruder motor to M5
* Connect the hotend heater to HE0
* Connect the part cooling fan to FAN1
* Connect the hotend cooling fan to FAN0
* Connect the hotend thermistor to TH0
* Connect the BIQU Microprobe as shown on the image.

#### Wiring Diagram

![Manta M5P Wiring](/images/manta-wires.jpg)

{: .warning}
> ENSURE THAT YOU FOLLOW THE DIAGRAM CAREFULLY FOR **HEATBED_CTRL_OUT**, you risk possible **THERMAL RUNAWAY** if you wire this incorrectly. GND **MUST** be connected to the **CONTROL PIN** of the mainboard, in this case **PA7**. I will not be responsible for any damages caused to you or your machine, you have been warned.

* Connect the 6 Pin PicoBlade connector from the bed into HEATBED_THERM.
* Connect the original SSR control cable to the new PCB, labeled HEATBED_CTRL_IN.
* Connect the HEATBED_CTRL_OUT to the pins shown on the image, **5V** must be supplied to the SSR, in this case from a NeoPixel connector.
* Connect HEATBED_THERM_OUT to TB on the M5P, if you get a bad thermistor reading, swap the pins. Polarity matters on this thermistor.

## Microprobe Wiring (Cred. BigTreeTech)

![Microprobe M5P Wiring](/images/microprobe%20m5p.png)

---

#### Last updated 05/05/2025