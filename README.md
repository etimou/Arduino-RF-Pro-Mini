# Arduino-RF-Pro-Mini
**Arduino Pro Mini + nRF24L01P = Arduino-RF-Pro-Mini**
- designed with [Kicad](https://kicad.org/).
- 100% Arduino Pro Mini pin compatible
- embeds nRF24l01+ chip for radio communication
- low power (can run for months on a battery)
- compatible with [MySensors](www.mysensors.org) framework, but not only

![Screenshot](https://github.com/etimou/Arduino-RF-Pro-Mini/blob/master/images/Screenshot%20from%202020-08-16%2017-35-07.png) 
![Screenshot](https://github.com/etimou/Arduino-RF-Pro-Mini/blob/master/images/IMG_0677.jpg) 

**Programming the board**

You need to select Arduino Pro or Pro mini, ATmega328P (3.3V, 8MHz) in the Arduino IDE. An USB-Serial adapter that provides 3.3V is required, otherwise the radio chip can be damaged.

**Source code**

The example program consists in a roundtrip message that is sent from a node, using a gateway. You need two modules.

**Special thanks**

 
