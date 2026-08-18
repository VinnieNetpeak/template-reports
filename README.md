# template-reports

Anonymised sample reports published as static HTML pages.

**Live:** https://vinnienetpeak.github.io/template-reports/

## Files

| File | What it is |
|---|---|
| `index.html` | Landing page — links to every report |
| `executive-scorecard.html` | Company-level monthly scorecard (3 pages) |
| `network-pl-cashflow.html` | Multi-location P&L, cash flow, unit economics (3 pages) |
| `cinema-bi-demo.html` | Cinema operator BI mock-up, 7 views, Ukrainian (Chart.js inlined) |
| `favicon.ico`, `apple-touch-icon.png` | Icons |

## Before adding anything

Check the file for client identifiers **inside** the content, not just in the file name:
brand names, city or venue names, real location lists, POS / platform vendors, account IDs.
A file can have a clean name and still name the client on slide three.

## Rules for this repo

- All figures are synthetic. No client data, no client identifiers.
- File names: lowercase, hyphens only — no spaces, no `&`, no em dashes.
  Those characters break the published URL.
- Every report is a single self-contained HTML file (CSS and JS inline).

## Adding a report

1. Rename the file to a clean slug, e.g. `retail-margin-report.html`.
2. Upload it to the repo root (**Add file → Upload files**).
3. Add a card for it in `index.html`.
