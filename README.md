# Sunshine City Consulting, LLC — Website (v0.1 Draft)

First draft for Stephen's review. Not a launch. Date: November 22, 2026.

Do not deploy or publish this site live before the Sunbiz LLC filing is confirmed (retry Mon Nov 23, ~8:30 AM EST). Uploading the code to the private GitHub repo for review is fine; going live is not.

## Structure

Clean URLs — one `index.html` per folder. All pages share `styles.css`.

```
index.html                          Home
services/index.html                 Services hub
services/nexus-analysis/            Nexus analysis
services/multi-state-taxability-analysis/   Multi-state taxability analysis
services/exposure-assessments/      Exposure assessments
services/notice-resolution/           Notice resolution
services/audit-defense/             Audit defense
services/voluntary-disclosure/      Voluntary disclosure
services/reverse-audits/            Reverse audits
services/penalty-abatement/         Penalty abatement
meet-the-firm/index.html            Meet the Firm
contact/index.html                  Contact (email link only)
salty-snacks/index.html             SALTy Snacks resource page (14 LinkedIn posts, newest first)
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
- Client feedback: the "Recommendations for Stephen" section on Meet the Firm
  carries the two verified LinkedIn recommendations (Ruth Faust, Sep 12, 2022;
  Paul Schechter, Jul 8, 2022 — both CFGI), quoted verbatim with
  role/employer/date labels. No other testimonials, client quotes, client
  names, or case results.
- Never name Forvis Mazars or any expert network, and never say Stephen is
  available for expert-network consultations.
- No wholesale resale, no paid newsletter/course/templates, no additional
  service pages beyond the eight approved ones (indirect tax due diligence
  is an open question).
- No invented services, team members, or claims beyond the record.
- Contact is by email link only — no phone number, no contact form.
- Copy was reviewed by Hermes (Dot) and verified by Metatron on Nov 22, 2026;
  no `<!-- PROPOSED -->` markers remain. The Privacy Policy and Terms of Use
  still carry private-preview markers ([Confirm...], [Effective date]) that
  must be resolved before any public version.
