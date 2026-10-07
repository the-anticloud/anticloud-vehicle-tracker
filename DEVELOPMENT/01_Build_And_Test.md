# Build and Test

**Project:** `VEHICLE_TRACKER`
**Upstream:** https://github.com/nicedoc/vehicle-tracker
**License:** MIT

## Quick Start

```bash
git clone https://github.com/nicedoc/vehicle-tracker
cd vehicle-tracker
pip install -r requirements-anticloud.txt
python anticloud_main.py --offline --pax-local
```

## Anticloud Improvements Applied

1. PAX L5 Narrow L2 General 27B local ADAS inference — in-vehicle, air-gapped
2. AIOSS tamper-evident vehicle event data recorder (EDR) chain
3. AES-256 encryption for all OBD/CAN bus data and trip logs
4. Single-binary ECU software package for production flash
5. Zero-cloud: all AI features operate without cellular connectivity
6. GPU/CPU equalizer: perception on embedded GPU, path planning on CPU
7. Open OBD-II interface: replaces proprietary diagnostic middleware
8. AUTOSAR-compatible module wrappers for OEM integration

## Benchmark Targets

| Metric | Target |
| --- | --- |
| Latency | Primary inference task: <5s on CPU, <1s on GPU |
| Throughput | Batch processing: >100 items/hour on single CPU server |
| Memory | <8GB RAM for standard deployment |
| Accuracy | Task-specific accuracy within 5% of cloud-API baseline |

## Build Status

Not yet measured. Run verified build and record actual figures above.
