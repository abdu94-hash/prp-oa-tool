# PRP for Osteoarthritis — Clinical Companion Tool

Free companion to *Platelet-Rich Plasma for Degenerative Osteoarthritis: Evidence, Clinical Applications, Safety, and Treatment Protocols* — Dr. Hafez Selim, MD, PhD (Selim Medical Press).

**Live site:** https://abdu94-hash.github.io/prp-oa-tool/

## What it does

Four modules, all running entirely in the browser:

1. **Candidacy screener** — eight-step selection sequence with absolute stop conditions, joint-specific evidence disclosure, pain-phenotype weighting, and consent/readiness checks.
2. **Product characterisation and dose** — calculates enrichment factor and absolute platelet dose, classifies leukocyte content, warns on volume outside the joint-specific range, and provides the fourteen-field documentation record.
3. **Evidence explorer** — 86 verified PubMed records, filterable by joint, study type, comparator, blinding, and direction of finding.
4. **Outcome tracker** — applies a threshold declared in advance, handles both scale directions, and classifies response including deterioration.

## Design constraints

- **Single file.** No build step, no dependencies, no framework.
- **No network.** Zero external requests, no analytics, no tracking, no cookies, no fonts loaded from anywhere.
- **No storage.** Nothing is saved or transmitted. Reloading discards everything.
- **Acceptance gate.** The tool will not run until the 15-clause terms of use are accepted.
- **Print bands.** Any printed output carries the not-medical-advice / not-a-medical-device banner.

## Deployment

1. Create a public repository named `prp-oa-tool`.
2. Upload `index.html`, `og-image.png`, `robots.txt`, `sitemap.xml`, `404.html`, `.nojekyll`, and this README.
3. Settings → Pages → Source: **Deploy from a branch** → Branch `main`, folder `/ (root)` → Save.
4. The site appears at `https://<username>.github.io/prp-oa-tool/` within a few minutes.

## Legal

Educational aid for licensed healthcare professionals. **Not medical advice. Not a medical device. No clinical recommendation is produced.** Platelet-rich plasma is not approved or cleared for the treatment of osteoarthritis by the FDA or any comparable authority known to the author.

The views expressed are the author's own and do not represent those of any current or former employer, client, institution, professional society, or regulatory authority.

Evidence cut-off: 21 August 2026. Re-verify before relying on anything here.

Corrections: abdu94@gmail.com

© 2026 Abdulhafez A. Selim. Published by Selim Medical Press.
