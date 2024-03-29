# AL_1105 machine configuration for LinuxCNC
Last edited: 2023-04-11

**CONFIGURATION NOTES**
- ATTENTION: Please note that this configuration has not been written for your machine! Do not use any of these parameters or settings unless you know what you are doing. I am not responsible if you run into trouble!
- All basic configuration is done in AL_1105.hal. AL1105_postgui.hal contains all connections to the peripherals
- Since many functions have multiple input options, AL_1105_postgui.hal is classified by functions
- HAL components are loaded with names instead of numbers so that they easily can be identified
- [easy]probe add-in can be found at https://github.com/hausen8/EasyProbe

**HARDWARE COMPONENTS**
- Sorotec Alu Line 1105
- MESA 7i76e Ethernet interface + 7i84 in keyboard drawer
- Logitech F310 USB game controller as pendant
- Jianken JGL-80 ATC spindle with Omron MX2 inverter connected to PC via Modbus (RS485)
- ColdEND minimum quantity lubrication controlled by LinuxCNC

**DOCUMENTATION**
- Pinout.pdf: Pinout of the MESA 7i76e and all Connectors (just to have all information at one place)
- VFD-Parameter.pdf: Omron MX2 / Hitachi WJ200 parameter set for Jianken JGL-80/2.2R30-20 spindle
- Probe_accuracy.png: Screenshot of repeating accuracy after 6 times probing a 25mm pocket
- pyVCP_Tab1.png: Screenshot of the pyVCP *Spindle* tab
- pyVCP_Tab2.png: Screenshot of the pyVCP *Easy Probe* tab
- pyVCP_Tab3.png: Screenshot of the pyVCP *E-Stop* tab

![tab1](https://github.com/hausen8/AL_1105/blob/2023-04-11/documentation/PyVCP-Tab1.png)

![tab2](https://github.com/hausen8/AL_1105/blob/2023-04-11/documentation/PyVCP-Tab2.png)

![tab3](https://github.com/hausen8/AL_1105/blob/2023-04-11/documentation/PyVCP-Tab3.png)
