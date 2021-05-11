# Configuration 
> Simple yet functional, lovelace design based on work of several really cool guys!

- [**`Frenck`**](https://github.com/frenck)
- [**`Kloggy`**](https://github.com/kloggy)
- [**`Kolja`**](https://github.com/KoljaWindeler)
- [**`Barma-lej`**](https://github.com/Barma-lej)


It's already some time ago, that I moved to Homeassistant as my perferred home automation solution away from [openhab](http://openhab.org) with absolutely no regrets.

I use homeassistant for controlling shutters, light, garage and the garden irrigation.

## Devices
From a device point of view I started using homematic radio switches and shuttercontrols. As my first hardware was a raspberry pi 3 I used the HM-MOD-RF for it.
Nowadays I use Shelly devices for doing so which is way less messy, given the fact they are 100% WLAN devices that do not need any special radio appliance.


### SONOFF
For the garden irrigation I have four [Hunter valves](https://www.hunterindustries.com/irrigation-product/valves/pgv) serving four zones in my garden. The irrgation control is a 4-switch-device [SONOFF 4ch pro](https://sonoff.tech/product/diy-smart-switch/4chr3-4chpror3/). The homeautomation approach is [Kloggy's solution](https://github.com/kloggy/HA-Irrigation-Version2), that I slightly adopted as you can see in my screenshots.


### Shellies
I have 18 shelly devices:
- **8** [Shelly 1](https://shelly.cloud/products/shelly-1-smart-home-automation-relay/): as light switches, garage door opener
- **8** [Shelly 2.5](https://shelly.cloud/products/shelly-25-smart-home-automation-relay/): as rollershutter driver for my basement windows
- **2** [Shelly HT](https://shelly.cloud/products/shelly-humidity-temperature-smart-home-automation-sensor/): as temperature sensor


### Lawnmower
I use a Worx Landroid 500E for my garden. 
The design is from 
- [**`ha landroid`**](https://github.com/Barma-lej/halandroid)
which I just translated into German.

## My lovelace set up
Follows screenshots of my lovelace views:
1. My irrigation system

![Irrigation system][irrigation-shield]

2. My Landroid Mower - first view

![Mower basic][mower_1-shield]

3. My Landroid Mower - second view

![Mower extended][mower_2-shield]

4. Another look with same components

![Other look][samestuff-shield]

5. My waste calendar solution based on [Kolja Windelers ICS](https://github.com/KoljaWindeler/ics)

![Wastecal][waste-shield]

## About
This is Hauke from Frankfurt, Germany and you're looking at my Home Assistant configuration files. Feel free to use it and look how I managed to do it.
Hopefully, this repository can help you get started with Home Assistant and give you some ideas for your own configuration.

## Some stats...
![GitHub Watchers][watchers]
![GitHub Stars][stars]

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

[watchers]: https://img.shields.io/github/watchers/haukemarkus/my_homeassistant?style=social
[stars]: https://img.shields.io/github/stars/haukemarkus/my_homeassistant?style=social
[buymeacoffee]: https://www.buymeacoffee.com/deichgraf
[buymeacoffee-shield]: /image/bmc.png

[mower_1-shield]: /image/mower.png
[mower_2-shield]: /image/mower2.png
[samestuff-shield]: /image/samestuffotherlook.png
[waste-shield]: /image/waste.png
[irrigation-shield]: /image/irrigation.png
