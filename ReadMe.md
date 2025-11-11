# MQTT Script for the Plasma Stick 2040 W (Pico W Aboard) by Pimoroni
MQTT Script for the Plasma Stick 2040 W (Pico W Aboard) by Pimoroni

The scripts provides a quick and easy way to visualise data coming in via an MQTT broker using an edited version of the Pimoroni Temperature Script. Connected to Wifi, it subscribes to an MQTT feed, enabling messages to be visualised via changes of Colour. 

![Plasma Stick 2040W ](https://cdn.shopify.com/s/files/1/0174/1800/products/plasma-stick-2040w-2_768x768.jpg?v=1666709554)

[Plasma Stick 2040W ](https://shop.pimoroni.com/products/plasma-stick-2040-w?variant=40359072301139)


Our example uses a Ships Lamp to visualise Wind Speed from a live feed provided from a Davis Vantage Pro 2 weather station out of the Connected Environments Lab at University College London. The colour of the ships lamp changes, every 3 seconds, from Green to Red over a spread of 0 to 40mph. 


![MQTT Ships Lamp](https://github.com/ucl-casa-ce/Open-Gauges/blob/main/Contributed/ShipsLamp/shipslamp.jpeg)

Copy all the files to your Plasma Stoick 2040 W using Thonny - edit config.py to add your Wifi and MQTT broker credentials.

Edit the MQTT_PlasmaStick_2040.py file for your own MQTTT topic, save as main.py so the Pico W runs the script on boot.

Created as part of work at the [Connected Environments Group] (https://connected-environments.org/) at the Centre for Advanced Spatial Analysis, University College London.
