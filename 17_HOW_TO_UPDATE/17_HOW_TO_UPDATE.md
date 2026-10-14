# How to Update — PX4

**Project:** `PX4`
**Category:** SPACE_AEROTECH
**Domain:** space aerotech
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
PX4 --version
PX4 check-update
```

### Applying Updates
```bash
pip install --upgrade PX4
```

### Rolling Back
```bash
pip install PX4==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
