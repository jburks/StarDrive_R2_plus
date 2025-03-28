# StarDrive_R2_plus
StarBoard SCSI Drive attachment with real-time clock

## Mini-FAQ:

### What is it?

StarDrive R2+ is an upgraded version of Chris "Crispy" Brenner's original reverse-engineered remake of the Microbotics StarDrive for their
StarBoard 2 expansion module for the Amiga 1000.

### Where can I get it?

This product is still in development. All files necessary for making your own will be here and links to assembled boards for sale will be
placed here when available.

### What's the status?

The original project has been converted to KiCAD and ports have been placed as accurately as possible using the materials still available
from Crispy's original design. Additional footprints for the slightly more available PCF8573T and footprints for a microcontroller and modern RTC are
WIP.

### What's this about an upgrade?

The original StarDrive uses two components that are no longer in production: the AM5380 SCSI interface controller; and the PCF8573P real-time clock.
Direct replacements are not known to be available for either, so StarBoard R2+ is planned to contain a microcontroller capable of emulating the PCF8573
so that a modern, easy to source solution is available. A substitute for the AM5380 has not been identified.

### How can I help?

The project would benefit from a modified StarBoard 2 driver that modifies the I2C code to talk to a modern RTC directly so that a PCF8573 or a
microcontroller that emulates one is not necessary.

## Board renderings

### Front:

![StarDrive R2+ Front](/EV1/StarDrive_R2+_Front.png)

### Back:

![StarDrive R2+ Back](/EV1/StarDrive_R2+_Back.png)
