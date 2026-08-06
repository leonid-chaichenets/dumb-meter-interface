<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->

# Gas Meters
![Kromschröder BK-4](images/BK-G4.jpg)
Our prime target is a [Kromschröder BK-4](https://docuthek.kromschroeder.com/download.php?lang=en&doc=64549). However, in principle, any meter with a magnetic reed switch interface
is supported.

## Sensors
Specifically for BK-4, native reed switches ([Honeywell IN-ZXX](https://process.honeywell.com/us/en/site/elster-instromet-de/produkte/gasmessung/balgengaszahler/in-z61))
are commercially available. When reusing a sensor, a new [plastic clip](https://gt-gascount.de/10-Stueck-Befestigungsclips-fuer-IN-Zxx) may be necessary.
![Honeywell IN-Z62 front side](images/IN-Z62_front.png) ![Honeywell IN-Z62 back side](images/IN-Z62_back.png) ![Honeywell IN-Z62 right-hand side](images/IN-Z62_right-hand_side.png) ![Honeywell IN-Z62 left-hand side](images/IN-Z62_left-hand_side.png) ![Honeywell IN-Z62 disassembled](images/IN-Z62_disassembled.png) ![Honeywell IN-Z62 printed circuit board, meter-facing side](images/IN-Z62_PCB_meter-facing_side.png) ![Honeywell IN-Z62 printed circuit board, aperture-facing side](images/IN-Z62_PCB_aperture-facing_side.png)
The sensor consists of the reed switch *only* &mdash; there is *no* current limiting or debouncing electronics.

An electrically equivalent [3rd party solution](https://ng3d-druck.de/products/reedkontakt-sensor-bk-gaszaehler-esphome) is also available.
