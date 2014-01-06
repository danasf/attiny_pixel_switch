ATtiny85 Pixel Switcher
================================

For use with ATtiny85 (or Arduino!) and WS2811 LEDs

Instructions
------------

* Download Adafruit's [NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel) library
* Get the [ATtiny cores](https://code.google.com/p/arduino-tiny/) for Arduino & a [programmer](https://www.adafruit.com/products/46)
* Attach your LED data line to Digital Pin 4
* Attach momentary push button/switch to Digital Pin 0
* Upload the sample sketch and enjoy your light show! 
* Create and share patterns of your own :-)

![ATtiny85](/attiny.jpg)

Useful Files
------------

* attiny_pixel_touch.ino - uses the [Capacitive Sense](http://playground.arduino.cc//Main/CapacitiveSensor) library to switch things
* attiny_pixel_switcher.ino - switches pattern with a button or momentary switch

More Info
------------

Need help getting started with ATtiny and lights? I wrote an [Instructable](http://www.instructables.com/id/Use-a-1-ATTiny-to-drive-addressable-RGB-LEDs/) on the subject.

