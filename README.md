# Anaplan (anaplan)

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
