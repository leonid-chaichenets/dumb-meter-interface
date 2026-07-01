<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->

# dumb-meter-interface

An electrical interface design to connect pulse outputs of consumption meters, e.g. reed switches, to GPIO inputs.

## Task Overview

The original goal was to interface an [electricity](docs/electricity_meters.md), [gas](docs/gas_meters.md), and [water meters](docs/water_meters.md) in a higher consumption
household to a smart metering solution, like [Volkszähler](https://volkszaehler.org/). An auxiliarly goal was to add a time signal read by a
[DCF-77](https://en.wikipedia.org/wiki/DCF77) [radio module](docs/time_meters.md) to the metering solution.
