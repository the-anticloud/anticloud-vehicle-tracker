# Ethics — VEHICLE_TRACKER

**Project:** VEHICLE_TRACKER  
**Category:** AUTOMOTIVE  
**Upstream:** see BENCH.json  
**Pinned commit:** `dd69e59b276e79b96bb459d8b1eda1501316086d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9f69ef7d4efc332a23b27d3bafb693daa1bea1c7e94db4063e3a5a565adeb659`  
**Date:** October 2026

## Position

VEHICLE_TRACKER is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
