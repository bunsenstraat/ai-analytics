# Remix IDE Analytics Reports

Internal analytics reports for Remix IDE's AI feature, published via GitHub Pages.

## Structure

```
index.html                          # Report listing / homepage
reports/
  YYYY-MM-DD-report-name.html       # Individual reports
```

## Adding a new report

1. Drop the HTML file into `reports/` following the naming convention `YYYY-MM-DD-slug.html`
2. Add an entry to the `<ul class="report-list">` in `index.html`
3. Commit and push — GitHub Pages picks it up automatically

## Local preview

```bash
npx serve .
```

Then open http://localhost:3000
