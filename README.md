# Arlula (arlula)

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

Arlula is a satellite imagery marketplace and API platform providing programmatic access to archive and tasking satellite imagery from multiple providers. The Arlula API enables developers to search the global satellite archive, discover tasking opportunities, place imagery orders, and download delivered datasets including GeoTIFF imagery, preview images, and metadata files.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/arlula/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/arlula/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Earth Observation
- Geospatial
- Imagery
- Remote Sensing
- Satellites

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-19

## APIs

### Arlula API

The Arlula API provides programmatic access to satellite imagery search, ordering, and delivery. It covers archive search for historical imagery, tasking for future satellite captures, and order management including campaign, dataset, and resource download operations. Authentication uses HTTP Basic with API Key and API Secret obtained from the Arlula dashboard.

- **Human URL:** [https://arlula.com/documentation/](https://arlula.com/documentation/)
- **Base URL:** `https://api.arlula.com`

#### Tags

- Archive
- Earth Observation
- Imagery
- Satellites
- Tasking

#### Properties

- [Documentation](https://arlula.com/documentation/)
- [OpenAPI](openapi/arlula-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Open Collection](collections/arlula.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/arlula-archive-scene-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arlula-archive-search-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arlula-tasking-opportunity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arlula-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/arlula-archive-scene-structure.json)
- [JSON Structure](json-structure/arlula-tasking-opportunity-structure.json)
- [JSON Structure](json-structure/arlula-order-structure.json)
- [JSON-LD](json-ld/arlula-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/arlula)
- [Website](https://arlula.com/)
- [Documentation](https://arlula.com/documentation/)
- [Getting Started](https://arlula.com/documentation/)
- [Portal](https://dashboard.arlula.com)
- [GitHub Organization](https://github.com/Arlula)
- [Spectral Rules](rules/arlula-spectral-rules.yml)
- [Vocabulary](vocabulary/arlula-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
