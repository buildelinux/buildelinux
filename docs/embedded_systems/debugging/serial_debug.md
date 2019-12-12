# BeagleBone Black Debugging

_by Javier Vega | December 12, 2019_

---

## Introduction
As an embedded developer, you always want to know what your microcontroller is doing at any time.
Sometimes it is challenging to know what the board is doing as it boots, unless you have a serial debugger.
The USB-to-serial cable becomes really useful when building a Linux distribution or when there are problems with you Linux distribution.
It helps you find issues or any errors in the kernel as it is booting.
This tutorial, will guide you step-by-step on how to debug the BeagbleBone Black using a serial cable.

## General Steps
1. Connect your USB side of the serial cable to your Host machine.
2. Connect the wires to the J1 header pins of the BeagleBone Black following the table below:

	|    Board    |    Cable    |
	| ----------- | ----------- | 
	| Pin 1 (GND) | Black (GND) |
	| Pin 4 (RX)  |	Green (TX)  |
	| Pin 5 (TX)  |	White (RX)  |

3. Open a Terminal Window and run `ls /dev/tty*` to look for the USB device.
4. 

## Log to a File
~~There are times that is difficult to see the errors on a live Terminal Window because the messages printed too fast.~~
