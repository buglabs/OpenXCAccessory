OpenXC Accessories_images/logo.png
Version:	0.0.1
Web:	http://openxcplatform.com
Documentation:	http://accessories.openxcplatform.com
Source:	http://github.com/openxc/openxc-accessories
The OpenXC Accessories are a line of hardware accessories intended to augment the Vehicle Interface (VI) and communicate with other entities. The benefit of the Accessory Platform is that all accessories share a common base (or motherboard) and new features are added by modifying or designing a new daughter card (mPCIe connector).

The base board contains an Atmel SAMA5 (Cortex-A5) running embedded Linux. All accessory functions are coded in Python. Interfaces include SD card slot, Bluetooth Classic, Bluetooth Low Energy (a.k.a Bluetooth Smart), USB OTG. WiFi is currently being enabled. A debug serial port is available.

The first in the line of accessories is a 3G Modem to enable sharing of vehicle data directly with the cloud, OTA updates to the Modem configuration, and still allows use of the Enabler app.

**Table of Contents**
- [Getting Started] (#getting-started)
	- [Install] (#install)
	- [Directory Structure] (#directory-structure)
	- [Scripts] (#scripts)
	- [Firmware Update] (#firmware update)
	- [Kernel Upgrade] (#kernel upgrade)
- [Configuration] (#configuration)
- [Design Sources] (#design_sources)
  - [Electrical] (#electrical)
	- [Mechanical] (#mechanical)
  - [Assembly] (#assembly)
- [License Disclosure] (#license)

## Getting Started

The device comes preloaded with the kernel and firmware for operation. Before using the first time use, please charge the Modem for at least 15 minutes with a micro-USB cable. A full battery will last approximately 8-10 hours during operation.

To turn on, press the button on the side of the device once until the LED lights stay on. If there are no lights emitting from the device, ensure that the device is charged.

Once the device is on, the device will automatically proceed with the auto start script, which initiates the connection and data communication with a VI and Android Device.

The following sections describe the next steps.

- [Install] (#install)
- [Directory Structure] (#directory-structure)
- [Scripts] (#scripts)
- [Firmware Update] (#firmware update)
- [Kernel Upgrade] (#kernel upgrade)e

### Install


### Directory Structure


### Scripts


### Firmware Update


### Kernel Upgrade


## Configuration


## Design Sources


### Electrical



### Mechanical



### Assembly



## License
Copyright (c) 2015 Ford Motor Company

Licensed under the BSD license.

This software depends on other open source projects, and a binary distribution may contain code covered by other licenses.
