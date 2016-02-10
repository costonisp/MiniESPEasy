MiniESPEasy = ESPEasy for modules with small number of available I/O pins

This is a fork of stable ESPEasy-R78 release.
Using this fork of ESPEasy you can use the Rxd and Txd pins on small modules like ESP-01, ESP-02 and several commercial WiFi-gadgeds with limited I/O pin numbers for general use and also for I2C use. 

For documentation of the program look at the documentation of ESPEasy

If you are using MiniESPEasy for the first time, follow the instructions for installing ESPEasy on http://www.esp8266.nu/index.php/Main_Page. After installing the libraries use the Arduino IDE to compile the MiniESP sourcecode and flash your ESP8266.


Wiki: http://www.esp8266.nu

Forum: http://www.esp8266.nu/forum



Credits:

All credit for this program goes to the writer of ESPEasy Martinus (mvdbro).
Also I want to mention martinayotte from the esp8266.com forum who alerted me to the existence of the Serial.swap() command.

My work was only to add a few Serial.swap() commands, slightly change the Hardware page of the webGui so that GPIO-13&15 are replaced by GPIO-1&3, reordering the pin_list and adding GPIO-1&3 in the I2C selection menu.
I also changed 2 bytes in the OLED module so that displays with SH1106 & SSD1366 controllers will be supported.
