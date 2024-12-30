# Mitsubishi ESPHome
 Controller board for Mitsubishi ESPHome 

Having 5 of these units and recently going way to deep on the whole Solar + Home Assistant I looked for a simple circuit I could just plug in and move on with my life.

I couldn't find one.  Everything was jamming some pins on a D1 mini or overkilling it with a Raspberry Pi.

So I looked really, really closely at:
https://chrdavis.github.io/hacking-a-mitsubishi-heat-pump-Part-1/
https://nicegear.nz/blog/hacking-a-mitsubishi-heat-pump-air-conditioner/

And used them to design my own.

To do the inital program for this you will need a Superhouse.tv ESPFlasher (https://www.superhouse.tv/product/espflasher-esp8266-esp32-usb-serial-flasher/)

I've included a config example for ESPHome.

To integrate this with Home Assistant.
https://github.com/echavet/MitsubishiCN105ESPHome