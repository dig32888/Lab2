This file implements functions that assign pins as inputs and outputs, as well as reads and writes the pins. To accomplish this, the main driver depends on the files GPIO_Driver.h and GPIO_Driver.c. 
GPIO_Driver.h "states" or lists out all of the functions
GPIO_Driver.c defines all of the functions
Using these to files, the main file includes their information and in a much more concise manner, causes the red LED to toggle on and off
