# Bruce Predatory — Full BOM / Component Guide

> Reference list for the LicensedV1 documentation package. Prices are approximate and can change by supplier.

## Main Hardware

| Component | Reference |
|---|---:|
| CYD / ESP32 display board | ₱543 |
| PCB | ₱84 |
| Female connectors | ₱64–₱200 |
| GPS module | ~₱200 |
| CC1101 module | Varies |
| NRF24 module | Varies |
| MicroSD card | Varies |

## Supporting Hardware

- Header pins / female headers
- Jumper wires
- Dupont connectors
- SMA/u.FL adapters where applicable to the specific module
- Small switches
- Capacitors for appropriate power filtering
- Battery/power system matched to the board requirements
- Enclosure / mounting hardware
- Cooling hardware if required by the final enclosure
- USB cable and programming cable

## Build Checklist

- [ ] Verify every module's operating voltage.
- [ ] Check polarity before applying power.
- [ ] Inspect solder joints and connector orientation.
- [ ] Confirm the SD card is recognized.
- [ ] Confirm the display initializes.
- [ ] Confirm GPS wiring and module power.
- [ ] Confirm expansion modules are electrically isolated before testing.
- [ ] Use a current-limited supply during first power-up where possible.
- [ ] Keep antennas and RF modules installed according to their manufacturer's specifications.

## Known Reference Prices

The earlier project notes recorded:
- CYD — ₱543
- PCB — ₱84
- Female connector — ₱64–₱200
- GPS — approximately ₱200

These are **reference prices, not guaranteed current prices**.

## RF / Wireless Safety

The presence of an RF-capable module does not authorize interference or unauthorized transmission. Test only equipment and frequencies you are legally permitted to use.
