# SouthState Bank (southstate-bank)

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
