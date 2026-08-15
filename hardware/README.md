# Hardware

This folder documents the physical Kobo-WX build: controller, environmental sensor, wiring, power, enclosure, and parts inventory.

## Actual hardware baseline

- ESP32 USB-C (Type-C) development board, listed as **CP2012**
- GY-BME280-5 / BME280 5V atmospheric pressure, temperature, and humidity sensor module
- Breadboard and jumper-wire prototyping
- USB-C power/programming
- Solderless first working prototype

> Note: ESP32 USB-C boards of this type commonly use a CP2102 USB-to-UART bridge. Our board listing says CP2012, so we will verify the actual board/chip marking before documenting model-specific details.

## Measurements available from the initial sensor

- Temperature
- Relative humidity
- Atmospheric pressure
- Derived values later, such as dew point
- Pressure presentation later in hPa and inHg
- Possible QNH/sea-level correction as a software feature

## Planned additions

- Enclosure and cable management
- Finalized wiring map after the exact board pinout is verified
- Calibration and placement notes

The goal is to understand every part of the chain before adding complexity.
