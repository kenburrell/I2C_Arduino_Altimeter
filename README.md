# I2C_Arduino_Altimeter
The I2C version of the Practice Altimeter for Arduino UNO using ILI9341 
touchscreen shield for the Arduino UNO, and the I2C BME280 sensor.

Range of Ground Level Pressure(QNH) 27.50 to 31.50 inches of Hg.
Any other input of inHg will result in "invalid" message with wait for
correct input.

To use, enter the most recent QNH in inches of Hg obtained from a nearby
airport METAR.  QNH is a sea level pressure equivalent, but not exactly
the same as Sea Level Pressure (SLP), as SLP is adjusted for a 12-hour 
average temperature, rather than for current conditions.

The shield requires the use of 4 extra long female shield headers ( 4pins,
6pins, and two 8pins) to enable the use of 3 female/femae jumper wires for
RST,VCC,GND and 2 female/male jumper wires for SDA,SCL connections to the 
BME280 sensor.

Additionally, the last two pins of the ILI9341 touchscreen shield (one labeled
LCD_RST and the other unlabeled) must be bent at a 45 degree angle so that
2 female/male jumper wires can be inserted into the A4/A5 (SDA/SCL) pins
of the Arduino UNO.

Made publicly available under the terms of the Creative Commons License.

Copyright August 2, 2020.  Ken Burrell.
