# AS GRC Copilot — User Guide

## Start
Open `app/index.html` in a modern browser. No build step, paid API, account, or server is needed.

## Overview
The Overview page summarizes risk ratings, control records, evidence records, and outstanding work.

## Risk register
1. Open **Risk register** and select **Add risk**.
2. Enter a title, affected asset/process, owner, likelihood (1–5), impact (1–5), treatment status, target date, and treatment plan.
3. Save the record. Use search and rating filters to find it later.
4. Edit or delete records from the Actions column.
5. Export the register to CSV.

The prototype calculates inherent score as likelihood × impact (1–25), using illustrative bands: 1–5 Low, 6–11 Medium, 12–19 High, 20–25 Critical. Approve your own definitions and thresholds before operational use.

## ISO controls
The Controls page starts with a small sample of ISO/IEC 27001:2022 controls. Add or edit controls, record applicability, implementation status, owner, and an evidence reference. The list is not the full Annex A catalog; verify the authoritative standard and your organization's scope.

## Audit evidence
Record an evidence title, description, related control/risk, owner, approved repository reference, review date, and status. Store evidence files in an approved repository; this prototype does not upload or protect evidence files.

## Backup and restore
- **Export data** downloads a JSON backup of all modules.
- **Import backup** replaces all current records in this browser after confirmation.
- Each module has its own CSV export.

Keep backups in an approved secure location. Importing a backup replaces the records currently stored in the browser.

## Data handling and limitations
- Records are stored in this browser profile using local storage.
- There is no server database, user authentication, encryption-at-rest guarantee, or team synchronization.
- Do not enter confidential, personal, regulated, customer, or production banking information.
- This is an early prototype, not a system of record, legal opinion, audit opinion, certification service, or compliance guarantee.
