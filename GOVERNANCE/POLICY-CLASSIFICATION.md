# Policy Classification (Public / Internal / Restricted)

## Purpose
Prevent privacy leaks and keep operations audit-ready. This repo is the **public operating manual**, not a student records system.

## Classification Levels
### 1) PUBLIC
Safe to publish publicly.
Examples:
- Program overview
- Tuition/fee schedule (family-facing)
- Withdrawal/refund policy
- Lane separation policy
- Academic model (high-level)
- Outcome reporting (aggregated)

### 2) INTERNAL
For staff/contractors only. Can be stored in GitHub if it contains **no personal data** and no sensitive operational secrets.
Examples:
- Role cards
- Process checklists
- Training outlines (no names)
- Vendor onboarding process (no bank info)

### 3) RESTRICTED (DO NOT COMMIT TO GITHUB)
Never store in this repo. Store in secure private storage.
Examples:
- Student names, records, grades, transcripts, IEP/504
- Immunization records
- Staff background check reports
- Banking/W-9/vendor forms
- Any credentials, passwords, API keys
- Incident reports with identifying details

## Enforcement Rules
1) If it contains **PII** (personally identifying information), it is RESTRICTED.
2) If it contains **financial account details**, it is RESTRICTED.
3) If it contains **background check details**, it is RESTRICTED.
4) Publish only **sanitized templates** with placeholders: [TBD], [REDACTED].

## Where RESTRICTED items live
Restricted Storage System: [TBD private drive/system]
Custodian: [TBD role]
Access: least privilege, logged access

## Review cadence
Policy owner reviews classification quarterly and whenever new tools/vendors are added.