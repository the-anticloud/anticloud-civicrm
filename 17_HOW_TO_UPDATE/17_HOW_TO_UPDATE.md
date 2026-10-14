# How to Update — CIVICRM

**Project:** `CIVICRM`
**Category:** POLICE_CIVIC
**Domain:** police civic
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
CIVICRM --version
CIVICRM check-update
```

### Applying Updates
```bash
pip install --upgrade CIVICRM
```

### Rolling Back
```bash
pip install CIVICRM==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
