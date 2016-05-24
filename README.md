# UHK Datasheets

This repository contains the datasheets of the ICs used in the [Ultimate Hacking Keyboard](https://ultimatehackingkeyboard.com/), and its add-on modules, along with some related documentation.

## Base keyboard

The Kinetis K22P121M120SF7 ARM Cortex-M4 microcontroller is used as the brain of the right keyboard half.
* [Technical Data Sheet](K22P121M120SF7.pdf)
* [Reference Manual](K22P121M120SF7RM.pdf)

The Kinetis KL03P24M48SF0 ARM Cortex-M0+ microcontroller is used as the brain of the left keyboard half, and of the add-on modules.

* [Technical Data Sheet](KL03P24M48SF0-782281.pdf)
* [Reference Manual](KL03P24M48SF0RM.pdf)

The CAT24C256 I2C EEPROM is used in the right keyboard half to store the configuration of the UHK.

* [CAT24C256 256 kb I2C CMOS Serial EEPROM data sheet](CAT24C256-D.pdf)

The IS31FL3731 I2C LED driver is used in both keyboard halves to drive the LED display and per switch backlighting.

* [IS31FL3731 I2C Audio Modulated Matrix LED Driver data sheet](31FL3731.pdf)

## Add-on modules

The ADNS-3530 optical sensor is used in the trackball module.

* [ADNS-3530 Low Power LED Integrated Slim Mouse Sensor data sheet](ADNS-3530.pdf)

Our custom touchpad module is backed by the IQS572 capacitive sensing controller.

* [IQS5xx-A000 Trackpad Datasheet](trackpad/iqs5xx-a000_trackpad_datasheet.pdf)
* [AZD067 Application Note: IQS5xx Trackpad Communication Interface](trackpad/azd067_iqs5xx_trackpad_communication_interface.pdf)
* [AZD068 Application Note: Trackpad Design Guide](trackpad/azd068-trackpad_design_guide.pdf)
* [AZD070 Application Note: IQS5xx Programming and GUI (data streaming) Guide](trackpad/azd070_iqs5xx_programming_and_data_streaming_guide.pdf)
