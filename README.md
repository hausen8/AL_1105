# AL_1105 machine configuration for LinuxCNC

**CONFIGURATION NOTES**
- All basic configuration is done in AL_1105.hal
- AL1105_postgui.hal contains all connections to a pendand (Logitech F310 game controller), some buttons in the keyboard drawer and the PyVCP panel
- Since many functions have multiple input options, AL_1105_postgui.hal is not sorted by input devices but by functions
- HAL components are used with names instead of numbers so that they easily can be identified

**HARDWARE NOTES**
- MESA 7i76e Ethernet interface
- Buttons and LEDs in a keyboard drawer connected with a MESA 7i84 via SmartSerial
- Logitech F310 USB game controller as pendant
- Jianken JGL-80 ATC spindle with Omron MX2 inverter connected to PC via Modbus (RS485)
- ColdEND minimum quantity lubrication controlled by LinuxCNC
