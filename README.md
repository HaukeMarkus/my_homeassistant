# homeassistant-config

## My home configuration 
It's already some time ago, that I moved to Homeassistant as my perferred home automation solution away from openhab with absolutely no regrets.

I use homeassistant for controlling shutters, light, garage and the garden irrigation.

## Devices
From a device point of view I started using homematic radio switches and shuttercontrols. As my first hardware was a raspberry pi 3 I used the HM-MOD-RF for it. 
Nowadays I use Shelly devices for doing so which is way less messy, given the fact they are 100% WLAN devices that do not need any special radio appliance.

### SONOFF
For the garden irrigation I have four Hunter valves serving four zones in my garden. The irrgation controlling is being switched by a [SONOFF 4ch pro](https://sonoff.tech/product/diy-smart-switch/4chr3-4chpror3/). As irrigation solution I use @kloggy's  [solution](https://github.com/kloggy/HA-Irrigation-Version2), that I slightly adopted as you can see in my screenshots.

### Shellies in use
- 8 [Shelly 1](https://shelly.cloud/products/shelly-1-smart-home-automation-relay/): as light switches, garage door opener
- 8 [Shelly 2.5](https://shelly.cloud/products/shelly-25-smart-home-automation-relay/): as rollershutter driver for my basement windows
- 2 [Shelly HT](https://shelly.cloud/products/shelly-humidity-temperature-smart-home-automation-sensor/): as temperature sensor


### Lawnmower
I use a Worx Landroid 500E for my garden. The device is controlled [@barma-lej's](https://github.com/Barma-lej/halandroid
)

<br />

![GitHub Watchers][watchers]
![GitHub Stars][stars]
![GitHub Forks][forks]
<br />


![Buy me a coffee](/image/bmc.png "Buy me a coffee MC")



# About

Hi folks, Hauke here from Frankfurt, Germany. This my Home Assistant configuration files. 
Hopefully, this repository can help you get started with Home Assistant and give you some ideas for your own configuration.


## My lovelace set up
Follows screenshots of my lovelace views





[watchers]: https://img.shields.io/github/watchers/haukemarkus/my_homeassistant?style=social
[stars]: https://img.shields.io/github/stars/haukemarkus/my_homeassistant?style=social
[buymeacoffee]: https://www.buymeacoffee.com/deichgraf
