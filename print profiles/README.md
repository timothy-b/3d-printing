# print profiles

## Manual setup

### PID Tuning:

https://all3dp.com/2/3d-printer-pid-tuning/
https://marlinfw.org/docs/gcode/M303.html

// M503 - Read EEPROM

// start tuning at 225°
M303 E0 S225 C5

// Save new values
M301 P I D

// Save to EEPROM
M500

### Min extrusion temp

// Set min unload extrusion temp
M302 S200

// Save EEPROM
M500
