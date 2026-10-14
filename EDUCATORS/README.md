# Educators — VEHICLE_TRACKER

**Project:** VEHICLE_TRACKER  
**Category:** AUTOMOTIVE  
**Upstream:** see BENCH.json  
**Pinned commit:** `dd69e59b276e79b96bb459d8b1eda1501316086d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9f69ef7d4efc332a23b27d3bafb693daa1bea1c7e94db4063e3a5a565adeb659`  
**Date:** October 2026

## Teaching with VEHICLE_TRACKER

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `9f69ef7d4efc332a23b27d3bafb693daa1bea1c7e94db4063e3a5a565adeb659` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
