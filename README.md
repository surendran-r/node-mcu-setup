# node-mcu-setup
Setup Instructions for node-mcu on mac

1. Download the CP2012 driver from http://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers
2. Download the esptool.py for flashing custom firmware from https://github.com/nodemcu/nodemcu-firmware/tree/master/tools 
3. To use Arduino IDE for coding NodeMCU we need to make sure we have the nodeMCU board added to the IDE
4. Add this link http://arduino.esp8266.com/stable/package_esp8266com_index.json to the IDE setting's "Additional Board Manager URL"
5. Open the "Board Manager" in the IDE and add the ESP8266 board
6. Make sure to select the board as "NodeMCU 0.9" and the proper port



