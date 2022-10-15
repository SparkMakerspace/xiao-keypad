# Spark RP9 (xiao-keypad)

The **RP9** was developed by some of the nerds at [Spark Makerpace](https://sparkmakerspace.org) for use in the Electronics & Technology Lab's soldering certification. 

**The problem:** most entry-level soldering kits are not useful following
**The solution:** make it a keyboard (macropad). the kids tell us it's what they're into these days.

Assumptions:
* Decent temperature-adjustable soldering irons.
* An instructor skilled in through-hole and surface-mount soldering.
* students with little-to-no prior soldering experience.
* 

Requirements:
* Ability to read values to demonstrate oscilloscope.
* Assemblable 2-3 hours of class time.

Requirements:
* Seeedstudio Xiao RP2040 as MCU
  * Mounted on top of board so RGB LED is visible
  * Instructions printed on board.
  * Leave serial pin unused. Break to testpoint?
  * Pinout for Xiao fully labeled on board.
  * SMT 3.5mm jack for I2C SDA/SCL/GND (no power!!)
  * Diodes and MCU **not stacked**.
  * COL2ROW diode alignment.
  
v2 goals:
* wider Xiao pads for mounting castellations.
* hotswap
* rgb (reverse-mount)
* support non-mx switches
* SAO connector
* cat pics.
