# Bottle Lights

Run bottle lights directly from an ESP8266 device, powered by ESPHome
<img src="https://github.com/grayfrost90/bottle-lights/assets/84717239/ef0a3013-d26a-4444-8046-87d155b039e1" width=50% height=50%>

## Build Instructions

1. Open [https://grayfrost90.github.io/bottle-lights/](https://grayfrost90.github.io/bottle-lights/)
2. Plug in ESP control box device
3. Click the connect button
4. Pick the serial device from the list
5. The installer should now connect to the device and install the firmware

## Setup Instructions

1. Connect the ESP control box to the bottle lights and a power source
2. The installer should take you through the WiFi setup, if not do the following:
   1. Once booted, look for a WiFi network called "Bottle-Lights-xxxxxx" and connect to it
   2. This will open a captive portal page to configure the WiFi. If it doesn't connect, browse to [http://192.168.4.1](http://192.168.4.1)
   3. Enter the WiFi details and save, the ESP will now reboot and should connect to your WiFi

## Home Assistant Setup

1. Once the device has connected to your WiFi it should appear in the intergration page of your Home Assitant site
   
   [![Open your Home Assistant instance and show your integrations.](https://my.home-assistant.io/badges/integrations.svg)](https://my.home-assistant.io/redirect/integrations/)
3. You should now see this in your integrations

## ESPHome Adoption

1. If you have ESPHome installed, you can adopt the device to keep it updated
2. This should appear for adoption if your ESPHome setup and ESP device are on the same VLAN
3. If you don't have ESPHome click the following link to browse for and install the add-on
   
   [![Open your Home Assistant instance and show the add-on store.](https://my.home-assistant.io/badges/supervisor_store.svg)](https://my.home-assistant.io/redirect/supervisor_store/)

Enjoy!
