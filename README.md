# MarstekMonitor

Small device with integrated display to monitor Marstek Venus battery systems.

Works on the 5.12kWh and 2.56kWh Marstek Venus battery.

Thanks to Superduper1969 and Tweakers (in Dutch) for EPSHome config and Modbus communication.

https://gathering.tweakers.net/forum/list_messages/2282240/0

## Main features
-Plugs directly into the RS485 port on the side of the battery

-Display shows:

Battery Operating Mode (Idle, Charge, Discharge)

Charge/Discharge power

Battery SoC (State of Charge)

Charging Strategy (Auto, AI, Custom)

-No separate power supply needed

-(optional) Can be connected to WiFi to monitor/control the battery remotely (eg. Home Assisstant)

## HW V0.1
HW v0.1 is meant to be a proof of concept only. It consists of nothing more than a carrier board for the various modules.

Partlist:
1. MarstekMonitor v0.1
2. LilyGo ESP32 T-Display v1.1 [link](https://www.tinytronics.nl/en/development-boards/microcontroller-boards/with-wi-fi/lilygo-ttgo-t-display-v1.1-esp32-with-1.14-inch-tft-display "Webshop").
3. Buck-Boost converter [link](https://www.tinytronics.nl/en/power/voltage-converters/buck-boost-(step-up-down)-converters/dc-dc-step-up-down-buck-boost-converter-0.6a-5v-output "Webshop").
4. RS485-Serial module <link>.
5. 3d Printed enclosure (TODO)
6. Weipu RS485 connector

