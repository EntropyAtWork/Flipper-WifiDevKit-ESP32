## Guide for ESP32 board for the Flipper Zero 


This WifiDev kit was made with the NodeMcu ESP32-Wroom-32 dev Lua 38Pin development kit, mostly because that was the one that was available in my region, but most ESP32 modules should be fine.

# Pin connections 
| ESP32-Wroom-32  | Flipper Zero|
|-----------------|-------------|
| 3V3             | Pin 9 (3V3) |  
| GPIO 0 (Touch_1)| Pin 10 (SWC)|
| GND             | Pin 11 (GND)|
| GPIO 2 (Touch_2)| Pin 12 (SIO)|
| RXD             | Pin 13 (TX) |
| TXD             | Pin 14 (RX) |
| GPIO 25  (DAC_1)| Pin 15 (C1) |
| GPIO 26  (DAC_2)| Pin 16 (C0) |

Following the table above i soldered the Pins from the ESP-32 module to the according pins that would later go into the Flipper Zero, 
Note that i added a second set of connection pins, to have it sit more stable on the Flipper Zero.


# This is what my board looked like after soldering.
![](/4.Docs/Images/ModuleFrontView.jpg)
**I chose to hot glue the back to prevent any wires from touching as it got a little packed.**
![](/4.Docs/Images/ModuleBackView.jpg)



## Reference pics of Pinout from the Flipper Zero website and one for my ESP32-Wroom-32 dev board.

![](/4.Docs/Images/FlipperZeroPinout.png)
![](/4.Docs/Images/doc-esp32-wroom-pinout.png.webp)

