# Battery Hybrid Digital Twin V15 — Fault-First Demo

## What changed
- Cell 6 fault is active from the first frame; no 60-second wait.
- The page automatically starts streaming when opened.
- Removed the **Start Live Stream** button.
- Only **Pause** and **Reset** remain.
- Cell 6 is visually marked **FAULT** and its temperature, SOH and resistance are intentionally abnormal.
- Fault severity ramps during the first 90 seconds.

## Fault model
Cell 6 is intentionally degraded with:
- Internal resistance: ~1.55× nominal at t=0, ramping toward ~2×.
- Effective SOH: ~88% at t=0, gradually reducing toward ~86%.
- Additional I²R heating drives Cell 6 temperature above the surrounding cells.

This is an illustrative engineering demo, not a validated BMS or battery safety estimator.
