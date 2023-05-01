#Marauder Setup

Firstly install this driver so that the module will be recognized by the pc(https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads)

* From https://github.com/justcallmekoko/ESP32Marauder/releases/ , download the latest version of maruader(esp32_maruader_flipper_sd_seriel).

* From  https://github.com/justcallmekoko/ESP32Marauder/wiki/update-firmware , your gonna want to get the Bootloader, Partitions and Boot App for the Flipper zero wifi Dev Board.
It should be looking something like this:

|                | Flipper Zero WiFi Dev Board |
|----------------|-----------------------------|
| Bootloader     |  0X1000                     |  
| Partitions     |  0X8000                     |
| Boot App       |  0XE000                     |
| Firmware       | 0X10000                     | 


Next 
* Next your gonna need to flash these to the ESP-32, this is done through this site(https://esp.huhn.me/) , with the Arduino IDE(https://www.arduino.cc/en/software) or with the program from this repository(https://github.com/martinloren/HScope) .

**If you use the web tool(https://esp.huhn.me/) , these are the steps to flash the device** 
    



**If you use the arduino IDE(https://www.arduino.cc/en/software) , these are the steps to flash device(Note that there are different steps for v1 and v2 of the IDE, but this will cover the steps for Arduino IDE V2.0)**



# If you use the tools from (https://github.com/martinloren/HScope) 

![](/4.Docs/Images/FlashTool.png)
