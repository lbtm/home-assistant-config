# Home Assistant Configuration

Here's my [Home Assistant](https://home-assistant.io/) configuration. I have installed HA on an [HP ProLiant MicroServer G7](https://amzn.to/2CXyVs0) with [8GB RAM](https://amzn.to/2TBaAxs) and [240GB SSD](https://amzn.to/2TyWfBR). I am currently running Fedora 29 Server on the MicroServer G7 and used the [alternative-install-on-generic-linux-server](https://www.home-assistant.io/hassio/installation/#alternative-install-on-generic-linux-server) approach to install HA.

My current HA version:  0.84.6


# <a name="menu">Menu</a>
 | [Gateway](#gateway) |


## <a name="hubs">Gateway</a>

| [Go to Menu](#gateway) |

| Device  | Quantity | Connection | Home Assistant | Notes |
| ------------- | :---: | ------------- | ------------- | ------------- |
| [Xiaomi Aqara](http://bit.ly/2CXK3Fu) | 1 | IP | [Xiaomi Aqara](https://www.home-assistant.io/components/xiaomi_aqara/) | For Zigbee sensors|
| [Z-Wave Plus Z-Stick GEN5 - Aeon Labs](https://amzn.to/2TwgrEu) | 1 | USB | [Z-Wave](https://www.home-assistant.io/components/zwave/) | Provides interface to Z-Wave Mesh Network devices|
| [RFXCOM RFXtrx433E](http://bit.ly/2CWB8UH) | 1 | USB | [RFXTRX](https://www.home-assistant.io/components/rfxtrx/) | Enables RX/TX of 433Mhz signals over a range of protocols|


| [Go to Menu](#menu) |


**All files are now being edited with [Atom](https://atom.io/).**

**All of my configuration files are tested against the most stable version of home-assistant using [Travis](https://travis-ci.org/lbtm/home-assistant-config).**


| [Go to Menu](#menu) |
