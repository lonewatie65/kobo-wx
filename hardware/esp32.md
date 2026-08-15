# ESP32 USB-C Development Board

## Role

This ESP32 development board is the controller for Kobo-WX. It will read the BME280 environmental sensor and initially send measurements to a computer over USB serial.

## Identification

The board was sold/listed as:

**ESP32 CP2012 USB-C (Type-C) Development Board Module**

Similar ESP32 development boards commonly use a **CP2102** USB-to-UART bridge. We will not silently substitute that assumption: the actual board markings will be inspected and recorded before choosing drivers, firmware, or a definitive pinout.

## Initial use

1. Identify the exact ESP32 module and USB-to-UART chip markings.
2. Confirm the board pinout.
3. Install/confirm appropriate MicroPython firmware.
4. Connect the GY-BME280-5 on a breadboard.
5. Read temperature, relative humidity, and atmospheric pressure.
6. Output simple readings over USB serial.
7. Later output structured JSON and add local Wi-Fi networking.

## Design preference

The first build should remain simple, local, understandable, and easy to troubleshoot. Cloud services are not required.

## Status

Hardware acquired / identification and initial setup pending.
