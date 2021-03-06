# ArduRower
The project was created on the basis of the ESP32 board (Heletec WiFi Kit 32 - cheap ESP32 board with OLED & LiPo battery interface) for equipping chinese clones of waterrover like Incline/XtremepowerUS (or DIY rowing machines) with a tiny OLED screen and bluetooth interface. The device have emulates the work of the original waterrover S4 equipped with a bluetooth comm module. Tested work with the Coxswain and Kinomap app, which allows to record and export your workouts to garmin connect and/or strava. To connect to your rowing machine, you only need to attach two GND and GPIO2 wires to the RPM sensor (you can add 1kΩ resistor or similar on each wire for protection ESP32 board). You can also connect the battery to GPIO33 through a divider of two resistors: 220k resistance connects to + of LiPo battery and GPIO33, 33k resistance to GND and GPIO33

![alt tag](https://raw.githubusercontent.com/zpukr/ArduRower/main/heltec.jpg)
![alt tag](https://raw.githubusercontent.com/zpukr/ArduRower/main/Coxswain.jpg)
![alt tag](https://raw.githubusercontent.com/zpukr/ArduRower/main/kinomap.jpg)

Rower side based on sketch **WaterRino**: https://github.com/adruino-io/waterrino
Bluetooth side on sketch **WaterRower S4BL3 Bluetooth BLE for S4**: https://github.com/vibr77/wr_s4bl3_samd
