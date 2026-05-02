# RelativityOne

RelativityOne is a cloud-based eDiscovery and legal technology platform that provides comprehensive REST APIs for legal hold management, document processing, search and analytics, workspace management, identity and access control, and billing insights. The platform integrates with Microsoft 365 and Google Workspace for data preservation and legal hold workflows.

**URL:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/apis.yml)

## APIs

| Name | Description |
|---|---|
| [Legal Hold API](https://platform.relativity.com/RelativityOne/Content/Legal_Hold_API/Legal_Hold_API.htm) | Endpoints for custodian management, preservation workflows, task tracking, entity management, and communication configuration. |
| [Object Manager API](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm) | CRUD operations for documents and Relativity Dynamic Objects (RDOs). |
| [Workspace Manager API](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm) | Workspace creation, configuration, and application installation operations. |
| [Search and Analytics API](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm) | dtSearch, keyword search, Analytics Conceptual Index, and Pivot query operations. |
| [User and Permission Manager API](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm) | Identity and access management including user, group, and permission operations. |
| [Import and Export API](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm) | Document and RDO transfer and bulk import operations. |

## Tags

- eDiscovery
- Legal
- Legal Hold
- Document Management
- Compliance
- Litigation

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-02

## Common Properties

| Type | URL |
|---|---|
| Website | [https://www.relativity.com](https://www.relativity.com) |
| Documentation | [https://platform.relativity.com/](https://platform.relativity.com/) |
| Developer Documentation | [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm) |
| API Reference | [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Relativity_API_reference.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Relativity_API_reference.htm) |
| Changelog | [https://platform.relativity.com/RelativityOne/Content/What_s_new/What_s_new.htm](https://platform.relativity.com/RelativityOne/Content/What_s_new/What_s_new.htm) |
| GitHub Organization | [https://github.com/relativitydev](https://github.com/relativitydev) |

## Artifacts

| Type | Path |
|---|---|
| APIs Index | [apis.yml](apis.yml) |
| OpenAPI (Legal Hold) | [openapi/relativityone-legal-hold-openapi.yml](openapi/relativityone-legal-hold-openapi.yml) |
| Spectral Rules | [rules/relativityone-rules.yml](rules/relativityone-rules.yml) |
| Capabilities | [capabilities/legal-hold-management.yaml](capabilities/legal-hold-management.yaml) |
| Capabilities (Shared - Legal Hold) | [capabilities/shared/legal-hold.yaml](capabilities/shared/legal-hold.yaml) |
| JSON Schema (Legal Hold Project) | [json-schema/relativityone-legal-hold-project-schema.json](json-schema/relativityone-legal-hold-project-schema.json) |
| JSON Schema (Custodian) | [json-schema/relativityone-custodian-schema.json](json-schema/relativityone-custodian-schema.json) |
| JSON Structure | [json-structure/relativityone-legal-hold-structure.json](json-structure/relativityone-legal-hold-structure.json) |
| JSON-LD Context | [json-ld/relativityone-context.jsonld](json-ld/relativityone-context.jsonld) |
| Examples | [examples/relativityone-create-legal-hold-project-example.json](examples/relativityone-create-legal-hold-project-example.json) |
| Examples | [examples/relativityone-add-custodian-example.json](examples/relativityone-add-custodian-example.json) |
| Vocabulary | [vocabulary/relativityone-vocabulary.yml](vocabulary/relativityone-vocabulary.yml) |

## Capabilities

### Workflow Capabilities

| Capability | Description |
|---|---|
| [Legal Hold Management](capabilities/legal-hold-management.yaml) | Unified REST and MCP API for managing legal hold projects, custodians, preservation, communications, and tasks (12 tools). |

### Shared Definitions

| Shared File | Description |
|---|---|
| [legal-hold](capabilities/shared/legal-hold.yaml) | Per-API consumed definition for the RelativityOne Legal Hold REST API. |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
