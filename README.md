# DK Cricket Ops

A responsive cricket tournament organiser app for fixtures, teams, payment tracking, expenses and finance summaries.

## Features
- Dashboard for expected fees, payments received, expenses and net cash position
- Match scheduling for AK Club DY Patil Ground, MCG Ground and Lords of Maval
- Team registration and payment ledger with outstanding balances
- Ground-wise expense log
- Finance CSV export and JSON backup/restore
- Responsive design for desktop and mobile

## Deploy on GitHub Pages
1. Open repository **Settings → Pages**.
2. Under Build and deployment, select **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then Save.
4. Wait for the deployment and open the Pages URL.

## Data storage
This initial version uses browser local storage. Data does not automatically sync across browsers or devices. Download regular JSON backups under Backup & Settings. Shared multi-device data requires a backend such as Supabase with authentication and access controls.

Finance figures reflect only entries you record; reconcile them with bank statements. This app is an organiser ledger, not tax/accounting software.
