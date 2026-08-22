# Amazon Application Discovery Service

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

Amazon Application Discovery Service helps enterprise customers plan application migration projects by automatically identifying servers, virtual machines, software, and software dependencies running in their on-premises data centers.

## Overview

The Amazon Application Discovery Service API provides programmatic access to discovery agents, application groupings, configuration items, export tasks, and import capabilities. It enables automated infrastructure discovery and dependency mapping to accelerate cloud migration planning.

## API Documentation

- **Human URL:** https://docs.aws.amazon.com/application-discovery/latest/APIReference/Welcome.html
- **Base URL:** https://discovery.us-east-1.amazonaws.com

## Features

- Agentless Discovery via VMware vCenter integration
- Agent-based discovery for physical and virtual servers
- Automatic server dependency mapping via network traffic analysis
- Application grouping and tagging for migration planning
- Data export to Amazon S3 in CSV and GraphML formats
- Bulk import of server inventory via CSV files
- Integration with AWS Migration Hub for centralized tracking
- Continuous data collection with configurable intervals
- Server neighbor discovery for dependency visualization
- Tag-based filtering and organization of discovered assets

## Use Cases

- Discover all servers and processes in on-premises data centers before migration
- Map application dependencies to create migration groups and waves
- Export inventory data for detailed analysis and migration planning in third-party tools
- Import existing server inventory from CMDBs or spreadsheets without installing agents
- Track migration readiness across thousands of servers in a single dashboard
- Identify unknown servers and shadow IT in large enterprise environments

## Artifacts

### OpenAPI Specification
`openapi/amazon-application-discovery-service-openapi.yml`

Complete OpenAPI 3.1.0 specification covering all 26 API paths including agents, configurations, applications, exports, imports, and tags.

### Spectral Rules
`rules/amazon-application-discovery-service-spectral-rules.yml`

Linting rules for validating OpenAPI specifications for this service.

### Naftiko Capabilities
- `capabilities/shared/application-discovery-service-api.yaml` — Shared per-API capability definition
- `capabilities/migration-discovery.yaml` — Workflow capability for migration discovery use cases

### Vocabulary
`vocabulary/amazon-application-discovery-service-vocabulary.yaml`

Structured vocabulary of resources, actions, workflows, and personas for the Application Discovery Service.

### JSON Schemas
`json-schema/` — 66 JSON Schema draft/2020-12 files for all request and response objects.

### JSON Structures
`json-structure/` — 66 JSON Structure files for all objects.

### JSON-LD Context
`json-ld/amazon-application-discovery-service-context.jsonld`

### Examples
`examples/` — 66 example JSON files for all objects.

## Integrations

- AWS Migration Hub
- AWS Server Migration Service
- AWS Application Migration Service
- Amazon EC2
- Amazon S3
- VMware vCenter
- AWS Database Migration Service
- AWS CloudFormation
- AWS Systems Manager
- AWS Cost Explorer

## Tags

Amazon Application Discovery Service, Migration, Discovery, Infrastructure, AWS

## Maintainers

- Kin Lane (kin@apievangelist.com)
