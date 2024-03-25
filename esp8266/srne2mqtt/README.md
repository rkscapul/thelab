# SRNE2MQTT
### Disclaimer
This project is from another project that achives the same purpose. For more information, check out [SRNE Solar Charge Controller Monitor by Cole888 on GitHub](https://github.com/cole8888/SRNE-Solar-Charge-Controller-Monitor).

### Original description
Read data from SRNE solar charge controllers via modbus over RS232.

This repository contains several example programs for reading data from SRNE solar charge controllers using Raspberry Pi, ESP32, ESP8266 and Arduino Nano / Uno.

Based on the modbus manuals, this should also work with some Renogy controllers, but I don't have one to test with. Also, verify the wiring is compatible with your controller.

### How I use this project
Currently I use the ESP8266 version of the project and the data is processed through Home Assistant via MQTT.

### Hardware
* NodeMCU ESP8266 (Will be testing on a Wemos D1 Mini to reduce the physical size of the MCU).
* MAX3232 Module.
* RJ12 Cable.