ESP32 EPD E-Paper Library
=======

ESP32 Arduino Library for the 4.3inch e-Paper display by Waveshare

See wiring.jpg and wiring-usb.jpg for information on how to connect the Display

![Wiring for the ESP32](wiring.JPG)

This repository combines a modified version of the esp8266 epd-library by [G6EJD](https://github.com/G6EJD/ESP32-8266-ePaper-Serial-UART-Wx-Display) with the example made by [sabas1080](https://github.com/sabas1080/LibraryEPD).

Instead of using RX0/TX0 this library and example use RX2/TX2 to communicate with the display.
