GCODE files for tuning 3D printers.

The use of another individuals GCODE is done at your own risk! 

To use my PA_tuning_5k.gcode file with Klipper, the [M900.cfg](https://github.com/bobbleheed/Klipper_Configurations/blob/main/Voron%20V2%2C%20300/M900.cfg) must be included within your printer's Klipper config file. This GCODE uses Marlin's Linear Advance test pattern to tune Klipper's Pressure Advance, at minimum, line 56 needs to be edited in order to set extruder and bed temperatures for your filament. The print acceleration used by this test gcode is 5k mm/s². You can create your own GCODE at: https://marlinfw.org/tools/lin_advance/k-factor.html
