# SmartCube

The SmartCube is based on the <a href="https://docs.m5stack.com/en/core/Core2%20v1.1">M5 Stack Core 2 v1.1</a> and sits on the dashboard of our van Alfred (2021 Fiat Ducato). It gives us all the informations we need while driving with it. It is based on <a href="https://esphome.io/">ESPHome</a> and connected to our <a href="https://www.home-assistant.io/">Home Assistant</a> in the van.

<img width="400" alt="SmartCube" src="https://github.com/Naaf3/SmartCube/blob/main/preview/smartcube.jpg"/>

## Introduction

The SmartCube is a project based on the Bento by Smarty Van:

### 📺 Watch the [YouTube video](https://www.youtube.com/watch?v=Z0hs0G1mfqU) about this project:
[<img width="350" alt="Smarty Van YouTube video" src="https://img.youtube.com/vi/Z0hs0G1mfqU/maxresdefault.jpg"/>](https://www.youtube.com/watch?v=Z0hs0G1mfqU)

So please check out the video and the informations about it at Smarty Van's.

## Differences between Bento and SmartCube

I did some changes so the SmartCube serves our needs:
- Added some buttons for alarms and lights on the second page
- Added a page (third page) to show our van tilt sensor and make parking easier 😉
- Removed some features like opening valve by tilting the device


## Pages

### Overview Page

<img width="400" alt="Overview Page" src="https://github.com/Naaf3/SmartCube/blob/main/preview/overview_page.jpg"/>

The overview page shows informations about:
- the freshwater level provided by the Mopeka Pro200 <a href="https://mopeka.com/consumer-solutions/">(for more infos visit the Mopeka homepage)</a>
- the level in our toilet cassette by Mopeka Pro Check <a href="https://mopeka.com/consumer-solutions/">(for more infos visit the Mopeka homepage)</a>
- SoC of our leisure battery by the Victron Smart Shunt <a href="https://www.victronenergy.de/battery-monitors/smart-battery-shunt">(for more infos visit the Victron homepage)</a>
- the level of our diesel tank by MeatPi WiCan Pro <a href="https://www.meatpi.com/products/wican-pro">(for more infos visit the MeatPi homepage)</a>
- the level of our AdBlue/DEF tank by MeatPi WiCan Pro <a href="https://www.meatpi.com/products/wican-pro">(for more infos visit the MeatPi homepage)</a>
- the power level of the starter battery by the Victron Smart Shunt <a href="https://www.victronenergy.de/battery-monitors/smart-battery-shunt">(for more infos visit the Victron homepage)</a>

### Controls Page

<img width="400" alt="Controls Page" src="https://github.com/Naaf3/SmartCube/blob/main/preview/controls_page.jpg"/>

The Controls Page shows four buttons:
- "Ida im Auto": Switching on/off an automation that sends us messages every 5 minutes about the temperature in our van, when our dog Ida has to stay there i.e. for grocery shopping
- "Alarmanlage": Car alarm based on Home Assistant
- "Skyroof": Ambient light in the front of the van controlled by a Shelly RGBW <a href="https://www.shelly.com/de/blogs/documentation/shelly-rgbw-2-device-smart-control">(for more infos visit the Shelly homepage)</a>
- "Bett": Ambient light in the sleeping area controlled by a Shelly RGBW <a href="https://www.shelly.com/de/blogs/documentation/shelly-rgbw-2-device-smart-control">(for more infos visit the Shelly homepage)</a>

### Van Tilt Page

<img width="400" alt="Van Tilt Page" src="https://github.com/Naaf3/SmartCube/blob/main/preview/vantilt_page.jpg"/>

The page shows one image of the side of the van and one of the back to visualize how the van is tilted. The van tilt sensor is based on a ESP32 combined with a MPU6050 Accelerometer: <a href="https://van-automation.com/adding_van_tilt_sensor/">Adding a Van Tilt Sensor</a>

I wanted it to look like the custom card in Home Assistant that we have. I took me some hours, but it's working now. 😊

### Water Filling Page

<img width="400" alt="Water Filling Page" src="https://github.com/Naaf3/SmartCube/blob/main/preview/water_filling_page.jpg"/>

Just the water arc to help filling up the water tank. The page can easily be activated by turning the SmartCube. With the magnets it can easily be attached to the van near the water intake.  
<br>
<br>
<br>
### Please note that there are still code snippets or functions in the yaml-file that are not fully reviewed or adapted to my needs.  
<br>
<br>

If you like my work and want to support me:

<a href="https://www.paypal.com/donate/?hosted_button_id=H9TBKLCDM8J2J">
  <img src="https://github.com/Naaf3/Introduction/blob/main/images/donate_button.png" width="300" alt="Donate with PayPal" />
</a>
