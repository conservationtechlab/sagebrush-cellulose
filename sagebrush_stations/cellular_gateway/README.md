# Solar-Powered Cellular LoRa Gateway Station

## Wiring

This folder contains a simplistic wiring diagram in the form of a jpg. Mainly to indicate
what components go inside the box enclosure versus outside, and what connects to what for
data and power.

## Materials

This folder contains a .csv with the required components and suggested links to parts
associated with building the system.

### Caveats
## LoRa Gateway - Antennas
For all gateway setups, we include standard LoRa gain antennas in our materials
lists. However, these can be swapped with different antennas depending on the
deployment location and needs. Assess your deployment location and needs before
selecting LoRa antennas/directionality.
## LoRa Cellular Gateway- Data Plans
Your data plan needs will vary with each deployment. In urban areas or
with many deployed devices, you may need higher data rates than in other
areas. We recommend going with a monthly plan to start at less data than
you think you need, and then topping up data as you hit lows. Then choosing
a longer term plan (typically this results in a discount versus month to month)
based on what your usage was. You can calculate expected data usage knowing
the amount of devices, amount of gateway up/downlinks, rate of device packets,
and size of packets, but this calculation is an estimate and does not account
for all the data usage factors, so it's important to monitor your baseline at
first so you don't overshoot or undershoot long term.
## LoRa Cellular Gateway - SIM Card
Ensure you choose an IoT data SIM. Not a SIM card with a phone number indended
for phone usage. The SIM card linked is good for individual deployments and
is plug and play. For large scale deployments, you may want to look into
IoT SIM management platforms where data plans are pooled across devices.
