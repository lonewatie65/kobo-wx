# Kobo-WX Roadmap

## Phase 1 — Hardware foundation

- [x] Create dedicated Kobo-WX repository
- [x] Establish hardware documentation structure
- [x] Record actual controller and sensor hardware
- [ ] Confirm exact ESP32 board/chip markings and pinout
- [ ] Confirm GY-BME280-5 module pin labels
- [ ] Breadboard ESP32 ↔ BME280 I2C connection
- [ ] Power-on test

## Phase 2 — MicroPython

- [ ] Install/confirm suitable MicroPython firmware on the ESP32
- [ ] Detect BME280 over I2C
- [ ] Read temperature
- [ ] Read relative humidity
- [ ] Read atmospheric pressure
- [ ] Calculate dew point
- [ ] Display pressure in hPa and inHg
- [ ] Output readings over USB serial

## Phase 3 — Weather calculations and presentation

- [ ] Define JSON data format
- [ ] Explore local sea-level/QNH correction
- [ ] Decide which raw and derived values belong in the standard Kobo-WX output

## Phase 4 — Kobo network

- [ ] Connect ESP32 to local Wi-Fi
- [ ] Build local receiver/service
- [ ] Create desktop readout

## Phase 5 — Physical station

- [ ] Choose enclosure
- [ ] Finalize wiring
- [ ] Decide whether permanent connections require soldering
- [ ] Sensor placement testing
- [ ] Calibration/comparison testing
