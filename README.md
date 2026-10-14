# SEO Blog Content Audit

A static, single-page content audit tool for Biztek Apps.

## Run locally
Open `index.html` in Chrome, Edge, or Firefox. No installation or server required.

## Deploy to Vercel
1. Upload this folder to a GitHub repository.
2. In Vercel, select **Add New > Project**, import the repository.
3. Framework preset: **Other**. No build command required. Output directory: leave blank.
4. Click **Deploy**.

Alternatively, install Vercel CLI and run `vercel` from this folder.

## Data and scoring
- Audits are stored in browser `localStorage` only. No server database, accounts, or cross-device sync.
- Use **Backup all JSON** regularly; import backups to restore data.
- Export CSV for spreadsheet analysis.
- Score is a *provisional weighted checklist pass rate*. Each category's pass fraction is multiplied by its proposed category weight, then normalized over categories with answered Pass/Issue items. N/A and unanswered items are excluded. This is not a validated writer performance score.
- Scores should not be compared across writers until responsibility ownership, evidence rules, and scoring are finalized.
