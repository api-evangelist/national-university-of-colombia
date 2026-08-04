# National University of Colombia (national-university-of-colombia)

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

The National University of Colombia (Universidad Nacional de Colombia, UNAL) is the country's largest public research university, ranked #219 in the QS World University Rankings 2025. This repository catalogs UNAL's public developer/API footprint as an APIs.json provider profile. UNAL does not publish a formal, documented public developer portal or REST API program; its most accessible programmatic surfaces are a DSpace institutional repository (OAI-PMH) and an open-data portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/national-university-of-colombia/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=national-university-of-colombia-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Colombia, Open Data, Institutional Repository, OAI-PMH

## APIs

- **Institutional Repository (DSpace / OAI-PMH)** — DSpace repository of theses, articles, books, and research data; registered with re3data/OpenDOAR as OAI-PMH enabled. Docs: https://www.re3data.org/repository/r3d100013982 — Portal: https://repositorio.unal.edu.co/
- **UNAL Open Data Portal** — Open datasets for public reuse; no documented API advertised. Docs: https://datosabiertos.unal.edu.co/

## Plans / Rate Limits / FinOps

- Plans: [plans/national-university-of-colombia-plans-pricing.yml](plans/national-university-of-colombia-plans-pricing.yml)
- Rate Limits: [rate-limits/national-university-of-colombia-rate-limits.yml](rate-limits/national-university-of-colombia-rate-limits.yml)
- FinOps: [finops/national-university-of-colombia-finops.yml](finops/national-university-of-colombia-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://unal.edu.co/
- GitHub: https://github.com/unal
- LinkedIn: https://www.linkedin.com/school/universidad-nacional-de-colombia/
- Review: [review.yml](review.yml)

## Notes

This profile reflects only publicly confirmable surfaces; no endpoints, keys, or signup flows were fabricated. The institutional repository is documented as OAI-PMH enabled (re3data/OpenDOAR), but the OAI-PMH request path probed during review returned HTTP 404 and must be re-verified against the current DSpace version before integration. The open-data portal does not advertise a documented API. The official UNAL website blocks automated clients but is the canonical domain.

## Maintainers

- Kin Lane — kin@apievangelist.com
