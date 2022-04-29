## Adafruit VL53L4CX Time of Flight Distance Sensor PCB

<a href="http://www.adafruit.com/products/5425"><img src="assets/5425.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit VL53L4CX Time of Flight Distance Sensor. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5425

### Description

The Adafruit VL53L4CX Time of Flight Sensor is another great Time of Flight distance sensor from ST in the VL5 series of chips, this one is great for long distances - it goes up to 6 meters compared with 4 meter max of the VL53L1X.

The sensor contains a very tiny invisible laser source and a matching sensor. The VL53L4CX can detect the "time of flight", or how long the light has taken to bounce back to the sensor. Since it uses a very narrow light source, it is good for determining distance of only the surface directly in front of it. Unlike sonars that bounce ultrasonic waves, the 'cone' of sensing is very narrow. Unlike IR distance sensors that try to measure the amount of light bounced, the VL53 is much more precise and doesn't have linearity problems or 'double imaging' where you can't tell if an object is very far or very close.

This is a 'big sister' of the VL53L4CD ToF sensor and can handle about ~1 to 6000mm of range distance, it also has some ability to do 'multi object detection'. Basically it can identify when more than one object is in view and tell you the two distances.

Please note, the Arduino driver for this chip does not support 'small memory' boards like the ATmega328 - you'll need a SAMD21, SAMD51, ESP, etc chip with 50K of flash memory available!

The sensor is small and easy to use in any robotics or interactive project. Since it needs 2.8V power and logic we put the little fellow on a breakout board with a regulator and level shifting. You can use it with any 3-5V power or logic microcontroller with no worries. Works great with the 3.3V logic level of a Feather, or the 5v level of a Arduino Mega, this breakout is ready to work with most common microcontrollers or SBCs. and since it speaks I2C, you can easily connect it up with two data wires plus power and ground. 

As if that weren't enough, we've also added SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder. Just wire up to your favorite micro with a plug-and-play cable to get ToF data ASAP. For a no-solder experience, just wire up to your favorite micro, like the STM32F405 Feather using a STEMMA QT adapter cable. The Stemma QT connectors also mean the VL53L4CX can be used with our various associated accessories. QT Cable is not included, but we have a variety in the shop

Communicating to the sensor is done over I2C with an API written by ST, they have an Arduino library with an example for communication

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
