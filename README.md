# Candid (candid)

Candid (formed from the 2019 merger of Foundation Center and GuideStar) helps social sector organizations advance their missions by sharing information, breaking down barriers, and improving giving. Candid maintains the most comprehensive set of data on U.S. nonprofits, foundations, grants, and philanthropy, and exposes that data through a family of developer APIs — Essentials, Premier, Charity Check, Demographics, Grants, News, Taxonomy, Eligibility, and PDF/Bulk variants — available through the Candid Developer Portal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/candid/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/candid/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Charities
- Donations
- Non-Profits
- Philanthropy
- Foundations
- Grants
- 990s
- Demographics

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### Candid Essentials API

Core nonprofit search and lookup. Provides fast search over Candid's database of U.S. nonprofits by name, EIN, location, NTEE code, size, and more. Returns summary records suitable for autocompletes, lookups, and basic-verification flows. Available in versions v1–v4 with POST and GET variants.

- **Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)
- **Base URL:** `https://api.candid.org/essentials`

#### Tags

- Nonprofits
- Search
- Lookup

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)
- [OpenAPI](openapi/candid-essentials-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/candid-essentials-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candid-essentials-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid Premier API

Deep nonprofit profile data. Returns comprehensive records for a given organization including financials, programs, leadership, board, grants received and awarded, operating details, affiliations, and FTA (Financial Trend Analysis). Supports a Profile PDF generation endpoint for building ready-to-share nonprofit briefs.

- **Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)
- **Base URL:** `https://api.candid.org/premier`

#### Tags

- Nonprofits
- Financials
- Profiles
- PDF

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)
- [Postman Collection](collections/candid-essentials-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candid-essentials-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid Charity Check API

Real-time nonprofit verification and compliance screening used for due diligence, donation compliance, and tax-deductibility checks. Returns IRS 501(c)(3) status, revocation history, public-charity / private- foundation classification, OFAC watchlist screening, and more. Offers national and state-level endpoints.

- **Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)
- **Base URL:** `https://api.candid.org/charitycheck`

#### Tags

- Compliance
- Verification
- IRS
- Due Diligence

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)
- [Postman Collection](collections/candid-essentials-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candid-essentials-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid Demographics API

Structured demographic data voluntarily provided by nonprofits about their staff, board, and populations served. Enables funders and platforms to analyze equity, diversity, and inclusion across the social sector.

- **Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)
- **Base URL:** `https://api.candid.org/demographics`

#### Tags

- Demographics
- DEI
- Nonprofits

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)
- [Postman Collection](collections/candid-essentials-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candid-essentials-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid Grants API

Access to Candid's global grants dataset — summary statistics, funders, recipients, and individual transaction records. Useful for philanthropic benchmarking, funder research, and grant-market intelligence.

- **Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)
- **Base URL:** `https://api.candid.org/grants`

#### Tags

- Grants
- Funders
- Recipients
- Transactions

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)
- [Postman Collection](collections/candid-essentials-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candid-essentials-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid News API

Search and retrieve philanthropic news content from Candid's curated news database covering funders, grantees, sector trends, and policy. Supports customizable parameters for date range, topic, geography, and organization.

- **Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)
- **Base URL:** `https://api.candid.org/news`

#### Tags

- News
- Philanthropy
- Content

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)
- [Postman Collection](collections/candid-essentials-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candid-essentials-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid Taxonomy API

Returns Candid's philanthropic classification system (subject, population, support-strategy, and geographic area taxonomies) so integrators can consistently tag and query nonprofit, grant, and funder records.

- **Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)
- **Base URL:** `https://api.candid.org/taxonomy`

#### Tags

- Taxonomy
- Classification
- Metadata

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)
- [Postman Collection](collections/candid-essentials-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candid-essentials-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid Nonprofit Eligibility API

Evaluates whether a given nonprofit is eligible to receive a grant or donation based on configurable rules — IRS status, country, OFAC, custom program criteria — to automate grantmaking and giving workflows.

- **Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)
- **Base URL:** `https://api.candid.org/eligibility`

#### Tags

- Eligibility
- Grantmaking
- Compliance

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)
- [Postman Collection](collections/candid-essentials-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candid-essentials-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/CandidOrg)
- [LinkedIn](https://www.linkedin.com/company/candiddotorg)
- [Website](https://candid.org)
- [Developer Portal](https://developer.candid.org/)
- [Data Portal](https://data.candid.org/reference/welcome-to-candids-data-portal)
- [A P Is Overview](https://candid.org/use-our-data)
- [Pricing And Access](https://candid.org/use-our-data)
- [Privacy Policy](https://candid.org/privacy-policy)
- [Terms of Service](https://candid.org/terms-of-use)
- [Support](https://help.candid.org/)
- [Integrations](https://candid.org/partners/)
- [L L Ms Txt](https://developer.candid.org/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
