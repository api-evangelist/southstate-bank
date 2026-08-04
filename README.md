# SouthState Bank (southstate-bank)

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

SouthState Bank, National Association is an OCC-chartered national commercial bank headquartered in Winter Haven, Florida, and the principal subsidiary of SouthState Bank Corporation (NASDAQ: SSB). Formed through the 2020 merger of South State Corporation and CenterState Bank and redomiciled to Florida in 2025, it holds roughly $67 billion in assets and serves customers across the Southeast, Texas, Colorado, and Virginia.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/southstate-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/southstate-bank/refs/heads/main/apis.yml)

## Open Finance & API Posture

SouthState Bank runs **no public first-party developer portal** and publishes **no downloadable OpenAPI/Swagger definitions**. The usual developer subdomains do not exist — `developer.southstatebank.com` and `api.southstatebank.com` fail DNS resolution, and no `/developers` or `/api` path is served.

Consumer-permissioned account data is available only through a **third-party aggregator**. The Open Banking Tracker records SouthState reachable via **Plaid** (no MX, Finicity, or Akoya route listed and no API products listed). There is **no documented Financial Data Exchange (FDX)** endpoint and **no published CFPB Section 1033** data-access posture for the institution. Open-finance connectivity is aggregator-mediated, not a self-serve bank-operated API.

This is an identity-only (stub) profile: an honest record that SouthState exposes no public API surface.

## Tags

- Financial Services
- Banking
- United States
- Regional Bank
- National Bank
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. SouthState Bank does not document a public first-party API. Consumer data access is available only through the Plaid aggregator.

## Common Properties

- [Website](https://www.southstatebank.com/)
- [GitHub Organization](https://github.com/southstatebank) (real, zero public repositories)
- [LinkedIn](https://www.linkedin.com/company/south-state-bank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
