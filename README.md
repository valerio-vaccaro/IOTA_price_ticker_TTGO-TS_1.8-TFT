
<p><img src="https://github.com/oxinon/IOTA_price_ticker_TTGO-TS_1.8-TFT/blob/master/picture/IOTA-Price-Ticker.png" alt="Cover" width="400"></p>

<br>

<p><img src="https://github.com/oxinon/IOTA_price_ticker_TTGO-TS_1.8-TFT/blob/master/picture/IOTA-Ticker-CM.png" alt="Cover" width="300"></p>

Simple IOTA price ticker by using ESP32 besed TTGO-TS_1.8 TFT and CoinMarketcap API for the Arduino IDE platform
<br>
IOTA ticker on Youtube: https://www.youtube.com/watch?v=napduhMtkBk&t=94s
<br>
<br>

* * *

<b>Index of this project</b>

+ [Add ESP32 Arduino IDE](#ESP32)
+ [Libraries for Arduino IDE](#libraries)
+ [Screen shifting Issue](#issue)
+ [Additional information](#additional)

* * *

<br>
<a name="ESP32"></a><h2>Add ESP32 in Arduino IDE</h2>
Before we can start compiling, the Arduino must have the TTGO-TS board, based on an ESP32 in the board selection available.
The instruction on https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/
In board selector you can select "ESP32 Dev Module" for TTGO-TS.
<br>
<br>

<a name="libraries"></a><h2>Libraries for Arduino IDE</h2>
Now we add libraries for Arduino IDE:

<b>Adafruit_GFX.h</b><p>
  <b>Adafruit_ST7735.h</b><br>
  (see "Screen shifting Issue" Adafruit_ST7735_and_ST7789_Library-TS18 if you have Screen shifting)<p>
<b>ArduinoJson.h</b><br>
    (please use version from "Aruinojson by Benholt Blanchon Version 5.13.4")<p> 
  <b>CoinMarketCapApi.h</b><p>
  If you are have problem with the "wifi.h" delete the arduino/libraries/wiFi directory, you can use the esp32 WiFi.h
<br>
<br>

<br>

<a name="issue"></a><h2>Screen shifting Issue</h2>

<p><img src="https://github.com/oxinon/IOTA_price_ticker_TTGO-TS_1.8-TFT/blob/master/picture/Display-Mapping2.png" alt="Cover" width="200"></p>
<br>

<p><img src="https://github.com/oxinon/IOTA_price_ticker_TTGO-TS_1.8-TFT/blob/master/picture/libery.png" alt="Cover" width="200"></p>
<br>

<a name="additional"></a><h2>Additional information</h2>

<p><img src="https://github.com/oxinon/IOTA_price_ticker_TTGO-TS_1.8-TFT/blob/master/picture/field-test2.png" alt="Cover" width="200"></p>
<br>

An SPI display is not the fastest to build the pixels, to make this faster, filled first only the colored marked fields with black and then built up with the new numbers.


* * *

If you like my work, you can give me a tip for a beer :)<br>
<b>Donate IOTA address:</b> 
CIMRZOWYFUGYRFUGBJRBDIILCUBNCNNBMYCJDFVJN9HRCNXQAPFRMHUI9KOQCQGXTZIKFFBJLRUJUUZPYEAZEWOXAX
