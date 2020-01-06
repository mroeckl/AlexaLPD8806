# Alexa LED control (LPD8806) via ESP8266
With this Arduino sketch an LPD8806 LED strip can be controlled via Alexa via an ESP8266. You can set the color as well as the intensity.

# Usage
Search for devices in the Alexa companion app. You should find a Royal Philips Electronics... device. Accept it and give it a name.

Switch it on: Alexa, switch &lt;name&gt; on

Change color: Alexa, set &lt;name&gt; to red

Change intensity: Alexa, brighten &lt;name&gt; to 60%

# Hardware
## Parts
* [ESP8266](https://www.banggood.com/de/ESP8266-ESP-01-Remote-Serial-Port-WIFI-Transceiver-Wireless-Module-p-947259.html?rmmds=search&cur_warehouse=CN) - ESP-01
* [LED Strip LPD8806](https://www.amazon.de/LPD8806-Streifen-Strip-Stripe-IP20/dp/B00KFQN3IU)
* [Step-Down Converter 3.3V](https://www.banggood.com/de/5V-To-3_3V-DC-DC-Step-Down-Power-Supply-Buck-Module-AMS1117-800MA-p-933674.html?rmmds=search&cur_warehouse=CN)
* [Power supply 5V/8A](https://www.amazon.de/LED-Netzteil-MeanWell-LPV-60-5-Schaltnetzteil/dp/B00MWQF08C) - enough for my 104 LEDs each drawing up to 60mA

## Layout
![Layout not found](https://raw.githubusercontent.com/mroeckl/AlexaLPD8806/master/AlexaLPD8806_bb.png)


# Arduino IDE
## Configuration
<img src="https://raw.githubusercontent.com/mroeckl/AlexaLPD8806/master/Arduino-IDE-Config.png" width="200px">

## Programming
Write the [AlexaLPD8806.ino](https://raw.githubusercontent.com/mroeckl/AlexaLPD8806/master/AlexaLPD8806.ino) file to the ESP8266.

# References
* [Aricookie/EspAlexa](https://github.com/Aircoookie/Espalexa)
* [Adafruit/LPD8806](https://github.com/adafruit/LPD8806)