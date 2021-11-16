# ESP32 mini KiCad Library
KiCad symbol and footprint for the ESP32 Mini, the ESP32 clone of the Wemos D1 mini with more pins and more power!
There is some info on the boards [here](https://www.reddit.com/r/esp8266/comments/a93raj/wemos_ttgo_mini_d1_esp32/). It seems to be a Wemos clone, but is def. not made by them. I really like the boards for the small size and cheap price while giving me the power of an ESP32 and much more IO compared to the Wemos D1 mini.

It seems people can't really agree on what this board is called, here are some common names I have found:
- D1 mini ESP32 ESP-32 
   - I am using these ones [AliExpress](https://www.aliexpress.com/item/32819907815.html?spm=a2g0o.placeorder.0.0.6362321eORA9U3&mp=1)
- MH-ET LIVE D1 Mini ESP32 ESP-32 WiFi 
   - [KeeYeesESP32 Mini @ Amazon](https://amzn.to/3bANxOz)*
   - [ALMOCN ESP32 ESP-WROOM-32 @ Amazon](https://amzn.to/3w8c9aW)*
   - [XTVTX Node-MCU ESP32 @ Amazon](https://amzn.to/3bBWK9q)*
(* affiliate links)

I am programming them using Platformio, where they call them [WeMos D1 MINI ESP32](  https://docs.platformio.org/en/latest/boards/espressif32/wemos_d1_mini32.html)

This what mine looks like:
![image](https://user-images.githubusercontent.com/558053/92308608-2eaab780-ef9f-11ea-97a7-bbd80803f333.png)

I made a sligthly simplified PIN out, which helps me breadboarding and programming, as it focuses on IO pins and their location:
![ESP32_mini_pins](https://user-images.githubusercontent.com/558053/93228315-a209b180-f775-11ea-95f7-2d7999092368.jpg)
[A PDF version can be found here.](https://github.com/r0oland/ESP32_mini_KiCad_Library/files/5225892/ESP32_mini_pins.pdf)

Pinout ([taken from www.esp32learning.com](https://i1.wp.com/www.esp32learning.com/wp-content/uploads/2018/12/MH-ET_LIVE_D1_mini_ESP32_pinout.png?resize=696%2C479))
![image](https://user-images.githubusercontent.com/558053/92308628-57cb4800-ef9f-11ea-81fa-64d722c4df24.png)
