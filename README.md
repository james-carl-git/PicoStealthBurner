# PicoStealthBurner
Print head control board designed to fit in the mini stealth burner print head. Display, accelerometer and more! This project is a work in progress, future code and hardware revisions expected. 

![Screenshot 2024-01-02 013116](https://github.com/james-carl-git/PicoStealthBurner/assets/78581339/d8298910-f1dc-4790-a2fa-db9e24e1a563)


#Features:
- Runs Klipper on RP2040
- Round LCD Display for custom graphics and stats
- Reduce wires, 2 wires for power and 1 USB cable
- Stepper driver(TWC2209) for extruder
- Inputs for probe, x-stop, extruder temperature sensor
- Hall effect switch for filament runout detection
- 2 part fan outputs
- 1 extruder fan output
- Extruder heater output
- ADXL345 accelerometer for input shaping calibration
- 3 neopixels for voron logo
- neopixel output for part LEDs

![Screenshot 2024-01-02 012836](https://github.com/james-carl-git/PicoStealthBurner/assets/78581339/1134632e-56fe-4059-9b44-1a5c5d6b602b)

![Screenshot 2024-01-02 013027](https://github.com/james-carl-git/PicoStealthBurner/assets/78581339/f6b88fba-6347-4b96-8044-a7924675b536)

#Version History
v0.1 - Initial prototype
v0.2 - Replaced the tiny fan mosfets with SOT-23, swapped out logic-level translator, changed non-standard LDO to SOT-23
