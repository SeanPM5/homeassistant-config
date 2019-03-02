# Home Assistant Configuration
[Home Assistant](http://homeassistant.io) configuration files.

* [Hardware](#hardware)
* [Presence Detection](#presence)
* [Automations](#automations)
* [Screenshots](#screenshots)

I will be sharing my Home Assistant configuration here once I become more comfortable using GitHub.

My Home Assistant is Hass.io running on a Raspberry Pi 3B+ with an Aotec Z-Stick.

# Hardware
* System
  * [Raspberry Pi 3 B+](https://www.amazon.com/dp/B07BDR5PDW/)
  * [CanaKit 5V 2.5A Raspberry Pi 3 B+ Power Supply](https://www.amazon.com/CanaKit-Raspberry-Supply-Adapter-Listed/dp/B00MARDJZ4/)
  * [Samsung 64GB 100MB/s (U3) MicroSD](https://www.amazon.com/gp/product/B06XX29S9Q/)
  * [Aeotec Z-Stick Gen5](https://www.amazon.com/Aeotec-Z-Stick-Z-Wave-create-gateway/dp/B00X0AWA6E/)
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

# Presence
Using a bayesian binary sensor with the following services:
* HomeKit
* [HomeAssistant iOS Companion App](https://itunes.apple.com/us/app/home-assistant-companion/id1099568401)
* [Life360 custom_component](https://community.home-assistant.io/t/life360-device-tracker-platform/52406)
* Bluetooth

# Automations
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

# Screenshots
Coming soon.
