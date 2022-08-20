# ETH008-hc3
Fibaro HC3 QuickApp for controlling ETH008 relay board.
This plugin will connect directly from the HC3 to the ETH008 device over TCP/IP.

- ETH008 product: https://www.robot-electronics.co.uk/files/eth008b.pdf
- Fibaro HC3 product: https://www.fibaro.com/nl/products/home-center-3/

The QuickApp will automatically create 8 binary switch devices. Each one represent 1 relay contact.

## Installation
Access the web interface of the Fibaro HC3 and go to setting and then devices.
Add a new device as shown in the picture below and upload the QuickApp. Use the required file "ETH008Core.fqa".

<img src="https://github.com/EggensEng/ETH008-hc3/blob/main/images/Upload.png?raw=true">

## Configuration
After installation the following settings need to be set:
- "TCP_IP" - IP address of the ETH008
- "TCP_Port" - Port number of the ETH008
- "TCP_Password" - Password to access the ETH008 (if required)
- "PulseTime_100ms" - Pulse time for the contacts. Pulse time is per 100ms. So a value of 10 will give a pulse time of 1 second.

Below 2 images will show how to edit the required variables and set them to the correct value:

<img src="https://github.com/EggensEng/ETH008-hc3/blob/main/images/SetSettings.png?raw=true">

<img src="https://github.com/EggensEng/ETH008-hc3/blob/main/images/SetIp.png?raw=true">

Check status to see if connection could be established:

<img src="https://github.com/EggensEng/ETH008-hc3/blob/main/images/DeviceStatus.png?raw=true">
