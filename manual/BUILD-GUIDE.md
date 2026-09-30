# Build & Inspection Guide

## 1. Prepare

Lay out the CYD/ESP32 board, expansion modules, storage, connectors, power parts, and enclosure parts.

## 2. Inspect

Check for:
- solder bridges
- reversed capacitors
- loose connectors
- damaged PCB traces
- exposed conductors that could short against the enclosure

## 3. Power

Use the correct voltage for each module. Do not assume every ESP32 accessory is 5 V tolerant. Measure rails before connecting sensitive peripherals.

## 4. Functional Checks

Test one subsystem at a time:
- display
- storage
- GPS
- individual expansion modules
- user controls
- enclosure and cable routing

## 5. Final Assembly

Secure boards against movement, provide strain relief for cables, and ensure antennas are not crushed or shorted.

## 6. Documentation

Record:
- board revision
- firmware version
- module versions
- pin map
- known issues
- changes from the previous build

## Safety

This is a documentation guide, not a substitute for the manufacturer's electrical specifications. Wireless capabilities must be operated only within applicable laws and authorized test environments.
