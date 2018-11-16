Forked from Adafruit's BlueFruit LE Connect for Android, which can be found at https://github.com/adafruit/Bluefruit_LE_Connect_Android.  Added is a Voice menu that will allow for Speech-To-Text translation and transmission to the Uno for commands.  Attach the .ino, .h, and .cpp files to your Arduino Uno, and you are ready to go.  

I will be posting updates to this project here, as well as on my blog at https://olsonetworks.wordpress.com.  I am no longer on Google+ anymore, but will attempt to remain relatively active on my blog.  

**UPDATE 11/15/2018***
Attached to this project is now code for the Arduino Mega2560.  We can now use the hardware serial port on the mega, which provides much better response than the software serial on the Uno.  This also gives us plenty more room to the additional sensors that will be used in this project, mainly the hc-05 ultrasonic distance sensor, the triple-axis accelerometer/gyro/magnetometer, and the neopixel rings.  Also fixed, the string from the voice menu now reports the entire packetbuffer.  Had a problem where the packetbuffer was only sending one char, this was probably my horrible coding, but to be sure, I have re-written that portion.  Thanks!

Bluefruit LE Connect for Android
================================

Android port of Adafruit's Bluefruit LE Connect app for iOS.

This application works with the following Adafruit breakouts:

- [Bluefruit LE Friend](https://www.adafruit.com/product/2267)
- [Bluefruit LE UART Friend](https://www.adafruit.com/product/2479)
- [Bluefruit LE SPI Friend](https://www.adafruit.com/product/2633)
- [Bluefruit LE Shield](https://www.adafruit.com/products/2746)
- [Bluefruit LE Micro](https://www.adafruit.com/product/2661)
- [Feather 32u4 Bluefruit LE](https://www.adafruit.com/product/2829)
- [Feather M0 Bluefruit LE](https://www.adafruit.com/products/2995)

Bluefruit LE Connect enables the exchange of information between your Bluefruit LE breakout and your BLE enabled Android device (Android 4.4 and higher required).  

The application also enables [over the air updates](https://learn.adafruit.com/introducing-the-adafruit-bluefruit-le-uart-friend/dfu-updates) to keep your Bluefruit module up to date with the latest [Bluefruit LE firmware](https://github.com/adafruit/Adafruit_BluefruitLE_Firmware).

## License

Unless otherwise specified, all files produced by Adafruit are covered by an [MIT license](https://github.com/adafruit/Bluefruit_LE_Connect_Android/blob/master/license.txt).  

Files produced by Nordic Semiconductors are covered by their own license terms, as detailed in the file headers and appropriate folders. Please carefully review the license requirements before using this source code in your own application.
