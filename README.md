# Gersh Elite Motors — Invoicing App

A simple, free, single-page invoicing app for Gersh Elite Motors Ltd.

**Live app:** enable GitHub Pages on this repo (see below) to get a public link.

## Features

- **New invoice** — enter client details and line items, auto-calculated totals, auto-incrementing invoice numbers (`GEM-126`, `GEM-127`, ...)
- **All invoices** — track every invoice, toggle paid / unpaid status, view or delete
- **Dashboard** — total invoiced, paid vs unpaid, monthly trend chart, recent invoices
- **Print / save as PDF** — every invoice opens in a clean printable layout matching the company's invoice format

## How data is stored

This app stores all invoice data in your **browser's local storage** — there is no external database or server. That means:

- Data is saved automatically as you create and update invoices
- Data stays on the device/browser you used to create it — it will **not** sync between different computers or phones
- Clearing your browser's site data/history for this page will erase the invoices
- Each person using the app on their own device will have their own separate set of invoices

If you need invoices to be shared and synced across multiple staff or devices, the app would need to be upgraded to use a real backend database (for example Supabase), similar to the LoanTrack app.

## Running it locally

Just open `index.html` in any web browser. No installation or build step needed.

## Hosting on GitHub Pages

1. Push this repo to GitHub (see setup steps provided separately)
2. Go to the repo's **Settings → Pages**
3. Under **Source**, select the `main` branch and `/ (root)` folder
4. Save — GitHub will give you a live URL, usually:
   `https://<your-username>.github.io/<repo-name>/`

## Files

- `index.html` — the entire app (HTML, CSS, and JavaScript in one file)
