# Wiring

This page will document the physical connections between the ESP32-S3 and Kobo-WX sensors.

## Prototype 1

ESP32-S3 → SHT31 using I2C on a solderless breadboard.

The exact GPIO pin assignments will be recorded here after the specific ESP32-S3 board pinout is confirmed.

| Signal | ESP32-S3 | SHT31 |
| --- | --- | --- |
| Power | TBD | VCC/VIN |
| Ground | GND | GND |
| I2C clock | TBD | SCL |
| I2C data | TBD | SDA |

## Rule

Do not assume GPIO assignments from another ESP32 board. Confirm the pinout for the actual Kobo-WX board before wiring.
