# RAPIRO_Fork1
Modify Rapiro Firmware to fit the Arduino RAM

This is for the evaluation purpose only, As against the 'Low memory available, stability problems may occur'.

[Problem]
A warning shows blow messages when I try to Arduino compile the Original firmware 'RAPIRO_ver0_0.ino'.

[Warning]
Sketch uses 10,512 bytes (32%) of program storage space. Maximum is 32,256 bytes.
Global variables use 1,744 bytes (85%) of dynamic memory, leaving 304 bytes for local variables. Maximum is 2,048 bytes.
Low memory available, stability problems may occur.

[Solution]
This is sorry but this source, Arudino sketch, reduced the Rapiro's motion and reduce the global memory to make enough local memory spaces.
