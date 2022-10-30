# UniMiniESP8266

For common simple microcontroller applications, I created a very tiny board in the size of an 18650 cell.
In many cases, the 3,0V - 4,2V of a single cell is sufficient, which makes it extremely simple to build working circuits.
There are many pins for power supply, so there is no more breadbord wiring or perfboard wiring hell.

What it can do for you:
- easyly powered with a single 18650 lithium cell, works down to 3,2V discharge due to LDO
- drives up to 6 servos (using 18650 voltage)
- has two pins with transitor-outputs, if populated
- can have an H-bridge using L9110
- onboard switch intended (or use a solder bridge)
- WiFi ability due to the power of ESP8266

To download code, use a FTDI-adapter, shorten pin M1 to ground and press reset or, if reset switch is not populated, just power on.

As an example, have a look in my "Servo-Tester" repository on github:
https://github.com/Pontifex42/ServoTester

It uses ESP8266-12F module, I will create an improved version using ESP-C3-12F soon.

