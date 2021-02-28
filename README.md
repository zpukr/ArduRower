# ArduRower
The project was created on the basis of the ESP32 board (Heletec WiFi Kit 32) for equipping Chinese clones of waterrover (or DIY rowing machines) with a tiny OLED screen and bluetooth interface. The device have emulates the work of the original waterrover S4 equipped with a bluetooth comm module. Tested work with the Coxswain app, which allows to record and export your workouts to garmin connect and/or strava. To connect to your rowing machine, you only need to attach two GND and GPIO2 wires to the RPM sensor (you can add 1kΩ resistor or similar on each wire for protection ESP32 board).

![alt tag](https://raw.githubusercontent.com/zpukr/ArduRower/main/heltec.jpg)
![alt tag](https://raw.githubusercontent.com/zpukr/ArduRower/main/Coxswain.jpg)

Rower side based on sketch **WaterRino**: https://github.com/adruino-io/waterrino

Bluetooth side on sketch **WaterRower S4BL3 Bluetooth BLE for S4**: https://github.com/vibr77/wr_s4bl3_samd
