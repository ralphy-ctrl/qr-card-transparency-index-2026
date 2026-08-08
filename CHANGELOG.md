# Changelog

## 1.0.2 — 2026-08-08

- Enabled automatic archival through the official Zenodo GitHub integration.
- Prepared a documentation-only release to obtain a persistent DOI and improve citation and discovery.
- No service observations or comparison results changed from version 1.0.1.

## 1.0.1 — 2026-08-08

- Corrected GetQRcard scan analytics: scan events have no automatic deletion period in the reviewed implementation.
- Clarified that totals and breakdowns by device and country cover the full period in both plans.
- Clarified that only the day-by-day chart is windowed: 30 days on the free plan and 90 days on the annual plan.
- Documented that `ScanTracker::hashIp()` uses a salt that rotates daily, preventing cross-day linkage of the same IP-derived fingerprint by the service.
- Identified these implementation-level details as a maintainer code review because the application source code was not part of this public repository at release time.

## 1.0.0 — 2026-08-08

- Initial public research release.
- Added 14 services.
- Added first-party evidence URLs, field definitions, confidence labels, limitations, conflict-of-interest disclosure, and public correction procedure.
- Added a verified project profile for GetQRcard and Le Chemin Numérique ASBL.
- Documented the difference between the obsolete 20 July product architecture and current GetQRcard v0.5.8.
- Added verified English and French media copy, founder answers, and factual press angles.
- Added original English and French articles about QR-code and hosted-service permanence.
- Verified the 2026-08-08 correction of the publisher's GetQRcard article and removed the resolved conflict from the dataset row.
