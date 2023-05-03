# PocketKerbal
Kerbal Space Program Controller using PocketBeagle

(Soon to be) Home to KerbalController!

This is a personalized Kerbal Space Program console built using a PocketBeagle and kRPC. 

More information can be found on my Hackster Page: https://www.hackster.io/rfn1/pocketkerbal-ksp-console-using-pocketbeagle-krpc-d380ad 

The program you need to use/edit is called Project_1_v2
It is actually intiated using a run program. 
For these files, see https://github.com/rafeisme/ENGI301

Currently this repository houses the PCB files for PocketKerbal. These still need some work, but should be functional. The board is the same size as the actual console, and is designed to be fitted behind it. For the sake of simplicity, some of the unique buttons and switches have been temporarily swapped out for generic ones. 
In total there are:
15 toggle switches
4 buttons
20 resistors
2 joysticks
2 potentiometers
2 led bars
2 leds
1 sliding potentiometer
1 display

A more comprehensive parts list can be found on the Hackster Page. 

NOTE: The "PocketBeagle Device" had not been made when the PCB layout was done, so the example PocketBeagle is included here. Most of the pins are used, so it is likely what would be used regardless.
NOTE: The project guidelines mentioned a 4"x5" maximum size, but in order to fit all of the components and be the size of the console, PocketKerbal is 12" x 6". It could be reduced if it was necessary. 
NOTE: The LCD screen was used as opposed to the SPI screen in my library. https://www.adafruit.com/product/181 

This is still a work in progress and will be updated soon. 
