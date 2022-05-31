# Microcontroller Code
For senior project at UOP, 2022.
Part of the Budget Tesla team's implementation of an autonomous electric golf cart.
In the end, we were only able to add a primitive brake assist to the cart.
Code is designed for a TM4C123GX LaunchPad.
Project in the `hemad/` directory is used to control an H-bridge, which controls the winch that pulls the brakes.
The `usb_dev_serial/` project takes input (NME Sentences) from an Adafruit Ultimate GPS module and forwards the latitude/longitude data over USB.

## Code stolen from:
- [TivaWare](https://www.ti.com/tool/SW-TM4C)
- [Junaidk11](https://github.com/Junaidk11/Adafruit_GPS_Module)
