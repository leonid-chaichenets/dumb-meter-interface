<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->

# Water Meters
Our prime target is
an [Ernst Heitland’s M100i](https://prod-edam.honeywell.com/content/dam/honeywell-edam/pmt/hps/products/sme/water/residential-metering/multi-jet-meters/m100i/M100i-Datasheet-German.pdf).
However, in principle, any meter with an inductive coupling interface is supported.
![Ernst Heitland M100i](images/M100i.jpg "Ernst Heitland M100i")

## Sensors
Specifically for M100i, a native sensor
module ([Honeywell Falon MJ Puls/M-Bus Modul](https://prod-edam.honeywell.com/content/dam/honeywell-edam/pmt/hps/products/sme/water/digital-metering/wmbus/falcon-mj-pulse-mbus/D-Falcon20MJ-D-1407-0317.pdf))
is commercially available. Measurements are done by inductively locating the metallic half-disc mounted on the
100ml-counter (the one with mold in the picture above) with a three-coil setup. Sensor’s output is available as
ISO-22158 shaped pulses or over the M-Bus (EN13757) interface. Compared to unfortunately
incompatible [simple reed switches](https://prod-edam.honeywell.com/content/dam/honeywell-edam/pmt/hps/products/sme/water/residential-metering/multi-jet-meters/m190/M190-Mehrstrahlz-hler-Data-sheet-German.pdf),
the module is therefore [quite costly](https://mysmartshop.de/products/honeywell-elster-falcon-mj-puls).

Commercially available generic [inductive sensors](https://en.wikipedia.org/wiki/Inductive_sensor) suffer from a number of
deficiencies: They either need a
[higher supply voltage](https://www.conrad.de/de/p/balluff-induktiver-sensor-bes05rk-1-st-908544362.html),
have a [WiFi interface](https://www.ebay.de/itm/388472415193) (overkill and need an additional power supply), or are
[bulky](https://de.aliexpress.com/item/1005005128346690.html).

A simple proximity switch can be built around the TI’s [LDC0851](https://www.ti.com/document-viewer/ldc0851/datasheet).
Unfortunately, the chip is rather small (WSON-8, 2mm x 2mm) and almost impossible to solder by hand. However, a good
friend of mine made a [development board](https://github.com/marcusmueller/leoniduction) for them. 