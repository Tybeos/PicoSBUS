# SBUS driver for Raspberry pi pico (RP2040)
a Micropython driver for the SBUS protocol

Based on https://github.com/Sokrates80/sbus_driver_micropython

It supports 16 standard Channels plus 2 digitals.

It has been tested only on the below FrSky receiver:
- Archer R8 Pro

An example of usage can be found in the file example.py

The signal does not have to be inverted, this module can invert the signal itself

It is recommend putting a 1K ohm resistor between the receiver and the connected pin

To run the example you have to connect the sbus receiver signal pin to the pico board pin 9 (UART 1)


