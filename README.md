# Candid (candid)

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
