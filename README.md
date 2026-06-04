# National University of Colombia (national-university-of-colombia)

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
