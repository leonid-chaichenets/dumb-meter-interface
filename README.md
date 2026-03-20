<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
# dumb-meter-interface
An electrical interface design to connect pulse outputs of consumption meters, e.g. reed switches, to GPIO inputs.

## Task Overview
The following meters shall be read:

### Gas Meter
![Kromschröder BK-4](docs/images/BK-G4.jpg "Kromschröder BK-G4")

[Kromschröder BK-4](https://docuthek.kromschroeder.com/download.php?lang=en&doc=64549)

### Water Meter
![Ernst Heitland M100i](docs/images/M100i.jpg "Ernst Heitland M100i")

[Ernst Heitland M100i](https://prod-edam.honeywell.com/content/dam/honeywell-edam/pmt/hps/products/sme/water/residential-metering/multi-jet-meters/m100i/M100i-Datasheet-German.pdf)

### Electricity Meter
![EFR SGM-D4-A920N](docs/images/SGM-D4-A920N.jpg "EFR SGM-D4-A920N")

* Smart Meter [EFR SGM-D4-A920N](https://www.efr.de/products/smart-energy-geraete/elektronische-stromzaehler/basiszaehler/sgm-d4/)
* Smart Metering [EMH Casa 1.2](https://emh-metering.com/produkte/smart-meter-gateway/casa/)