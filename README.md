# BJT Water Level Indicator

## Overview

A water level indicator using NPN BJTs forced into saturation mode via a minuscule current from tap water, which flows into the base and is amplified to light up a reference LED.

## Hardware Specifications

- **Level Indicators** 3× LEDs
- **Current Amplifier** 3× 2N3904 BJTs
- **Probes** 4× 15+cm 22 AWG stripped wire (1× Master Probe, 3× Probes connected to base of 2N3904 BJTs)
- **Circuit Protection** 3× 1kΩ Resistors

## Prerequisites

To achieve my 5V power rail, I used a battery pack regulated to output 5V. Here is a link to the repository:
[5V Linear Breadboard Power Supply](https://github.com/mhos2006/starter-dc-makeshift-power-supply)

## Schematic

<img width="460.5" height="340.5" alt="image" src="https://github.com/user-attachments/assets/9f9fa491-808c-4988-942b-f2906b24de72" />

## Testing

https://github.com/user-attachments/assets/e5b6b6be-7824-49d6-9163-9148845a0b6e

## Schematic and PCB Documentation

I created the schematic using KiCad software. While my schematic has been verified, I have moved the components over to PCB software. PCB layout and component placement is in progress.


