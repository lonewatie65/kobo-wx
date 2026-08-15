# Software

Kobo-WX software will be developed after the initial hardware path is documented and verified.

## Planned areas

### MicroPython

Code running directly on the ESP32-S3:

- Sensor detection
- Sensor readings
- Derived weather values
- USB serial output
- Later local Wi-Fi communication

### Desktop / receiver

Python software running on a Kobo computer:

- Receive measurements
- Parse structured data
- Display current conditions
- Later store/log measurements

Software implementation will be developed on a separate feature branch after the hardware foundation is reviewed.
