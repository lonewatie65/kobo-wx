# Kobo-WX Roadmap

## Phase 1 — Hardware foundation

- [x] Create dedicated Kobo-WX repository
- [x] Establish hardware documentation structure
- [ ] Confirm exact ESP32-S3 board and pinout
- [ ] Breadboard SHT31 connection
- [ ] Power-on test

## Phase 2 — MicroPython

- [ ] Install/confirm MicroPython on ESP32-S3
- [ ] Detect SHT31 over I2C
- [ ] Read temperature
- [ ] Read relative humidity
- [ ] Calculate dew point
- [ ] Output readings over USB serial

## Phase 3 — Pressure

- [ ] Select pressure sensor
- [ ] Add pressure measurement
- [ ] Display hPa
- [ ] Display inHg
- [ ] Explore local sea-level/QNH correction

## Phase 4 — Kobo network

- [ ] Define JSON data format
- [ ] Connect ESP32-S3 to local Wi-Fi
- [ ] Build local receiver/service
- [ ] Create desktop readout

## Phase 5 — Physical station

- [ ] Choose enclosure
- [ ] Finalize wiring
- [ ] Decide whether permanent connections require soldering
- [ ] Sensor placement testing
- [ ] Calibration/comparison testing
