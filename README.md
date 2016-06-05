# UHK Datasheets

This repository contains the datasheets of the ICs used in the [Ultimate Hacking Keyboard](https://ultimatehackingkeyboard.com/), and its add-on modules, along with some related documentation.

## Base keyboard

The Kinetis K22P121M120SF7 ARM Cortex-M4 microcontroller is used as the brain of the right keyboard half.
* [K22P121M120SF7 Technical Data Sheet](K22P121M120SF7.pdf)
* [K22P121M120SF7 Reference Manual](K22P121M120SF7RM.pdf)

The Kinetis KL03P24M48SF0 ARM Cortex-M0+ microcontroller is used as the brain of the left keyboard half, and of the add-on modules.

* [KL03P24M48SF0 Technical Data Sheet](KL03P24M48SF0-782281.pdf)
* [KL03P24M48SF0 Reference Manual](KL03P24M48SF0RM.pdf)

The CAT24C256 I2C EEPROM is used in the right keyboard half to store the configuration of the UHK.

* [CAT24C256 256 kb I2C CMOS Serial EEPROM data sheet](CAT24C256-D.pdf)

The IS31FL3731 I2C LED driver is used in both keyboard halves to drive the LED display and per switch backlighting.

* [IS31FL3731 I2C Audio Modulated Matrix LED Driver data sheet](31FL3731.pdf)

A custom LED segment display is used in the left keyboard half.

* [Custom LED segment display schematic](led-display.png)

## Add-on modules

A BlackBerry trackball is used in the key cluster module. Even though this trackball doesn't seem to have any datasheets available, SparkFun sells a breakout board that features it, so we use their design as our reference design.

* [SparkFun Blackberry Trackballer Breakout](https://www.sparkfun.com/products/13169)

The ADNS-3530 optical sensor is used in the trackball module.

* [ADNS-3530 Low Power LED Integrated Slim Mouse Sensor data sheet](ADNS-3530.pdf)

The IQS572 capacitive sensing controller is used in the touchpad module.

* [IQS5xx-A000 Trackpad Datasheet](trackpad/iqs5xx-a000_trackpad_datasheet.pdf)
* [IQS5xx Reference Design](trackpad/iqs5xx_reference_designs/IQS5xx.pdf)
* [AZD067 Application Note: IQS5xx Trackpad Communication Interface](trackpad/azd067_iqs5xx_trackpad_communication_interface.pdf)
* [AZD068 Application Note: Trackpad Design Guide](trackpad/azd068-trackpad_design_guide.pdf)
* [AZD070 Application Note: IQS5xx Programming and GUI (data streaming) Guide](trackpad/azd070_iqs5xx_programming_and_data_streaming_guide.pdf)

The part number of the trackpoint within our trackpoint module is unknown, and the label of the IC is scraped off, but it's probably the SK7102 FlexPointTM PS/2 Pointing Stick Mouse Encoder. We believe this because the trackpoint closely resembles the SK8702 FlexPointTM 3 Axis PS/2 Pointing Stick Module, which uses this IC.

* [The incomplete datasheet of the trackpoint](trackpoint/trackpoint_module.pdf) - Our supplier didn't provide us the name or complete datasheet of the trackpoint because he signed an NDA with the manufacturer.
* [SK8702 FlexPointTM 3 Axis PS/2 Pointing Stick Module](trackpoint/DS0013_SK8702_Datasheet.pdf) - No longer in production but this documentation may come in handy.
* [SK7102 FlexPointTM PS/2 Pointing Stick Mouse Encoder ](trackpoint/DS0006 SK7102 Datasheet.pdf) - The IC of the SK8702, and probably the unknown trackpoint, too.
