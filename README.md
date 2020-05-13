# MINI-CNC
Implemented a mini CNC plotter using Arduino Uno.
This plotter draws diagrams which are given as an input via computer.
At first, the user uses Inkscape- a vector graphics editor to convert the diagram to be printed by the CNC plotter to G-code format.
After saving the required figure as G-code the inkscape application is closed and hardware is connected to the PC via USB and then a software called Processing was used.
Gctrl is code that is meant to run on the software Processing.The GCtrl provides control options for jogging and sending Gcode.
This is sent to the microcontroller to control rotation of stepper motors according Gcode.
