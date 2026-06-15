# RelativityOne (relativityone)

RelativityOne is a cloud-based eDiscovery and legal technology platform that provides comprehensive REST APIs for legal hold management, document processing, search and analytics, workspace management, identity and access control, and billing insights. The platform integrates with Microsoft 365 and Google Workspace for data preservation and legal hold workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- eDiscovery
- Legal
- Legal Hold
- Document Management
- Compliance
- Litigation

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### Legal Hold API

The Legal Hold API enables matter and project management integration with external systems like matter management platforms and HR systems. It provides endpoints for custodian management, preservation workflows, task tracking, entity management, and communication configuration. Authentication is handled via Microsoft Graph API.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Legal_Hold_API/Legal_Hold_API.htm](https://platform.relativity.com/RelativityOne/Content/Legal_Hold_API/Legal_Hold_API.htm)
- **Base URL:** `https://relativity.rest/api`

#### Tags

- Legal Hold
- Custodian Management
- Preservation
- eDiscovery
- Compliance

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Legal_Hold_API/Legal_Hold_API.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/openapi/relativityone-legal-hold-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/json-schema/relativityone-legal-hold-project-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/json-schema/relativityone-custodian-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/json-structure/relativityone-legal-hold-structure.json)
- [Postman Collection](collections/relativityone-legal-hold.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/relativityone-legal-hold.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Object Manager API

The Object Manager API provides CRUD operations for documents and Relativity Dynamic Objects (RDOs). It supports bulk read, create, update, and delete operations with filtering and search capabilities across workspace objects.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm)
- **Base URL:** `https://relativity.rest/api`

#### Tags

- Document Management
- Object Management
- CRUD Operations
- Workspace

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm)
- [Postman Collection](collections/relativityone-legal-hold.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/relativityone-legal-hold.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workspace Manager API

The Workspace Manager API provides CRUD operations for Relativity workspaces, including workspace creation, configuration, application installation, and environment management.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm)
- **Base URL:** `https://relativity.rest/api`

#### Tags

- Workspace Management
- Administration
- Configuration

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm)
- [Postman Collection](collections/relativityone-legal-hold.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/relativityone-legal-hold.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Search and Analytics API

APIs for search and analytics operations in RelativityOne including dtSearch index management, keyword search, Analytics Conceptual Index for LSI and concept discovery, and Pivot queries for data analysis.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm)
- **Base URL:** `https://relativity.rest/api`

#### Tags

- Search
- Analytics
- Full Text Search
- Concept Search
- Data Analysis

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm)
- [Postman Collection](collections/relativityone-legal-hold.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/relativityone-legal-hold.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### User and Permission Manager API

APIs for identity and access management in RelativityOne. Includes user CRUD operations, permission assignment and management, group administration, and client management.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm)
- **Base URL:** `https://relativity.rest/api`

#### Tags

- Identity
- Access Management
- Permissions
- User Management

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm)
- [Postman Collection](collections/relativityone-legal-hold.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/relativityone-legal-hold.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Import and Export API

Import and Export Services API for handling document and Relativity Dynamic Object (RDO) transfers, including bulk import operations for large data sets.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm)
- **Base URL:** `https://relativity.rest/api`

#### Tags

- Import
- Export
- Data Transfer
- Bulk Operations

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm)
- [Postman Collection](collections/relativityone-legal-hold.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/relativityone-legal-hold.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/relativityhq)
- [Website](https://www.relativity.com)
- [Documentation](https://platform.relativity.com/)
- [Developer  Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/index.htm)
- [API Reference](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Relativity_API_reference.htm)
- [Changelog](https://platform.relativity.com/RelativityOne/Content/What_s_new/What_s_new.htm)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/json-ld/relativityone-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/vocabulary/relativityone-vocabulary.yml)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/relativityone/refs/heads/main/rules/relativityone-rules.yml)
- [GitHub Organization](https://github.com/relativitydev)
- [Integrations](https://www.relativity.com/partners/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
