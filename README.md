# heatcontrol-arduinomega

This is an example AppMyProduct device application on the Arduino Mega2560 platform simulating a heatpump. Currently supports the Heat Control Ionic starter app.

# What is needed to run the demo

This demo is tested on an Arduino Mega2560 with Wiznet W5100 Ethernet Shield board connected to it.

To compile the example you need to install the Arduino IDE. 

We also need a device name and key, both of which can be created at portal.appmyproduct.com

Download the latest heatcontrol-arduinomega-master zip library from the releases (not the Source code (zip)).

No matter which way, we can now add the library to the Arduino IDE via Sketch -> Include Library -> Add .ZIP Library... and then browse to and add the heatcontrol-arduinomega-master that was just created/downloaded.

# Run the example

We can now open the HeatPump.ino example by going to File -> Examples -> Nabto-ESP8266 -> HeatPump
