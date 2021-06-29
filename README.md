# AL_1105 machine configuration for LinuxCNC
Last edited: 2021-06-29

**CONFIGURATION NOTES**
- ATTENTION: Please note that these settings may not match your hardware! Do not use any of these parameters or settings unless you know what you are doing. I am not responsible for any malfunctions or damages of your CNC machine!
- All basic configuration is done in AL_1105.hal
- AL1105_postgui.hal contains all connections to the pendand (Logitech F310 USB game controller), some buttons in a keyboard drawer and the pyVCP panel
- Since many functions have multiple input options, AL_1105_postgui.hal is not sorted by input devices but by functions
- HAL components are used with names instead of numbers so that they easily can be identified

**HARDWARE**
- MESA 7i76e Ethernet interface
- Buttons and LEDs in a keyboard drawer connected with a MESA 7i84 via SmartSerial
- Logitech F310 USB game controller as pendant
- Jianken JGL-80 ATC spindle with Omron MX2 inverter connected to PC via Modbus (RS485)
- ColdEND minimum quantity lubrication controlled by LinuxCNC

**DOCUMENTATION**
- Pinout.pdf: Pinout of the MESA 7i76e and all Connectors (just to have all information at one place)
- VFD-Parameter.pdf: Omron MX2 / Hitachi WJ200 parameter set for Jianken JGL-80/2.2R30-20 spindle
- pyVCP_Tab1.png: Screenshot of the first pyVCP panel tab (spindle tab)
- pyVCP_Tab2.png: Screenshot of the second pyVCP panel tab (coordinate system tab)
