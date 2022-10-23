# arduino-rgb-led-controller
Arduino script - RGB (ARGB) LED controller for 3-pin addressable RGB devices (i.e. WS2812b compatible addressable LEDs)

## Setup example
- Arduino Uno or similar
- Look at the `argb_header_5v_schematics.png` schematics and connect the Arduino to your rgb cable/header. GND to GND, 5V to 5V, and Data connector to data pin 8 on the arduino (or another pin but then you have to change the script). In between the data pin on the rgb cable/header and the arduino data pin it is recommended to add a 470 ohm resistor (anything between 300 and 1k is fine).
- Load the script `arduino_rgb_controller.ino` onto your arduino (using the Arduino IDE and connecting the Arduino Board to the USB port on your PC) and then you're set. You may need to install the FastLED library into your Arduino IDE, using the built-in library manager.

## config
the script have 3 light example configs;
- rainbow (classic rgb style)
- static color
- gradient using two colors
