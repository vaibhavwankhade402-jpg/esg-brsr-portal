# ESG & BRSR Intelligence Portal

A reusable static portal for the SRCE ESG rating assignment.

## Two modes

### 1. Analyse one company
- Enter any Indian listed company.
- Upload its BRSR or Sustainability Report.
- Extract candidate ESG evidence in the browser.
- Review/edit evidence, source pages and scores.
- Calculate Environmental, Social, Governance and overall ESG scores.

### 2. Compare two companies
- Enter Company A and Company B.
- Upload both reports.
- Compare the same ESG themes side by side.
- Scan BRSR Principles 1–9.
- Flag potentially comparable versus not-yet-comparable metrics.
- Avoid false comparisons caused by different baselines, units or reporting boundaries.

## GitHub Pages setup

1. Create a **public** GitHub repository, for example `esg-brsr-portal`.
2. Upload `index.html` from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under the publishing source, select **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. GitHub will publish the site at the repository's Pages URL.

GitHub Pages uses `index.html` as the entry file.

## Technical note

The portal is static HTML/CSS/JavaScript. PDF text extraction is performed in the user's browser with PDF.js from a public CDN. No server-side Python is required.

## Academic note

The ITC FY 2024-25 values are included as a demonstration baseline from the project. The portal is not an official ESG rating agency tool.

Automatic extraction is only a candidate-finding aid. Before a final rating, verify:
- reporting year
- metric definition
- unit
- organisational boundary
- baseline
- target/benchmark
- source page

Do not treat missing information as zero. Use manual review or Not Comparable.
