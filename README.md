# Content Hours Dashboard

An interactive, single-file HTML dashboard showing term-to-date content-hours consumption across a contracted customer book, with uncontracted usage flagged for audit. Click any customer row for monthly detail.

**Demo data:** All customer names in this version have been replaced with fictional organization names. No real customer identities are present. Numbers, statuses, dates, CSM names, and structure are otherwise unchanged from the source build.

## What's here

- `index.html` — the complete, self-contained dashboard. All data is inlined as JSON in a `<script id="DATA">` block; charts render via Chart.js loaded from a CDN.

## Viewing it

Open `index.html` directly in a browser, or publish it with GitHub Pages.

### Enabling GitHub Pages

GitHub Pages must be turned on manually in the repository settings:

1. Go to **Settings -> Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**.
4. Click **Save**.

Once published, the dashboard will be live at:

https://isosceleskr4mer.github.io/content-hours-dashboard/
