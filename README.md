# Battery Hybrid Digital Twin V29

Blind-fault demonstration with separated HTML/CSS/JS.

- C1, C2 and C12 are measured temperature sensors.
- One hidden fault is randomly injected into C3-C11.
- The DT is not told the fault location.
- Healthy thermal field starts at 36.5 C and develops a modest spatial gradient.
- Fault thermal footprint uses a 1-D thermal propagation signature to the three sparse sensors.
- Sparse candidate scoring uses thermal-pattern fit + correlation + aggregate electrical evidence.
- Debug log reports top candidate, runner-up, gap and estimated resistance increase every 10 s.

This is an illustrative engineering demo, not a validated BMS safety algorithm.
