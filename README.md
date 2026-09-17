# PRP for Osteoarthritis — Clinical Companion Tool

Free companion to *Platelet-Rich Plasma for Degenerative Osteoarthritis: Evidence, Clinical Applications, Safety, and Treatment Protocols* — Dr. Hafez Selim, MD, PhD (Selim Medical Press).

**Live site:** https://abdu94-hash.github.io/prp-oa-tool/

## What it does

Four modules, all running entirely in the browser:

1. **Candidacy screener** — eight-step selection sequence with absolute stop conditions, joint-specific evidence disclosure, pain-phenotype weighting, and consent/readiness checks.
2. **Product characterisation and dose** — calculates enrichment factor and absolute platelet dose, classifies leukocyte content, warns on volume outside the joint-specific range, and provides the fourteen-field documentation record.
3. **Evidence explorer** — 87 verified PubMed records, filterable by joint, study type, comparator, blinding, and direction of finding.
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

## Changelog

**16 September 2026**
- AAPM&R guidance entry relabelled from "Favorable" to "Consensus", with a note that matches the statement's own framing (expert opinion and limited evidence; consideration for selected mild-to-moderate knee OA; calls for dose-dependent RCTs).
- The dose calculator no longer treats 10 × 10⁹ platelets as a reference to aim for: all dose notes now state that no minimum, maximum or optimal clinical dose has been established. The Dório 2021 characterized dose (≈1.4–5 × 10⁹, negative) is given for context.
- Dório 2021 corrected from "Mixed" to "No benefit", with the product characterization from the full text.
- Chu 2022 (n = 610, sham-controlled, 60-month follow-up) added; its structural claim is flagged as unreplicated.
- Practice readiness gains a tenth item: an individualized, documented medication plan coordinated with the responsible prescriber.
- The non-responder result now points to rechecking the diagnosis and discussing alternatives, and warns against inferring underdosing from non-response.
- Evidence cut-off moved to 16 September 2026.

## Legal

Educational aid for licensed healthcare professionals. **Not medical advice. Not a medical device. No clinical recommendation is produced.** Platelet-rich plasma is not approved or cleared for the treatment of osteoarthritis by the FDA or any comparable authority known to the author.

The views expressed are the author's own and do not represent those of any current or former employer, client, institution, professional society, or regulatory authority.

Evidence cut-off: 16 September 2026. Re-verify before relying on anything here.

Corrections: abdu94@gmail.com

© 2026 Abdulhafez A. Selim. Published by Selim Medical Press.
