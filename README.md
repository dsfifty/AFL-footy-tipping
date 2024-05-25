![1000019147](https://github.com/dsfifty/AFL-footy-tipping/assets/113217855/1454fe34-b86a-425d-a928-043ecc0a6159)
![1000019144](https://github.com/dsfifty/AFL-footy-tipping/assets/113217855/f72631a0-d818-4583-aeb6-28e90580bbfb)
# ESP32 AFL-footy-tipping
An esp32 project that works with a TFT screen to collect AFL footy tips and then update scores and your tip results. 

Written in the Arduino IDE.

Comments in the code might help understand what is happening.
Special thanks to the ArduinoJSON assistant v7

Accesses api.squiggle.com.au

This code uses the TFT_eSPI library. In this library you have to set up the User.Setup.h file in the library folder according to your own connections.

If you have your screen working properly using the TFT_eSPI library, then this code is good to go (nearly).
NOTE: All versions prior to v1.1 run on a 320x240 screen (ILI9341). Versions v1.1 and after are on a 320x480 screen with touch (ILI9488)

Report any issues and I will try to help
