# Author: Shane Price
# Written: 09/20/18
# Last Updated 09/20/18 1140

# Summary
The task of this part of the lab was to have an LED toggle on and off with 50% duty cylce on two seperate MSP microcontroller boards. 
## General Functionality
There are two ".c" files demonstrating how to have a simple blink of an LED on an MSP430G2553 and an MSP430FR2311. The time between the blinks are made by using "__delay_cycles(*frequency*)" this command works on both boards. To have the LED blink on and off every second the frequency should be 1MHz. The 50% duty cylce means time on and off are equal, this code meets that requirement by having it on for 0.5 seconds and off for 0.5 seconds.
