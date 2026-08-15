# Wiring

This page will document the physical connections between the ESP32 USB-C development board and the GY-BME280-5 sensor module.

## Prototype 1

ESP32 → GY-BME280-5 using I2C on a solderless breadboard.

The exact GPIO pin assignments will be recorded here after the specific ESP32 board pinout and the markings on the actual BME280 module are confirmed.

| Signal | ESP32 board | GY-BME280-5 |
| --- | --- | --- |
| Power | TBD | VIN/VCC — verify module marking |
| Ground | GND | GND |
| I2C clock | TBD | SCL/SCK — verify module marking |
| I2C data | TBD | SDA/SDI — verify module marking |

## Rules

- Do not assume GPIO assignments from another ESP32 development board.
- Do not assume a voltage connection solely from the product title; inspect the actual module and its regulator/level-shifting arrangement first.
- Confirm the pin labels on both physical boards before applying power.

Once verified, this page becomes the authoritative Kobo-WX wiring reference.
