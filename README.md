# AS GRC Copilot

A practical, browser-based GRC workspace prototype for cybersecurity risk management, ISO/IEC 27001 control tracking, audit evidence organization, and management visibility.

## Current status
Early prototype — built for workflow exploration and CEO review. Not production-ready.

## Try it locally
1. Download or clone this repository.
2. Open `app/index.html` in a modern browser.
3. No build step, paid API, account, or server is required.

## Current modules
- **Overview:** summary metrics and work queue.
- **Risk register:** create, edit, search, filter, score, and export risk records.
- **ISO controls:** starter sample of ISO/IEC 27001:2022 controls with applicability and implementation tracking.
- **Audit evidence:** track evidence descriptions, references, owners, review dates, and status.
- **Data portability:** JSON backup/import and CSV exports.

## Important limitations
- Data is stored in the current browser profile using local storage; there is no server-side database, user authentication, encryption-at-rest guarantee, or team synchronization.
- Do not enter confidential, personal, regulated, customer, or production banking information.
- The included control list is a small starter sample, not the complete ISO/IEC 27001:2022 Annex A control set. Verify licensed standard content and organizational applicability independently.
- Risk rating thresholds are illustrative. Each organization must approve its own methodology, appetite, escalation thresholds, and acceptance criteria.
- This prototype does not provide certification, legal advice, audit assurance, or a guarantee of compliance.

## Documentation
- [User guide](docs/USER-GUIDE.md)
- [Product roadmap](docs/PRODUCT-ROADMAP.md)
- [Service offer](docs/SERVICE-OFFER.md)
- [Client discovery checklist](docs/CLIENT-DISCOVERY.md)
- [Client outreach template](docs/OUTREACH-TEMPLATE.md)

## Roadmap
See [Product roadmap](docs/PRODUCT-ROADMAP.md). Next priorities include usability testing, security review, accessible validation, a complete control catalog sourced appropriately, and an approved hosting/data architecture before any multi-user deployment.
