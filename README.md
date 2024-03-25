# Fake-Access-Point-Using-ESP8266-NodeMCU

## Overview
This repository contains the code and documentation for creating a fake Wi-Fi access point using the ESP8266 NodeMCU. The purpose of this project is to demonstrate the capabilities of the ESP8266 module in hosting a network that devices can connect to.

## Features
- **Simple Web Interface**: A user-friendly web interface for interacting with the fake access point.
- **Custom SSID**: Ability to set a custom SSID for the fake access point.
- **Connection Logging**: Logs devices that attempt to connect to the access point.

## Hardware Requirements
- ESP8266 NodeMCU module
- Micro USB cable for power supply and programming

## Software Requirements
- Arduino IDE for programming the ESP8266 NodeMCU
- ESP8266WiFi library for handling Wi-Fi functionalities

## Installation
1. Connect the ESP8266 NodeMCU to your computer via the micro USB cable.
2. Open the Arduino IDE and install the ESP8266WiFi library.
3. Load the provided sketch onto the ESP8266 NodeMCU.
4. Configure your desired SSID in the sketch.
5. Upload the sketch to the module and monitor the serial output.

## Usage
Once the ESP8266 NodeMCU is programmed and running, it will broadcast the SSID. Devices can see the network and attempt to connect, and their connection attempts will be logged.

## Disclaimer
This project is for educational purposes only. Creating fake access points may be illegal in some jurisdictions, and the creator of this repository does not endorse any illegal activities.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributions
Contributions are welcome! Please read the CONTRIBUTING.md file for details on how to submit pull requests.

## Acknowledgments
- Thanks to the open-source community for the ESP8266WiFi library.
- Special thanks to everyone who has contributed to this project.

