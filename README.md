# London School of Economics and Political Science (lse)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
