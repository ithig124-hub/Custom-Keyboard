# Keyboard Build Log

## 2026-07-15

- Signed up for the Hack Club keyboard grant program (keeb.hackclub.com).
- Decided on a **60% layout** (~61 keys), wired via USB-C (no wireless — keeping scope
  manageable for a first custom PCB build).
- Decided to add **per-key RGB** (SK6812 MINI-E) as the one "extra" feature. Skipped
  rotary encoder and OLED display to keep complexity down.
- Drafted initial BOM (`bom.csv`):
  - Orpheus Pico (MCU)
  - MX-style switches x65 (61 + spares)
  - 1N4148 diodes x65
  - DSA blank keycaps x65
  - SK6812 MINI-E LEDs x65
  - 60% stabilizer kit
  - M3x16mm screws + M3x5x4mm heatset inserts
  - Custom PCB (still needs to be designed — not part of the grant's provided parts list)
  - Case/plate material (also not in the grant's provided parts list)
- Estimated total cost: **~$93**
- Still need to:
  - Confirm real vendor prices before finalizing BOM
  - Confirm SK6812 MINI-E reel quantity (does 1 reel cover 61+ LEDs?)
  - Sketch actual key layout / switch placement for PCB design
  - Design PCB in KiCad
  - Design case/plate

## Next steps
- [ ] Finalize layout sketch
- [ ] Start PCB design (docs: Designing the PCB)
- [ ] Design case
- [ ] Write firmware (QMK, since board is wired)
