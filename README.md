# DK Cricket Ops — Workbook-style Web App

A fresh, single-page cricket ground scheduling and team-payment workbook inspired by the Excel file used for DK Cricket Ops.

## Sheets
- **Ground Schedule** — Excel-style wide table with fixed Date / Day / Ground columns, weekend rows through 28 February 2027, seven booking/time slots, booking notes, ground status, tournament columns, and payment-received team names.
- **Leather Payment Tracker** — automatically derives tennis fixtures and up to two leather matches from Ground Schedule. Team A and Team B payments are tracked independently using Pending / Paid / Not Applicable.
- **Tournament Teams** — editable team directory for each tournament.
- **Round Robin Fixtures** — tournament pairings with editable date, ground, time, status and payment columns.
- **How to Schedule** — workbook workflow notes.

## Workflow
1. Enter a fixture in a Ground Schedule time slot using `Team A vs Team B`.
2. Open Leather Payment Tracker; the fixture and each team's independent payment dropdown appear automatically.
3. Use the same row for each date. The first weekend row defaults to AK Club DY Patil Ground; the second is blank for an actual MCG Ground or Lords of Maval booking.
4. Changes autosave in the current browser. Use **Download Backup** and **Restore Backup** to move the data between devices.

## Hosting and storage
This is a static GitHub Pages app and requires no build step. Data is stored in the browser's local storage; GitHub Pages does not sync edits between different devices or users. For shared live collaboration, connect a hosted database such as Supabase in a future step.

## Deploy
GitHub Pages deploys the root `index.html` from the repository's configured workflow.
