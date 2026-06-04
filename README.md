# London School of Economics and Political Science (lse)

The London School of Economics and Political Science (LSE) is a public research university in London, United Kingdom, ranked #38 in the QS World University Rankings 2025 and globally renowned for the social sciences. LSE does not run a unified public developer portal; its confirmed machine-readable footprint is concentrated in library and open-research infrastructure plus federated identity. This repository catalogs that footprint as an APIs.json profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/lse/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=lse-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, United Kingdom, Library, Open Research, Repository, OAI-PMH, IIIF, Identity

## APIs

- **LSE Research Online OAI-PMH** — EPrints institutional repository exposing research metadata via OAI-PMH 2.0. Docs: https://www.openarchives.org/OAI/openarchivesprotocol.html | Repository: https://researchonline.lse.ac.uk/ | Registry: https://www.re3data.org/repository/r3d100011218
- **LSE Digital Library (IIIF / OAI-PMH)** — Quartex-powered digitised collections offering IIIF manifests and OAI-PMH metadata harvesting on request. Docs: https://digital.library.lse.ac.uk/about
- **LSE Library Search (Ex Libris Alma / Primo)** — Discovery and resource management on Alma/Primo; programmatic access follows the Ex Libris developer model. Docs: https://www.lse.ac.uk/library/using-the-library/catalogues
- **LSE Identity / SAML2 Single Sign-On** — SAML2 federated authentication (Shibboleth / UK Access Management Federation) for student, staff and learning systems. Docs: https://moodle.lse.ac.uk/auth/saml2/selectidp.php

## Plans

- [plans/lse-plans-pricing.yml](plans/lse-plans-pricing.yml)

## Rate Limits

- [rate-limits/lse-rate-limits.yml](rate-limits/lse-rate-limits.yml)

## FinOps

- [finops/lse-finops.yml](finops/lse-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.lse.ac.uk/
- LinkedIn: https://www.linkedin.com/school/the-london-school-of-economics-and-political-science/
- Twitter: https://twitter.com/LSEnews
- Authentication: https://moodle.lse.ac.uk/auth/saml2/selectidp.php
- Plans: plans/lse-plans-pricing.yml
- Rate Limits: rate-limits/lse-rate-limits.yml
- FinOps: finops/lse-finops.yml
- Review: review.yml

## Notes

- LSE (the university) is distinct from LSEG (London Stock Exchange Group, developers.lseg.com) — none of the LSEG financial APIs are included here.
- No official LSE GitHub organization exists; `github.com/lse` is an unrelated systems-programming lab. Course/timetable libraries found in the wild are third-party community projects, not official LSE APIs, and are not cataloged.
- The LSE Research Online repository root and its OAI-PMH endpoint returned HTTP 500 during the 2026-06-03 review; the base URL is nonetheless registered with re3data, SHERPA and ROAR.
- Library, repository and identity interfaces are largely gated by institutional affiliation or federation membership rather than open self-service. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
