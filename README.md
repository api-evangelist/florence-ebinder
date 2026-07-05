# Florence Healthcare (florence-ebinder)

Florence Healthcare provides eRegulatory and clinical-trial site enablement software for research sites, sponsors, and CROs. **eBinders** is an electronic investigator site file (eISF) and participant binder platform that replaces paper regulatory binders with structured, compliant, 21 CFR Part 11 workflows; **eTMF** manages the sponsor-side trial master file; and **SiteLink** connects a network of 10,000+ investigator sites across 44+ countries to sponsors and CROs for remote site access, monitoring, document exchange, and source data verification.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/florence-ebinder/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/florence-ebinder/refs/heads/main/apis.yml)

## Access Model — Important

This is an **honest gated stub**. Florence repeatedly describes an **"open API"** for eBinders, eTMF, and SiteLink — supporting connected management of roles and permissions, inbound and outbound document exchange, and document status reporting across regulatory and source documents. **However, that API is partner- and customer-gated.** As of this writing there is:

- **No public developer portal**
- **No public API reference**
- **No published OpenAPI description**
- **No published base URL, authentication, sandbox, or rate-limit documentation**

Access is provisioned through Florence's integration and partnership programs, not self-service signup. A third-party tracker ([apitracker.io](https://apitracker.io/a/florencehc)) lists a "Native REST API," but its developer-portal and API-reference links resolve to placeholder pages — confirming there is no open public documentation. The [FlorenceHC GitHub org](https://github.com/FlorenceHC) holds only general-purpose and archived forked repos, not a product SDK or API spec.

The APIs listed below are **logical APIs modeled** from Florence's public statements about its open API and SiteLink capabilities. Endpoint paths, base URLs, and an OpenAPI surface were **not fabricated** — each modeled API is flagged `endpointsModeled: true` in `apis.yml`. No `openapi/`, `plans/`, `rate-limits/`, `finops/`, or `collections/` artifacts were created because no sourced technical detail exists.

## Tags

- Clinical Trials
- eRegulatory
- eISF
- eBinders
- eTMF
- Clinical Research
- Healthcare
- Life Sciences
- Document Management
- Partner API

## Timestamps

- **Created:** 2026-07-05
- **Modified:** 2026-07-05

## APIs (Modeled)

### Florence Documents and Binders API
Modeled logical API for the eBinders eISF and participant binder structure — creating and organizing binders, folders, and placeholders, and inbound/outbound exchange of regulatory and source documents between sites, sponsors, and CROs.

### Florence Signatures and Compliance API
Modeled logical API for compliant electronic signature and audit-trail workflows on regulatory documents (21 CFR Part 11 / GxP), including signature requests, signing, and document status/compliance reporting.

### Florence Studies and Sites API
Modeled logical API over the SiteLink network for managing studies, investigator sites, and cross-site document status reporting.

### Florence Users and Permissions API
Modeled logical API for connected management of users, roles, and permissions across the eBinders/SiteLink platform.

### Florence Tasks and Workflows API
Modeled logical API for operational tasks and workflow automation (site startup, monitoring, source data verification) orchestrated by SiteLink.

## Pricing

Not published. Florence prices eBinders/SiteLink by quote based on study profile and organizational dynamics; sponsors typically reimburse sites for eBinders on a per-trial basis. Contact Florence sales for a quote.

## Common Properties

- [Website](https://www.florencehc.com/)
- [LinkedIn](https://www.linkedin.com/company/florence-healthcare)
- [GitHub Organization](https://github.com/FlorenceHC)
- [Documentation](https://www.florencehc.com/products/sitelink/)
- [Sign In](https://www.florencehc.com/sign-in-4/)
- [Contact](https://www.florencehc.com/contact/)

## WebSocket Review

Does Florence Healthcare expose a documented public WebSocket API? **No.** Florence publishes no public WebSocket surface — and no public REST API description of any kind. See `review.yml` for the full assessment.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
