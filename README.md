## Adafruit QT 3V to 5V Level Booster Breakout - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/5649"><img src="assets/5649.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit QT 3V to 5V Level Booster Breakout - STEMMA QT. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5649

### Description

If you're looking to use the Qwiic / Stemma QT standard for your next project - but you're using a sensor or device that requires 5V power or logic, this board is designed for you! It will let you use the 3V power and logic from your Raspberry Pi, or ARM Cortex microcontroller, and boost/shift it up to 5V for use with older or high-power devices that aren't happy with only 3V.

These days, almost every microcontroller / microcomputer board has 3V power and logic: ESP32 series, ATSAMD chips, RP2040 boards, micro:bits, etc! But we still see sensors and devices here and there that really want 5V power or logic. Like this Sensirion SEN54 which has a small motor with 5V power requirements.

On one side of this board is 3V power and logic level inputs. In the middle is a 5V charge-pump boosting regulator that can provide 100mA continuous (250mA peak) plus level shifting circuitry. On the opposite side is the same I2C traffic but now safely shifted up to 5V. If you happen to be using a board that wants 5V power, but 3V logic I2C, there's a solder jumper on the back you can cut/solder to set the output logic level to unshifted 3V.

It's simple but very effective! You also get breadboard breakout pins for breadboard usage so it can also be used as a QT-to-perfboard adapter. If you need something that does 5V to 3V down-conversion, we have that in the shop as well.

The STEMMA QT connectors on either side are compatible with the  I2C connectors. This allows you to make solderless connections between your development board and the QT Shifter or to chain it with a wide range of other sensors and accessories using a compatible cable. QT Cable is not included, but we have a variety in the shop. 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
