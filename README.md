# Capacitive-Soil-Sensor
This is a setup to use multiple capacitive soil sensors with one ESP8266 utilizing the great ESPHome library. Eventually this will will have 3D printed design files as well to enclose and waterproof the capacitive soil sensors and the ESP8266. 

Here are the sensors I am using:
https://www.aliexpress.com/item/10pcs-Capacitive-soil-moisture-sensor-not-easy-to-corrode-wide-voltage-wire-for-arduino/32859931034.html?spm=a2g0s.9042311.0.0.36424c4dca4OGe

I am using this Wemos D1 Mini Lite to read the sensor values:
https://smile.amazon.com/gp/product/B07BK435ZW/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1

Connect all of the sensors ground wires to ground, and connect all the analog outputs from each sensor to the same ADC pin. The positive wire on each sensor should go to its own GPIO on the ESP8266.

Some notes for parts I will use in this project:

I am going to use these connectors to make each sensor able to disconnect from a long cord, yet still stand up to outside weather
https://smile.amazon.com/gp/product/B071NCK9WW/ref=ppx_yo_dt_b_asin_title_o04_s00?ie=UTF8&psc=1

I am going to use this AC to DC converter to power the Wemos
https://smile.amazon.com/gp/product/B076K8HT8Z/ref=ppx_yo_dt_b_asin_title_o09_s00?ie=UTF8&psc=1
