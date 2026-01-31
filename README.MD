# smart_schematic

Interactive schematic demo showing how a single schematic can support
multiple build variants.

## Demo behavior

This demo uses the same schematic for all builds.
Differences are controlled by a variant selector.

### Variant selector
- **Version A**: All components populated
- **Version B**: Some components intentionally not populated

### Clicking components

**C3 (Capacitor)**
- Always populated in all variants
- Clicking C3 shows:
  - Real component photo
  - Datasheet link

**D6 (Diode)**
- Variant-dependent population
- Version A:
  - D6 is populated
  - Clicking shows datasheet
- Version B:
  - D6 is not populated
  - Clicking shows **NOT POPULATED**

### Purpose

The goal is to make component population explicit and prevent
wrong assumptions during receiving, staging, SMT, and rework.

This demo focuses on behavior, not schematic redraws.

Demo only. No proprietary data.
