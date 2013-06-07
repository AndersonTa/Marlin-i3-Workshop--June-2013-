Marlin-i3-Workshop--June-2013-
==============================

Marlin i3 Workshop June 2013

Configured for Melzi Electronics, 63

100K Thermistor
GT2 Belting
GT2 20 tooth belting
MakerGear Hot end, 0.35mm orifice for 3mm filament
Hobbed drive gear from Prusa (340 E Step in firmware)
M5 0.8mm pitch Z

What you need to do after downloading the ZIP

1. Unzip the entire folder
2. Go to slic3r.org and download the appropriate option for your operating system
3. Search for "FTDI Driver" and download the appropriate driver for your operating system
4. Go to arduino.cc and download the Arduino IDE for your operating system
5. Take the "Mighty1284P____" folder and add it to the Arduino hardware folder
6. Open arduino, open the Marlin.ino file inside the Marlin(IDA) folder
7. Go to tools, select board, Mighty1284P Optiboot is the option you want selected
8. Select the proper port
9. Upload to board
10. Go into the PrintRun directory and copy the appropriate PrintRun for your operating system
11. Open "pronterface" inside that directory
12. Select proper port and baudrate (250000)
13. Open slicer and load the Prusa(i3) config in the main directory
14. Load TestCube.stl found in the main directory
15. Slice, export gcode
16. Load newly generated gcode into Pronterface
17. Set temps, extruder to 190C, bed to 60C
18. Wait for temps to set
19. Hit Print!
20. Freak the fuck out!