# Candid (candid)

Candid (formed from the 2019 merger of Foundation Center and GuideStar) helps social sector organizations advance their missions by sharing information, breaking down barriers, and improving giving. Candid maintains the most comprehensive set of data on U.S. nonprofits, foundations, grants, and philanthropy, and exposes that data through a family of developer APIs — Essentials, Premier, Charity Check, Demographics, Grants, News, Taxonomy, Eligibility, and PDF/Bulk variants — available through the Candid Developer Portal.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/candid/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

 - Charities, Donations, Non-Profits, Philanthropy, Foundations, Grants, 990s, Demographics

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-04-23

## APIs

### Candid Essentials API

Core nonprofit search and lookup. Provides fast search over Candid's database of U.S. nonprofits by name, EIN, location, NTEE code, size, and more. Returns summary records suitable for autocompletes, lookups, and basic-verification flows. Available in versions v1–v4 with POST and GET variants.

**Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)

#### Tags

 - Nonprofits, Search, Lookup

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)

### Candid Premier API

Deep nonprofit profile data. Returns comprehensive records for a given organization including financials, programs, leadership, board, grants received and awarded, operating details, affiliations, and FTA (Financial Trend Analysis). Supports a Profile PDF generation endpoint for building ready-to-share nonprofit briefs.

**Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)

#### Tags

 - Nonprofits, Financials, Profiles, PDF

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)

### Candid Charity Check API

Real-time nonprofit verification and compliance screening used for due diligence, donation compliance, and tax-deductibility checks. Returns IRS 501(c)(3) status, revocation history, public-charity / private-foundation classification, OFAC watchlist screening, and more. Offers national and state-level endpoints.

**Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)

#### Tags

 - Compliance, Verification, IRS, Due Diligence

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)

### Candid Demographics API

Structured demographic data voluntarily provided by nonprofits about their staff, board, and populations served. Enables funders and platforms to analyze equity, diversity, and inclusion across the social sector.

**Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)

#### Tags

 - Demographics, DEI, Nonprofits

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)

### Candid Grants API

Access to Candid's global grants dataset — summary statistics, funders, recipients, and individual transaction records. Useful for philanthropic benchmarking, funder research, and grant-market intelligence.

**Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)

#### Tags

 - Grants, Funders, Recipients, Transactions

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)

### Candid News API

Search and retrieve philanthropic news content from Candid's curated news database covering funders, grantees, sector trends, and policy. Supports customizable parameters for date range, topic, geography, and organization.

**Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)

#### Tags

 - News, Philanthropy, Content

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)

### Candid Taxonomy API

Returns Candid's philanthropic classification system (subject, population, support-strategy, and geographic area taxonomies) so integrators can consistently tag and query nonprofit, grant, and funder records.

**Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)

#### Tags

 - Taxonomy, Classification, Metadata

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)

### Candid Nonprofit Eligibility API

Evaluates whether a given nonprofit is eligible to receive a grant or donation based on configurable rules — IRS status, country, OFAC, custom program criteria — to automate grantmaking and giving workflows.

**Human URL:** [https://developer.candid.org/reference/welcome](https://developer.candid.org/reference/welcome)

#### Tags

 - Eligibility, Grantmaking, Compliance

#### Properties

- [Documentation](https://developer.candid.org/reference/welcome)
- [Portal](https://developer.candid.org/)

## Use Cases

- Donation platforms that verify nonprofits (Charity Check) and enable tax-deductible giving with IRS-compliant records.
- Corporate giving and employee matching programs automating eligibility, screening, and compliance through the Eligibility API.
- Grantmaking foundations searching and profiling potential grantees via Essentials and Premier, then benchmarking against the Grants API.
- Nonprofit-facing research tools using Premier for 990-derived financials, programs, and trend analysis.
- Equity and DEI dashboards aggregating Demographics API data across funder portfolios.
- Sector news products embedding Candid News API feeds filtered by topic, funder, or region.

## Common Properties

- [Website](https://candid.org)
- [Developer Portal](https://developer.candid.org/)
- [Data Portal](https://data.candid.org/reference/welcome-to-candids-data-portal)
- [APIs Overview](https://candid.org/use-our-data)
- [Pricing and Access](https://candid.org/use-our-data)
- [Privacy Policy](https://candid.org/privacy-policy)
- [Terms of Service](https://candid.org/terms-of-use)
- [Support](https://help.candid.org/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
