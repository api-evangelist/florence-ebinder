# Florence Healthcare (florence-ebinder)

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
