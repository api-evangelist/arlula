# Arlula (arlula)
Arlula is a satellite imagery marketplace and API platform providing programmatic access to archive and tasking satellite imagery from multiple providers. The Arlula API enables developers to search the global satellite archive, discover tasking opportunities, place imagery orders, and download delivered datasets including GeoTIFF imagery, preview images, and metadata files.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/arlula/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Earth Observation, Geospatial, Imagery, Remote Sensing, Satellites

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-04-19

## APIs

### Arlula API
The Arlula API provides programmatic access to satellite imagery search, ordering, and delivery. It covers archive search for historical imagery, tasking for future satellite captures, and order management including campaign, dataset, and resource download operations. Authentication uses HTTP Basic with API Key and API Secret obtained from the Arlula dashboard.

**Human URL:** [https://arlula.com/documentation/](https://arlula.com/documentation/)

#### Tags:

 - Archive, Earth Observation, Imagery, Satellites, Tasking

#### Properties

- [Documentation](https://arlula.com/documentation/)
- [OpenAPI](openapi/arlula-openapi.yaml)
- [JSONSchema](json-schema/arlula-archive-scene-schema.json)
- [JSONSchema](json-schema/arlula-archive-search-request-schema.json)
- [JSONSchema](json-schema/arlula-tasking-opportunity-schema.json)
- [JSONSchema](json-schema/arlula-order-schema.json)
- [JSONStructure](json-structure/arlula-archive-scene-structure.json)
- [JSONStructure](json-structure/arlula-tasking-opportunity-structure.json)
- [JSONStructure](json-structure/arlula-order-structure.json)
- [JSON-LD](json-ld/arlula-api-context.jsonld)

## Common Properties

- [Website](https://arlula.com/)
- [Documentation](https://arlula.com/documentation/)
- [GettingStarted](https://arlula.com/documentation/)
- [Portal](https://dashboard.arlula.com)
- [GitHubOrganization](https://github.com/Arlula)

## Features

| Name | Description |
|------|-------------|
| Archive Search | Search a global satellite image archive from multiple providers using area-of-interest (polygon/bounding box) and temporal filters to find available historical scenes. |
| Satellite Tasking | Commission future satellite captures by searching tasking opportunities and placing orders for specific areas of interest and time windows. |
| Multi-Provider Access | Access imagery from multiple satellite providers through a single unified API, enabling price and resolution comparisons across providers. |
| Bundle Selection | Choose from available product bundles (e.g., analytic, visual) when ordering scenes to match data requirements and budget. |
| Dataset Download | Download delivered imagery resources including GeoTIFF files, preview images, and metadata through the Orders API after capture and processing. |
| Batch Ordering | Place multiple archive or tasking orders in a single batch API request to efficiently process large-scale imagery acquisitions. |

## Use Cases

| Name | Description |
|------|-------------|
| Agricultural Monitoring | Search and order archive or tasking imagery to monitor crop health, irrigation patterns, and field conditions over growing seasons. |
| Environmental Change Detection | Acquire multi-temporal satellite imagery to detect deforestation, coastal erosion, urban expansion, or disaster impact areas. |
| Infrastructure Inspection | Order high-resolution imagery for remote inspection of pipelines, power lines, roads, and construction site progress monitoring. |
| Disaster Response | Rapidly search and order post-event imagery to assess damage extent and support emergency response and recovery planning. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Arlula API](openapi/arlula-openapi.yaml)

### JSON Schema

- [arlula-test-response-schema](json-schema/arlula-test-response-schema.json)
- [arlula-archive-search-request-schema](json-schema/arlula-archive-search-request-schema.json)
- [arlula-archive-scene-schema](json-schema/arlula-archive-scene-schema.json)
- [arlula-bundle-schema](json-schema/arlula-bundle-schema.json)
- [arlula-archive-order-request-schema](json-schema/arlula-archive-order-request-schema.json)
- [arlula-batch-archive-order-request-schema](json-schema/arlula-batch-archive-order-request-schema.json)
- [arlula-tasking-search-request-schema](json-schema/arlula-tasking-search-request-schema.json)
- [arlula-tasking-opportunity-schema](json-schema/arlula-tasking-opportunity-schema.json)
- [arlula-tasking-order-request-schema](json-schema/arlula-tasking-order-request-schema.json)
- [arlula-batch-tasking-order-request-schema](json-schema/arlula-batch-tasking-order-request-schema.json)
- [arlula-order-response-schema](json-schema/arlula-order-response-schema.json)
- [arlula-cancel-response-schema](json-schema/arlula-cancel-response-schema.json)
- [arlula-orders-list-response-schema](json-schema/arlula-orders-list-response-schema.json)
- [arlula-order-schema](json-schema/arlula-order-schema.json)
- [arlula-campaign-schema](json-schema/arlula-campaign-schema.json)
- [arlula-campaigns-list-response-schema](json-schema/arlula-campaigns-list-response-schema.json)
- [arlula-dataset-schema](json-schema/arlula-dataset-schema.json)
- [arlula-datasets-list-response-schema](json-schema/arlula-datasets-list-response-schema.json)
- [arlula-resource-schema](json-schema/arlula-resource-schema.json)

### JSON Structure

- [arlula-test-response-structure](json-structure/arlula-test-response-structure.json)
- [arlula-archive-search-request-structure](json-structure/arlula-archive-search-request-structure.json)
- [arlula-archive-scene-structure](json-structure/arlula-archive-scene-structure.json)
- [arlula-bundle-structure](json-structure/arlula-bundle-structure.json)
- [arlula-archive-order-request-structure](json-structure/arlula-archive-order-request-structure.json)
- [arlula-batch-archive-order-request-structure](json-structure/arlula-batch-archive-order-request-structure.json)
- [arlula-tasking-search-request-structure](json-structure/arlula-tasking-search-request-structure.json)
- [arlula-tasking-opportunity-structure](json-structure/arlula-tasking-opportunity-structure.json)
- [arlula-tasking-order-request-structure](json-structure/arlula-tasking-order-request-structure.json)
- [arlula-batch-tasking-order-request-structure](json-structure/arlula-batch-tasking-order-request-structure.json)
- [arlula-order-response-structure](json-structure/arlula-order-response-structure.json)
- [arlula-cancel-response-structure](json-structure/arlula-cancel-response-structure.json)
- [arlula-orders-list-response-structure](json-structure/arlula-orders-list-response-structure.json)
- [arlula-order-structure](json-structure/arlula-order-structure.json)
- [arlula-campaign-structure](json-structure/arlula-campaign-structure.json)
- [arlula-campaigns-list-response-structure](json-structure/arlula-campaigns-list-response-structure.json)
- [arlula-dataset-structure](json-structure/arlula-dataset-structure.json)
- [arlula-datasets-list-response-structure](json-structure/arlula-datasets-list-response-structure.json)
- [arlula-resource-structure](json-structure/arlula-resource-structure.json)

### JSON-LD

- [arlula-api-context](json-ld/arlula-api-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Arlula API](capabilities/shared/arlula-api.yaml) — 16 operations for archive search, tasking, order management, and dataset download

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Satellite Imagery Operations](capabilities/satellite-imagery-operations.yaml) | Arlula API | 11 | Geospatial Analyst, Remote Sensing Engineer |

## Vocabulary

- [Arlula Vocabulary](vocabulary/arlula-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 4 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Arlula Spectral Rules](rules/arlula-spectral-rules.yml) — 30 rules across 9 categories enforcing Arlula API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
