# Technical Architecture — VEHICLE_TRACKER

**Upstream:** [https://github.com/nicedoc/vehicle-tracker](https://github.com/nicedoc/vehicle-tracker)
**License:** MIT
**Category:** AUTOMOTIVE
**Anticloud Integration:** PAX L5 Narrow L2 General 27B + AIOSS + Offline-First

## Upstream Description

OBD2 vehicle telemetry tracking

## Anticloud Architectural Changes

1. PAX L5 Narrow L2 General 27B local ADAS inference — in-vehicle, air-gapped
2. AIOSS tamper-evident vehicle event data recorder (EDR) chain
3. AES-256 encryption for all OBD/CAN bus data and trip logs
4. Single-binary ECU software package for production flash
5. Zero-cloud: all AI features operate without cellular connectivity
6. GPU/CPU equalizer: perception on embedded GPU, path planning on CPU
7. Open OBD-II interface: replaces proprietary diagnostic middleware
8. AUTOSAR-compatible module wrappers for OEM integration

## Integration Points

- **PAX Inference Socket:** Local HTTP endpoint at `127.0.0.1:11434/v1/chat` — same OpenAI-compatible API, zero cloud
- **AIOSS Hook:** Every write operation calls `aioss_append(event, payload)` before commit
- **Encryption Layer:** All file I/O routed through `anticloud_crypto.encrypt_at_rest()`
- **Single Binary Build:** `pyinstaller anticloud_vehicle_tracker.spec` or `go build -o vehicle_tracker`

## Deployment Modes

| Mode | Hardware | Notes |
| --- | --- | --- |
| Edge CPU | Raspberry Pi 4 / Intel NUC | Full feature set, PAX on CPU |
| Desktop GPU | RTX 3060 / A10 | PAX GPU inference, <1s latency |
| Server | 2× A100 | Full batch throughput |
| Air-gapped | Any x86/ARM | Zero network dependency |