# Final-Project-CSN-150 Deauth Detector
Alex Gomez's, Brianna Martinez's, Joshua Morfe's Project of the Deauth Detector

## Purpose
A deauth detector monitors the wireless network for these deauthentication packets and alerts the network administrator or takes action to mitigate the attack, such as blocking the source of the deauthentication packets or automatically re-authenticating disconnected devices. These detectors are commonly used in enterprise or public Wi-Fi environments to enhance network security and ensure uninterrupted connectivity for users.

In a deauthentication attack, an attacker sends deauthentication packets to one or more devices connected to a Wi-Fi network. These packets force the devices to disconnect from the network, disrupting their connectivity. This type of attack can be used for various malicious purposes, such as forcing users to reconnect to a rogue access point controlled by the attacker or causing denial of service (DoS) by disrupting network connectivity.

### Equipment
1. Arduino
2. ESP8266
3. Yourself ofc

#### The Documentation I Followed For This Project

https://github.com/SpacehuhnTech/DeauthDetector

##### Steps To Do

1. Install Arduino
2. Then install the driver for your ES8266 board with this link https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads
3. Click on CP210x Windows Drivers option
4. After you install Arduino and the driver as well you install the ESP8266 SDK
5. To install it, you go to File, Preferences then when it opens, scroll down to you see URL and you paste this https://arduino.esp8266.com/stable/package_esp8266com_index.json
6. After doing that you install it onto Arduino by going to tools and board manager and type in ESP8266 there should be a only option there and when you see ESP8266 install it
7. When its done installing select your board as adafruit feather huzzah esp8266
8. Download this project and open it with Arduino
9. When the file is done extract it, and open the folder deauth_detector file and inside there should be a file, open that file in Arduino
10. By opening the file, click on file, open, and open the file inside the folder of deauth_detector.
11. Then upload your code and it should work

###### Problems I Have Encounter

One of the issue we have encountered was we notice that we was using a ESP32 instead of a ESP8266
Another issue is the board was not connecting to the laptop, how we fix that issue was we install the driver since we notice we forgot to install the driver for the ESP8266 and after we plug it back we saw it worked and connected
