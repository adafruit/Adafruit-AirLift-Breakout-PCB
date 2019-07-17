## Adafruit AirLift – ESP32 WiFi Co-Processor Breakout Board PCB

<a href="http://www.adafruit.com/products/4201"><img src="assets/4201.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit AirLift – ESP32 WiFi Co-Processor Breakout Board. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4201

### Description

Give your plain ol' microcontroller project a lift with the Adafruit AirLift - a breakout board that lets you use the powerful ESP32 as a WiFi co-processor. You probably have your favorite microcontroller (like the ATmega328 or ATSAMD51), awesome peripherals and lots of libraries. But it doesn't have WiFi built in! So lets give that chip a best friend, the ESP32. This chip can handle all the heavy lifting of connecting to a WiFi network and transferring data from a site, even if its using the latest TLS/SSL encryption (it has root certificates pre-burned in).

Having WiFi managed by a separate chip means your code is simpler, you don't have to cache socket data, or compile in & debug an SSL library. Send basic but powerful socket-based commands over 8MHz SPI for high speed data transfer. You can use 3V or 5V Arduino, any chip from the ATmega328 or up, although the '328 will not be able to do very complex tasks or buffer a lot of data. It also works great with CircuitPython, a SAMD51/Cortex M4 minimum required since we need a bunch of RAM. All you need is an SPI bus and 2 control pins plus a power supply that can provide up to 250mA during WiFi usage.

We placed an ESP32 module on a PCB with level shifting circuitry, a 3.3V regulator, and a tri-state chip for MOSI so you can share the SPI bus with other devices. Comes fully assembled and tested, pre-programmed with ESP32 SPI WiFi co-processor firmware that [you can use in CircuitPython to use this into a WiFi co-processsor over SPI + 2 pins](https://github.com/ladyada/Adafruit_CircuitPython_ESP32SPI). We also toss in some header so you can solder it in and plug into a solderless breadboard.

[The firmware on board is a slight variant of the Arduino WiFiNINA core, which works great!](https://github.com/adafruit/nina-fw) At this time connection to Enterprise WiFi is not yet supported.

[Check out our learning system guide for schematics, files, and to get started AirLift'in' within minutes!](https://learn.adafruit.com/adafruit-airlift-breakout)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
