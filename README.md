# National University of Colombia

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The National University of Colombia (Universidad Nacional de Colombia, UNAL) is the country's largest public research university, ranked #219 in the QS World University Rankings 2025. UNAL operates NO central developer portal, no API gateway and no documented public API program, and no llms.txt, ai.txt or .well-known/apis.json exists on unal.edu.co. What it does operate, on its own hosts, is scholarly infrastructure: a DSpace 7.6.5 institutional repository at bffrepositorio.unal.edu.co with an anonymous HAL+JSON REST API and an OAI-PMH 2.0 endpoint, and a second, independent OAI-PMH 2.0 endpoint on the Portal de Revistas UN (Open Journal Systems 3.4.0.10) serving 100+ journal sets. Beyond that its programmable footprint is relationships rather than engineering: six open datasets published as a named publisher scope on Colombia's national Socrata portal datos.gov.co, a self-hosted Ex Libris Aleph library catalog whose X-Services gate answers with a configuration error, Crossref membership (prefix 10.15446), a ROR identifier, and single sign-on brokered by a commercial vendor rather than a Shibboleth IdP. Colombia has no eduGAIN federation, so the identity-federation surface most universities have does not exist here.

**Areas:** Education · Higher Education · University · Public Research University · Colombia · Latin America · Open Data · Institutional Repository · Research Data · Scholarly Publishing · Library · OAI-PMH

## National University of Colombia on APIs.io

Everything profiled for National University of Colombia is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/national-university-of-colombia/](https://apis.io/providers/national-university-of-colombia/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [National University of Colombia OAI-PMH API](https://apis.io/apis/national-university-of-colombia/national-university-of-colombia-oai-pmh-api/) — OAI-PMH 2.0 metadata harvesting interface of the Repositorio Institucional UNAL, served from the university's own host. Twelve metadata prefixes (oai_dc,…
- [National University of Colombia REST - Core API](https://apis.io/apis/national-university-of-colombia/national-university-of-colombia-rest-core-api/) — Anonymous HAL+JSON read endpoints for the repository's community/collection structure on UNAL's own host. The contract documents only what a credential-free…
- [National University of Colombia REST - Discover API](https://apis.io/apis/national-university-of-colombia/national-university-of-colombia-rest-discover-api/) — Faceted, anonymous search across archived objects in UNAL's institutional repository, on the university's own host. Verified live 2026-09-01.
- [UNAL open data on datos.gov.co (Socrata)](https://apis.io/apis/national-university-of-colombia/datos-gov-co-publisher/) — UNAL's open data is not published on its own portal. datosabiertos.unal.edu.co is a static informational page with no catalogue and no API; the actual…
- [Crossref membership (DOI registrant)](https://apis.io/apis/national-university-of-colombia/crossref-membership/) — UNAL is a Crossref member in its own right — member id 6146, DOI prefix 10.15446 — with a second member record for its Faculty of Sciences, member id 21512,…
- [ROR organization identifier](https://apis.io/apis/national-university-of-colombia/ror-identifier/) — UNAL is registered in the Research Organization Registry as https://ror.org/059yx9a68 ("National University of Colombia", UNAL), carrying GRID…
- [SINAB library catalog (self-hosted Ex Libris Aleph)](https://apis.io/apis/national-university-of-colombia/library-catalog-aleph/) — catalogo.unal.edu.co runs Ex Libris Aleph on UNAL's own infrastructure (168.176.5.96), not on an Ex Libris cloud tenancy — the host verdict is institution,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [National University Of Colombia Agentic Access](https://apis.io/agentic-access/national-university-of-colombia/national-university-of-colombia-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [DSpace Collection](https://apis.io/schemas/national-university-of-colombia/national-university-of-colombia-collection/)
- [DSpace Community](https://apis.io/schemas/national-university-of-colombia/national-university-of-colombia-community/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [National University Of Colombia Collection Structure](https://apis.io/json-structure/national-university-of-colombia/national-university-of-colombia-collection-structure/)
- [National University Of Colombia Community Structure](https://apis.io/json-structure/national-university-of-colombia/national-university-of-colombia-community-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [National University Of Colombia Context](https://apis.io/jsonld/national-university-of-colombia/national-university-of-colombia-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [National University of Colombia Institutional Repository Vocabulary](https://apis.io/vocabularies/national-university-of-colombia/national-university-of-colombia-vocabulary/)

#### Examples (3)

Example requests and responses.

- [National University Of Colombia Listcollections Example](https://apis.io/examples/national-university-of-colombia/national-university-of-colombia-listCollections-example/)
- [National University Of Colombia Listcommunities Example](https://apis.io/examples/national-university-of-colombia/national-university-of-colombia-listCommunities-example/)
- [National University Of Colombia Oairecord Example](https://apis.io/examples/national-university-of-colombia/national-university-of-colombia-oaiRecord-example/)

#### Collections (3)

Postman and Open Collection request collections.

- [National University of Colombia - Institutional Repository OAI-PMH API](https://apis.io/collections/national-university-of-colombia/open-national-university-of-colombia-oai-pmh-api/)
- [National University of Colombia - Institutional Repository OAI-PMH REST - Core API](https://apis.io/collections/national-university-of-colombia/open-national-university-of-colombia-rest-core-api/)
- [National University of Colombia - Institutional Repository OAI-PMH REST - Discover API](https://apis.io/collections/national-university-of-colombia/open-national-university-of-colombia-rest-discover-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [National University of Colombia — jsonschema rules](https://apis.io/rules/national-university-of-colombia/national-university-of-colombia-jsonschema-spectral-rules/)
- [National University of Colombia API Rules](https://apis.io/rules/national-university-of-colombia/national-university-of-colombia-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [National University Of Colombia Domain Security](https://apis.io/security/national-university-of-colombia/national-university-of-colombia-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [National University Of Colombia Plans Pricing](https://apis.io/plans/national-university-of-colombia/national-university-of-colombia-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [National University Of Colombia Rate Limits](https://apis.io/rate-limits/national-university-of-colombia/national-university-of-colombia-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [National University Of Colombia Finops](https://apis.io/finops/national-university-of-colombia/national-university-of-colombia-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://unal.edu.co/)
- [Documentation](https://www.re3data.org/repository/r3d100013982)
- [GitHub](https://github.com/unal)

## API Evangelist rating

**Kin Score 24.1** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 53.9 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 9.5 |
| Access clarity | 5.3 |

**Agent readiness 17.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 10.8** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/national-university-of-colombia/](https://apis.io/providers/national-university-of-colombia/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for National University of Colombia: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/national-university-of-colombia/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
