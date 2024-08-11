# Home Assistant Wall/deck panel

This project uses [ESPHome](https://esphome.io) and [LVGL library](https://lvgl.io).

<img src="https://community-assets.home-assistant.io/original/4X/1/3/3/1339b489be02221adcba378b4462c97992f19f59.jpeg" />

<img src="https://community-assets.home-assistant.io/original/4X/f/9/7/f975f971d55742fceda674031b30953f017fb104.jpeg" />


Hardware: Guition 480x480 ESP32-4848S040 

<a href="https://www.aliexpress.com/item/1005006622809642.html">Link AliExpress</a>


Features:

Page 1 (Home & Clock):
- Date & Time synced from Home Assistant settings
- Weather Condition & Temperature synced from Home Assistant with weather Icons MaterialDesign
- House temperature. A sensor that groups and average the temperature of the rooms thermometers set on HA
- Light switch (button) and slider to control a dimmable light via HA

Page2 (Heating Controls)
- Trigger the automations to turn on/off the boiler and areas of the house
- Control of the thermostat (+ or -) and sync with the value set on HA.

General
- Status of connection with HA Top/right icon 
- Boot page with HA logo and spinner
- Screen backlight timer. On touch 100% > 30s > 50% > 15min > 35% > 15min > off 0% > LCD antiburn on (snow animation)
