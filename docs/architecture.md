# Kobo-WX Architecture

## Phase 1 — USB prototype

```text
SHT31
  │ I2C
  ▼
ESP32-S3
  │ USB serial
  ▼
Computer
```

The ESP32-S3 reads the sensor and sends measurements over USB. This keeps the first system small and easy to debug.

## Phase 2 — Structured data

The ESP32-S3 will emit machine-readable measurements, likely JSON lines containing temperature, relative humidity, dew point, and later pressure.

## Phase 3 — Local network

```text
Sensors → ESP32-S3 → local Wi-Fi → Kobo network service → desktop/readout
```

The project remains local-first. Network capability should be added only after the USB prototype is reliable.
