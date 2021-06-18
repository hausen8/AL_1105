# AL_1105 machine configuration for LinuxCNC using a Mesa 7i76e and 7i84

- All basic configuration is done in AL_1105.hal
- AL1105_postgui.hal contains all connections to a pendand (Logitech F310 game controller), some buttons in the keyboard drawer and the PyVCP panel
- Since many functions have more than one input, AL_1105_postgui.hal is not sorted by input devices but by functions
- HAL components are used with names instead of numbers so that they easily can be identified
