## Adafruit ISO1540 Bidirectional I2C Isolator PCB

<a href="http://www.adafruit.com/products/4903"><img src="assets/4903.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit ISO1540 Bidirectional I2C Isolator. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4903

### Description

Sometimes you'll find yourself with an I2C bus controller on one side, and an I2C bus device on the other and you gotta keep em (electrically) separated. Maybe because one is Earth-grounded, maybe because you've got some funky power monitoring setup, maybe you want to reduce noise.

Whatever it is, you can use the Adafruit ISO1540 Bidirectional I2C Isolator to add full electrical isolation between two sides of an I2C bus. The chip we use, the TI ISO1540 is fully bi-directional, supports up to 1 MHz clock rates, supports clock-stretching, works with 3 to 5V DC power or logic (separate on either side of course), with 2500 V-RMS isolation

Usage is easy - you get power/ground/clock/data breakout pads for each side as well as a matching STEMMA QT connector. Unlike our other QT boards, the two sides are obviously electrically isolated, which means each half must be powered! Check that the green LED is lit on both sides. Now send data over I2C and you're good to go. We have 10K pullups on each side, from the I2C pins to the matching VCC for that side.

For more details about chip specifications, check out the TI product page.

To get you going fast, we spun up a custom made PCB in the STEMMA QT form factor, making it easy to interface with. The STEMMA QT connectors on either side are compatible with the SparkFun Qwiic I2C connectors. This allows you to make solderless connections between your development board and the ISO1540 or to chain it with a wide range of other sensors and accessories using a compatible cable. QT Cable is not included, but we have a variety in the shop.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
