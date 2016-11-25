Marlin Firmware adjusted for eShapeOko/RAMPS
============================================

This is a personal fork of the original [Marlin](https://github.com/MarlinFirmware/Marlin) firmware, extended and configured to work with the eShapeOko router (with enlarged working area):

- Usable work space: 32 cm x 80 cm
- Second Y axis motor is driven by the E2 stepper driver (reverse direction)
- 20x2 LCD display enabled
- RAMPS stepper shield
- SD card reader enabled
- min+max endstops, always enabled, Y endstops with special logic circuit
- Servo output (PWM) used to control spindle speed (M3/M5 op codes)
