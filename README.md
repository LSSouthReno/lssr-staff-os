# LS South Reno — Staff Operating System

EOS (Entrepreneurial Operating System) implementation for Living Stones South Reno staff.

## How It Works

1. **`index.html`** — the staff-facing webpage. Open directly or host via GitHub Pages.
2. **`data/eos-data.json`** — the live data file. Updated by the Google Apps Script from the Google Sheet.

## Updating Data

Edit the **LS South Reno Staff OS** Google Sheet → click **🏛 Staff OS → Push to GitHub Now** in the menu.

The page fetches fresh data from this repo on every load.

## Hosted URL

`https://lssouthreno.github.io/lssr-staff-os/`

## Sections

- **V/TO** — Vision/Traction Organizer
- **VOT** — Values, Observable, Teachable (Humble · Hungry · Happy · Honest)
- **Accountability Chart** — Staff roles and ownership
- **Scorecard** — Weekly metrics with owners and goals
- **Rocks** — Quarterly priorities with On Track / Off Track status
- **Team / WG** — Staff Working Genius map and team analysis
- **Meeting Pulse** — L10, QBOP, 1-on-1, and annual planning rhythms
- **IDS** — Issues list with Identify · Discuss · Solve process
- **⚙ Setup** — Google Sheets + Apps Script connection guide
