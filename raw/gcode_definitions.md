For context, I have provided example commands for a 3d printer.
M104 S205 sets nozzle temperature to 205 degrees Celsius
G28 homes all axes
G1 Z5 F5000 moves the Z axis up 5mm at a speed of 5000mm/min
M109 S200 sets bed temperature to 200 degrees Celsius
G21 sets all units to millimeters
G90 uses absolute coordinates
M82 uses absolute distance for extrusion
G92 E0 sets extrusion to 0
M107 turns off the fan
M106 S255 turns on the fan at full speed. S128 would turn it on at half speed
G1 X90 Y90 F7800 moves the print head in X and Y to 90mm at a speed of 7800mm/min
G1 E2 F2400 extrudes 2mm of filament at a speed of 2400mm/min
G1 F1800 sets the feedrate to 1800mm/min