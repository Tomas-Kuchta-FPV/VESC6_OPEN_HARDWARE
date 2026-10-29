# VESC6_OPEN_HARDWARE
> WiP Stage: Designed (asked for funding)  
Open source powerfull VESC that has 2 channels and it's based on the VESC 6 schematic.  

## Design
* 2 channels connected through CAN
* 4 layered PCB
* Continuous current: 70A per ch; instantaneous current: 120A (With proper heat sinking)
* STL130N6F7 MOSFETs rated to switch up to 130A, software limits it to 120A.
* Voltage: 10V-60V(Cells: 3-13S)
* Ports: USB-C, CAN x2, ADC, on/off switch, SWD, Hall Sensors
* LSM6DS3 IMU
* JST-SH connectors (6pin and 4 pin)
* Holes either side of the MOSFETs allow for even clamping of a simple rectangular heatsink.

Possible future upgrades with built in ESP for VESC express.  

## Manufacture
* Commonly usable and easy to source components so you can either have JLCPCB make it for you or assemble it youself.
* Custom board software build as well as hardware configuration files are available in the software folder.
  * Further testing required once I assemble it

![image](/Images/top.png "top")  
![image](/Images/isometric.png "isometric")  

## Credits
https://github.com/craigg96/VESC6_OPEN_HARDWARE  

## Motivation
So I love hoverboard motors, but it turns up that a lot of the ESCs are not compatible with the custom FW. And at the end of summer holidays I've designed Hover Cruiser. It's an electric skateboard made out of hoverboard motors. And also my brother made his own gocart powered by hoverboard motors. So thats why I made this modification for 2 channels.  
![image](https://github.com/Tomas-Kuchta-FPV/HoverCruiser/raw/main/Electronics%20diagram.drawio.png "HoverCruiser Electronics")  
![image](https://github.com/Tomas-Kuchta-FPV/HoverCruiser/raw/main/Images/BoardIso.png "HoverCruiser")  

## BOM
| Item                       | Price          |
| -------------------------- | -------------- |
| LCSC                       | $114.67        |
| LCSC Shipping              | $13.24         |
| LCSC Tarif                 | $38.85         |
| JLCPCB                     | $38.42         |
| JLCPCB Shipping            | $11.86         |
| JLCPCB tarif               | $21.76         |
| Assembly & other materials | Freeeee labor! |
| Total                      | $238.80        |
