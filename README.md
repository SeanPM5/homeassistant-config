# Home Assistant Configuration

## Overview
[Home Assistant](http://homeassistant.io) configuration files.

I'll be sharing my Home Assistant configuration files here once I finish organizing it and become more comfortable using GitHub (don't want to make any mistakes accidentally uploading sensitive information). At the moment I'm mostly using this to brainstorm future ideas and enhancements on my [issues](https://github.com/SeanPM5/homeassistant-config/issues) page.

My Home Assistant is Hass.io running on a Raspberry Pi 3B+ with an Aotec Z-Stick.

## Hardware
* System
  * [Raspberry Pi 3 B+](https://www.amazon.com/dp/B07BDR5PDW/)
  * [CanaKit 5V 2.5A Raspberry Pi 3 B+ Power Supply](https://www.amazon.com/CanaKit-Raspberry-Supply-Adapter-Listed/dp/B00MARDJZ4/)
  * [Samsung 64GB 100MB/s (U3) MicroSD](https://www.amazon.com/gp/product/B06XX29S9Q/)
  * [Aeotec Z-Stick Gen5](https://www.amazon.com/Aeotec-Z-Stick-Z-Wave-create-gateway/dp/B00X0AWA6E/) for Z-Wave control
* Lights
  * Philips Hue A19 Color Light Bulbs (x5)
  * [Philips Hue Light Strips](https://www.amazon.com/gp/product/B0167H33DU/) (x5)
  * [Philips Hue Motion Sensors](https://www.amazon.com/dp/B076MGK22M/) (x2)
  * Philips Hue Iris
  * [Philips Hue Tap](https://www.amazon.com/Philips-Hue-Batteries-Installation-Free-Exclusively/dp/B079P5H2WG/)
  * [Philips Hue Dimmer](https://www.amazon.com/Philips-Dimmer-Switch-Installation-Free-Exclusively/dp/B076MGKTGS/)
* Voice Assistants
  * Using [Nabu Casa / Home Assistant Cloud](https://www.nabucasa.com/)
  * Google Home mini (x4)
  * Google Home
  * Google Home Hub
  * Google Chromecast (x2)
  * Amazon Echo Dot (x3)
  * Amazon Dash Wand
  * Mounts:
    * [Dot Genie Google Home Mount](https://www.amazon.com/gp/product/B078JNBMDG/)
    * [Dot Genie Outlet Cover Plate Mount for Echo Dot 2nd Gen](https://www.amazon.com/gp/product/B0785FY482/) (x2)
* Switches
  * [Wemo Mini Smart Plug](https://www.amazon.com/gp/product/B01NBI0A6R/)
* Other Hardware
  * Logitech Harmony Ultimate Home Remote (x2)
  * Logitech Harmony Hub (x3)
  * [Withings WS-50 Body Scale](https://www.amazon.com/gp/product/B00BKRQ4E8/)
  * [Withings Sleep bed sensor](https://www.amazon.com/Withings-Nokia-Sleep-Temperature-Compatible/dp/B078Z1B34S)
  * [Automatic Classic Car OBD II Adapter](https://www.amazon.com/Automatic-Connected-Realtime-Diagnostics-Detection/dp/B01JRBQ9PC/)
  * [iBeacons](https://www.amazon.com/gp/product/B019G0VVZC/) (x5)
  * Door sensors

## Presence
Using a bayesian binary sensor with the following services:
* [HomeKit](https://www.home-assistant.io/components/homekit/)
* [HomeAssistant iOS Companion App](https://itunes.apple.com/us/app/home-assistant-companion/id1099568401)
* [Life360 custom_component](https://community.home-assistant.io/t/life360-device-tracker-platform/52406)
* [Geofency](https://www.home-assistant.io/components/geofency/)
* Bluetooth

## Automations
* IFTTT Integration
  * Withings weigh-in reminders
* Lights
  * Night Light - Kitchen on motion
* Media
  * Dim lights when Plex starts playing
* Notifications
  * Greetings on Google Home TTS when entering home
  * Notify of new Spotify personalized playlists on Monday and Fridays
  * Alert when at home but not connected to Wi-Fi
* House Modes
  * Guest mode that disables many automations
  * Cleaning mode that sets lights to max brightness and disables motion sensors (among other things)
  * Shower mode that plays radio while in shower
  * Exercise mode that starts the fan and a Spotify workout playlist with a 30 min timer

## Aspirations
These are some of the high level goals that I try to keep in mind with my setup.
* Minimize user interaction as much as possible. The best automations are ones you don't even think about.  
* User interface - I strive to keep a good balance between "minimal" and "powerful" UI by making extensive use of [Lovelace conditional cards](https://www.home-assistant.io/lovelace/conditional/). Everything should be accessible in 3 clicks or less, with as little scrolling as possible. Mobile UI is very important too. 
* Hardware - Always prefer local devices when possible.
* Backups - I cannot stress enough how important it is to maintain backups. SD cards can and will fail, and you don't want to lose all your hard work (I learned that the hard way). Connect your HA system to a UPS too, they are cheap now. 

## Screenshots
Coming soon.

## Documentation
I hope to provide extensive documentation both as readme files in every directory and at the [wiki](https://github.com/SeanPM5/homeassistant-config/wiki). If you have a question about my setup you can open an issue or hit me up on the Home Assistant Discord server - my username there is __Sean__#2149. 
