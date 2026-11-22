# Sunshine City Consulting, LLC — Website (v0.1 Draft)

First draft for Stephen's review. Not a launch. Date: November 22, 2026.

Do not deploy or publish this site live before the Sunbiz LLC filing is confirmed (retry Mon Nov 23, ~8:30 AM EST). Uploading the code to the private GitHub repo for review is fine; going live is not.

## Structure

Clean URLs — one `index.html` per folder. All pages share `styles.css`.

```
index.html                          Home
services/index.html                 Services hub
services/nexus-analysis/            Nexus analysis
services/exposure-assessments/      Exposure assessments
services/audit-defense/             Audit defense
services/voluntary-disclosure/      Voluntary disclosure
services/reverse-audits/            Reverse audits
services/penalty-abatement/         Penalty abatement
meet-the-firm/index.html            Meet the Firm
contact/index.html                  Contact (email link only)
privacy-policy/index.html           Privacy Policy (short draft)
terms-of-use/index.html             Terms of Use (short draft)
assets/hero.webp                    Hero image — sunrise over the St. Petersburg
                                    skyline and bay, pelican in flight, no text
assets/logo-transparent.png         Logo for light backgrounds (header)
assets/logo-white.png               Logo for dark backgrounds (footer on navy)
styles.css                          One shared stylesheet
README.md                           This file
```

## How to preview

Open `index.html` in a browser, or serve the folder with any static server,
e.g. `python3 -m http.server` from this directory.

## Review

- **Claude reviews this code via the GitHub repo.** This folder is the source
  that gets pushed to the repo; do not edit the code in two places.
- **Google Drive is the docs hub** (site map, plans, tracker, handoffs). Code
  lives here / in GitHub; documents live in Drive.
- Review loop: drafts go through the multi-model iterative review process
  (Gemini + Dot in parallel, Metatron verifies). Nothing is adopted or
  published without Stephen's word.

## Guardrails (binding — see the site map for the full list)

- No prices anywhere. The $200/hr network rate never appears.
- No testimonials, client quotes, client names, or case results. The client
  feedback section is omitted entirely until real LinkedIn recommendations
  are pulled and adapted.
- Never name Forvis Mazars or any expert network, and never say Stephen is
  available for expert-network consultations.
- No wholesale resale, no paid newsletter/course/templates, no seventh
  service page (indirect tax due diligence is an open question).
- No invented services, team members, or claims beyond the record.
- Contact is by email link only — no phone number, no contact form.
- Proposed wording is marked `<!-- PROPOSED: ... -->` in the HTML for
  Stephen to confirm (hero headline and supporting line, the three
  "how to engage" steps, the SALTy Snacks link, and the legal-page drafts).
