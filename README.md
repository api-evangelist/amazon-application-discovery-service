# Amazon Application Discovery Service

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
