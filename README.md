# HA-Metrotherm-scrape
Get data from Metrotherm heat-pump

This uses Multiscrape from danieldotnl (Installed via HACS):

https://github.com/danieldotnl/ha-multiscrape?fbclid=IwAR2OE-v1uBoPT58IoVOZ3HgEi09SGR_uCwoI6B3Oq6ZaYKkIDWtMrXJV8xE


Creates sensors for:


Outdoor temperature (current and average)

Temperature of the water in the heating circuit

Auxiliary heater power and runtime

Compressor runtime (total and hot water)

Compressor frequency


Installation:


  1. Install Multiscrape via HACS


  2.Place the metrotherm.yaml file in the config directory of your Home Assistant instance and insert the follwing line in configuration.yaml


    multiscrape: !include metrotherm.yaml


  3. Restart Home Assistant
