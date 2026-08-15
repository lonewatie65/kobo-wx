# Kobo-WX Architecture

## Phase 1 — USB prototype

```text
GY-BME280-5
  │ I2C
  ▼
ESP32 USB-C development board
  │ USB serial
  ▼
Computer
```

The BME280 provides temperature, relative humidity, and atmospheric pressure from the start. The ESP32 reads the sensor and sends measurements over USB serial. This keeps the first system small and easy to debug.

## Phase 2 — Structured data

The ESP32 will emit machine-readable measurements, likely JSON lines containing temperature, relative humidity, pressure, and derived values such as dew point. Pressure can later be presented in hPa and inHg, with sea-level/QNH correction explored separately.

## Phase 3 — Local network

```text
GY-BME280-5 → ESP32 → local Wi-Fi → Kobo network service → desktop/readout
```

The project remains local-first. Network capability should be added only after the USB prototype is reliable.
