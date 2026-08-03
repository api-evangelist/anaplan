# Anaplan (anaplan)

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

Anaplan is a cloud-native connected planning platform used by enterprises for financial planning and analysis (FP&A), supply chain planning, and sales performance management. Its REST API allows integrators to import and export data, trigger model processes, and manage Anaplan workspaces programmatically. Beyond bulk data operations, Anaplan exposes dedicated APIs for financial consolidation, identity management via SCIM, audit event streaming, application lifecycle management, and CloudWorks custom integrations.

APIs.json: https://raw.githubusercontent.com/api-evangelist/anaplan/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=anaplan-api-evangelist&utm_content=repo

## Tags

- Connected Planning
- Enterprise Planning
- FP&A
- Supply Chain
- Sales Planning
- Financial Consolidation
- SCIM
- REST

## APIs

| API | Description | Documentation |
|-----|-------------|---------------|
| Integration API v2.0 | RESTful bulk and transactional API for importing data, exporting results, running processes, and managing models | [Docs](https://help.anaplan.com/integration-api-v20-399496b0-d66e-4a84-895a-8d1ffdee2e6b) |
| Authentication Service API | Manages authentication token creation and refresh for all Anaplan APIs | [Docs](https://help.anaplan.com/anaplan-api-844c6d40-a21c-423d-8435-ebaaa0372b76) |
| Financial Consolidation API | Controls workflows and manages financial data and metadata for consolidation | [Docs](https://help.anaplan.com/anaplan-financial-consolidation-api-e83345d8-0509-4228-b532-679ee398a9d5) |
| SCIM API | User identity provisioning and management across multiple domains | [Docs](https://help.anaplan.com/anaplan-api-844c6d40-a21c-423d-8435-ebaaa0372b76) |
| CloudWorks API | Custom connections and integrations with external data sources | [Docs](https://help.anaplan.com/anaplan-api-844c6d40-a21c-423d-8435-ebaaa0372b76) |
| Audit API | Audit event streaming for SIEM integration | [Docs](https://help.anaplan.com/anaplan-api-844c6d40-a21c-423d-8435-ebaaa0372b76) |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/anaplan-plans-pricing.yml](plans/anaplan-plans-pricing.yml) |
| Rate Limits | [rate-limits/anaplan-rate-limits.yml](rate-limits/anaplan-rate-limits.yml) |
| FinOps | [finops/anaplan-finops.yml](finops/anaplan-finops.yml) |

**Rate Limits:** 600 requests per minute at the tenant level (token bucket algorithm). HTTP 429 returned when exceeded. Retry-After header provided on throttled responses.

**Pricing:** Enterprise SaaS subscription, contact sales required. Entry-level from ~$30K/year; large enterprise deployments reach $1M+/year.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.anaplan.com |
| Documentation | https://help.anaplan.com |
| GitHub Organization | https://github.com/anaplaninc |
| LinkedIn | https://www.linkedin.com/company/anaplan |
| Blog | https://www.anaplan.com/blog/ |
| Pricing | https://www.anaplan.com/platform/ |
| Status Page | https://status.anaplan.com/ |
| X (Twitter) | https://x.com/anaplan |

## Maintainers

- Kin Lane / kin@apievangelist.com
