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
	- [Firmware Update] (#firmware-update)
	- [Kernel Upgrade] (#kernel-upgrade)
- [Configuration] (#configuration)
- [Design Sources] (#design-sources)
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
- [Firmware Update] (#firmware-update)
- [Kernel Upgrade] (#kernel-upgrade)

### Install

#### Android

In order to connect with the Android device, install the accessories branch of the Enabler in the openxc-android project. That branch is currently unavailable, but will be uploaded soon. The .apk is available [here] (https://github.com/openxc/openxc-accessories/tree/master/tools/openxc-enabler-v6.0.6-modem.354.apk).

Be sure Bluetooth is enabled before trying to connect to the Modem. Once the Modem is running the main function, connect to the OpenXC-Modem from the Android device using Bluetooth. The password/pin code is “1234”.

#### Windows

The main method of configuring and setting up the modem will be through USB from the Modem to a Windows PC. A program called Teraterm will be used to interface with the operating system on the device. To allow ease of use, a program called “OpenXC Modem Connect” will be used to automatically configure the connection settings.

#### Note

Using OpenXC Modem Connect is suggested for easier and faster access to the Modem, although you may choose to manually configure TeraTerm to connect to the modem.

Download OpenXC Modem Connect [here] (https://github.com/openxc/openxc-accessories/blob/master/tools/ModemConnect/ModemConnect-v1.0.0.143.msi). Detailed instructions are available [here] (https://github.com/openxc/openxc-accessories/blob/master/tools/ModemConnect/Documents/OpenXC%20Modem%20Connect%20App%20Installation%20Procedure.docx).

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
