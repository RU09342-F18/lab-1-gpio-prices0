# Author: Shane Price
# Written: 09/20/18
# Last Updated 09/20/18 2105

# Summary
The task of this part of the lab was to have multiple LEDs turn blink at different intervals using the MSP430G2553, but by taking the chip off the development board and creating your own reset circuit. 
## General Functionality
The ".c" file demonstrates how to have multiple LEDs blink on in different intervals. This was done by using the same code from "Lab1_MultiBlink_MSP430G2553" ".c" file. To do this correctly, the input voltage has to be taken into account in order to not blow the chip, size resistors for the LEDs, and using the datasheet to make a proper reset circuit.
## Input/Output
Input: toggle switch
Output: 2 red LEDs

