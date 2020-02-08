# Description
The Alexa light switch is pretty self explanitory. The .ino file that is included in the repo is responsible for connecting a NodeMCU to the SSID that is provided to it and will then connect to the specified Sinric smart home account.
## Mechanical Movement
The light switch is mechanically moved by a 3D printed arm that screws into the switch plate found on the wall. To be clear, the 3D design was taken from Thingiverse and the designer will be linked below. The purpose of the arm is to generate maximum torque to ensure the least amount of wear on the cheap 9 gram servo motor. (Images can be seen through the link)
[Alexa Light Switch](http://csdutra.com)
## Code
Some of the code for the project was taken from the examples in the ESP8266 library. Other than a few basic lines and include statements to get the NodeMCU to connect to the local SSID. Other than that, all the code is specific to my use case but can easily be modified to fit the needs of anyone who would like to try the project for themselves.
## Sinric
Sinric is a simple service that allows Raspberry Pi's, ESP8266, and other WiFi microcontrollers to link with Amazon Alexa and Google Home. An account will be needed for this project. Also take note of your API key and device IDs as they will be needed in the .ino file to ensure proper communication between the two services
## 3D Design for Wall Mount
* **trobb13** - *3D Design*
[Thingiverse Link](https://www.thingiverse.com/thing:2826024)

### Acknowledgments
* Authors of the ESP8266 Arduino Library
* 3D designer of the wall mount for the 9 gram servo
