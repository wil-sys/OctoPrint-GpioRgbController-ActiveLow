# OctoPrint-GpioRgbController

This is a lightweight plugin dedicated to the control of an external RGB LED strip via Raspberry Pi GPIO pins.  This plugin has the following features:

* Convenient sidebar control
* Adjustable RGB color picker
* Pin selection via settings
* Optional on/off trigger via input pin
* M150 GCODE support
* Independent GCODE control using optional RGB index


## Setup

Install using this URL in the octoprint plugin manager

    https://github.com/wil-sys/Octoprint-GpioRgbController-ActiveLow/archive/master.zip


## IMPORTANT - LED Strip Compatibility

This plugin is only intended to drive discrete or strip RGB LED's via independent GPIO control.  This plugin will not work with LED strips that have coontrolers or digital interface such as SPI.  




