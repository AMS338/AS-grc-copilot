# AS GRC Copilot — Prototype User Guide

## Open the prototype
Open `app/index.html` in a modern desktop or mobile browser. No build step, account, server, or API key is required.

## Add a risk
1. Select **Add risk**.
2. Enter a concise risk title.
3. Add the affected asset/process and an accountable owner where known.
4. Select likelihood and impact from 1 to 5.
5. Record the treatment status, target date, and mitigation plan.
6. Select **Save risk**.

## Scoring model
The prototype calculates an inherent score as:

`Likelihood × Impact` (range 1–25)

| Score | Rating |
|---:|---|
| 1–5 | Low |
| 6–11 | Medium |
| 12–19 | High |
| 20–25 | Critical |

This is a simple illustrative model. An organization should approve its own risk methodology, thresholds, definitions, appetite, and escalation rules before operational use.

## Manage records
- Use search to find records by title, asset, owner, or treatment.
- Use the rating selector to filter the register.
- Select **Edit** to update a record.
- Select **×** to delete a record after confirmation.

## Export and backup
- **Export CSV** creates a spreadsheet-friendly risk register.
- **Backup JSON** downloads a complete JSON backup that can be retained separately.

## Data handling and limitations
- Records are stored in the current browser profile using local storage.
- Data is not synchronized between devices or users.
- Clearing browser storage can remove records; export backups regularly.
- Do not enter confidential, personal, regulated, customer, or production banking data.
- This is an early prototype, not an audited product, risk-management system of record, legal opinion, compliance determination, or certification service.
