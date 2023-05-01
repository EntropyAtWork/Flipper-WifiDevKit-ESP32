## Guide for ESP32 board for the Flipper Zero 


This module was made with the NodeMcu ESP32-Wroom-32 dev Lua 38Pin development kit, mostly because that was the one that was available in my region, but most ESP32 modules should be fine.

![](/4.Docs/Images/FlipperZeroPinout.png)
![](/4.Docs/Images/doc-esp32-wroom-pinout.png.webp)


#Pin connections 
| ESP32-Wroom-32 | Flipper Zero|
|----------------|-----------------------------|
| 3V3            | 9/3V3|  
| G0/Touch_1     | 10/SWC|
| GND            | 11/GND|
| G2/Touch_2     | 12/SIO|
| RXD            | 13/TX |
| TXD            | 14/RX |
| G25/DAC_1      | 15/C1 |
| G26/DAC_2      | 16/C0 |
 
**
