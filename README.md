# URTelegram - ESP32 Telegram bot

Initially intended as a fork of https://github.com/cotestatnt/AsyncTelegram but changes went too far and in quite a different direction, this bot is not intended for a typical bot applications with in-built keyboard and standard responses, instead it should be used as a free text communication tool. At the moment all text processing code is outside of the bot core - but eventually will be moved into it

It relies on [ArduinoJson](https://github.com/bblanchon/ArduinoJson) v6 library so, in order to use a AsyncTelegram object, you need to install the ArduinoJson library first (you can use library manager).

You also need to install the [ESP8266 Arduino Core and Library](https://github.com/esp8266/Arduino) or the [ESP32 Arduino Core and Library](https://github.com/espressif/arduino-esp32).

### Features
+ Send and receive non-blocking messages to Telegram bot
+ Stickers!

### Supported boards
The library works with ESP32 and possibly may work with ESP8266 but not tested there yet

