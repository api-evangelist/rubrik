# Rubrik (rubrik)

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

Rubrik is a Zero Trust data security company that protects enterprise, cloud, and SaaS data with backup, recovery, threat analytics, data security posture management, and cyber recovery workflows through Rubrik Security Cloud (RSC) and on-premises Rubrik clusters. Rubrik publishes a comprehensive developer program including the Rubrik Security Cloud GraphQL API at /api/graphql, the legacy Rubrik Cluster REST API (v1, v2, and internal endpoints), an interactive API Playground, a PowerShell module, a Terraform provider, and Postman collections through the Rubrik Developer Center at developer.rubrik.com.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rubrik/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rubrik/refs/heads/main/apis.yml)

## Tags

- Backup
- Cyber Recovery
- Data Security
- Data Security Posture Management
- GraphQL
- Ransomware Recovery
- REST API
- SaaS Protection
- Threat Analytics
- Zero Trust

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Rubrik Security Cloud API

The Rubrik Security Cloud (RSC) API is a single-endpoint GraphQL API at /api/graphql that exposes the full RSC platform, including SLA domain management and assignment, on-demand backups, recovery operations, data security posture, data threat analytics, observability, SaaS app protection, and reporting. The API is introspectable and is supported by an in-product API Playground IDE.

- **Human URL:** [https://developer.rubrik.com/Rubrik-Security-Cloud-API/](https://developer.rubrik.com/Rubrik-Security-Cloud-API/)

#### Tags

- Backup
- Cyber Recovery
- Data Security Posture
- GraphQL
- Threat Analytics

#### Properties

- [Documentation](https://developer.rubrik.com/Rubrik-Security-Cloud-API/)
- [A P I Playground](https://developer.rubrik.com/Rubrik-Security-Cloud-API/API-playground/)
- [Authentication](https://developer.rubrik.com/Rubrik-Security-Cloud-API/Authentication/)
- [A P I Playground Docs](https://docs.rubrik.com/en-us/saas/gql/api_playground.html)
- [Postman Collection](collections/rubrik.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubrik.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rubrik Cluster API

REST API exposed by on-premises Rubrik clusters (CDM) with v1, v2, and internal endpoints for managing protected objects, SLA domains, backup jobs, recovery, cluster configuration, events, and reports. Provides the foundation for the rubrik-sdk-for-python and rubrik-sdk-for-powershell tooling.

- **Human URL:** [https://developer.rubrik.com/Rubrik-Cluster-API/](https://developer.rubrik.com/Rubrik-Cluster-API/)

#### Tags

- Backup
- CDM
- On-Premises
- REST API

#### Properties

- [Documentation](https://developer.rubrik.com/Rubrik-Cluster-API/)
- [API Reference](https://rubrikinc.github.io/rubrik-api-documentation/)
- [Postman Collection](collections/rubrik.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubrik.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rubrik PowerShell Module

Fully-supported PowerShell module for automating Rubrik Security Cloud using cmdlets that wrap the underlying GraphQL API.

- **Human URL:** [https://github.com/rubrikinc/rubrik-powershell-sdk](https://github.com/rubrikinc/rubrik-powershell-sdk)

#### Tags

- PowerShell
- SDK
- Automation

#### Properties

- [Source Code](https://github.com/rubrikinc/rubrik-powershell-sdk)
- [Power Shell Gallery](https://www.powershellgallery.com/packages/rubriksecuritycloud)
- [Postman Collection](collections/rubrik.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubrik.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rubrik Polaris Terraform Provider

Terraform provider for managing Rubrik Security Cloud (Polaris) resources as infrastructure-as-code.

- **Human URL:** [https://registry.terraform.io/providers/rubrikinc/polaris/](https://registry.terraform.io/providers/rubrikinc/polaris/)

#### Tags

- Infrastructure as Code
- Polaris
- Terraform

#### Properties

- [Registry](https://registry.terraform.io/providers/rubrikinc/polaris/)
- [Source Code](https://github.com/rubrikinc/terraform-provider-polaris)
- [Postman Collection](collections/rubrik.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubrik.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.rubrik.com/)
- [Developer Portal](https://developer.rubrik.com/)
- [Documentation](https://docs.rubrik.com/)
- [GitHub Organization](https://github.com/rubrikinc)
- [A P I Playground](https://developer.rubrik.com/Rubrik-Security-Cloud-API/API-playground/)
- [S D Ks](https://developer.rubrik.com/SDKs-and-Tools/)
- [Integrations](https://developer.rubrik.com/Integrations/)
- [Support](https://support.rubrik.com/)
- [Blog](https://www.rubrik.com/blog)
- [Customers](https://www.rubrik.com/customers)
- [Partners](https://www.rubrik.com/partners)
- [About Us](https://www.rubrik.com/company)
- [Investor Relations](https://ir.rubrik.com/)
- [Careers](https://www.rubrik.com/company/careers)
- [Trust Center](https://www.rubrik.com/company/trust)
- [LinkedIn](https://www.linkedin.com/company/rubrik-inc/)
- [L L Ms Txt](https://developer.rubrik.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
