# Lymphoma Guide — Pro Edition

A responsive, English-language static website for lymphoma patient and caregiver education.

## Included
- Home page with clear entry points
- Lymphoma types overview
- Guided information navigator (not a diagnostic tool)
- Diagnosis and tests
- Treatment categories and questions for clinicians
- Living with lymphoma and support
- Searchable/filterable trusted resource directory
- Interactive appointment checklist with copy and print
- Privacy and medical disclaimer
- Responsive layout, keyboard focus states, skip link, mobile navigation, and optional dark theme
- No build step or third-party JavaScript dependency

## Run locally
1. Extract this ZIP.
2. Open `index.html` in a modern browser.
3. Optional local server: from this folder run `python -m http.server 8000`, then visit `http://localhost:8000`.

## Publish
Upload the contents of this folder to a static hosting service such as GitHub Pages, Netlify, or Cloudflare Pages. Keep `index.html` at the root.

## Before public launch
- A qualified hematology/oncology clinician should review all medical content.
- Recheck links, local support details, and the date-stamp.
- Add no reviewer name or endorsement until it has been genuinely approved.
- This version does not collect patient-submitted data. If forms, analytics, accounts, or health-data storage are added, conduct appropriate privacy/security/legal review first.
- The site is educational only; it does not diagnose or recommend individualized treatment.

## Structure
- `index.html`
- `types.html`
- `subtype-navigator.html`
- `diagnosis.html`
- `treatment.html`
- `living-support.html`
- `resources.html`
- `appointment-checklist.html`
- `privacy.html`
- `assets/styles.css`
- `assets/main.js`
- `assets/favicon.svg`
