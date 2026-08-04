# Debian (debian)

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

Debian is a free operating system distribution maintained by the Debian Project, a community of more than a thousand volunteers worldwide. Debian provides a number of developer-facing services including a source-code browsing API at sources.debian.org, the Bug Tracking System (BTS) at bugs.debian.org, and the Ultimate Debian Database (UDD) - a single Postgres database aggregating package, bug, Lintian, popcon, and reproducibility data for cross-cutting queries.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- Bug Tracker
- Debian
- Linux
- Open Source
- Operating System
- Package Management
- Source Code

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Debian Sources API

The Debian Sources API at sources.debian.org provides programmatic access to source code, package metadata, copyright records, and Debian patches for every source package in the archive.

- **Human URL:** [https://sources.debian.org/doc/api/](https://sources.debian.org/doc/api/)
- **Base URL:** `https://sources.debian.org/api`

#### Tags

- Copyright
- Packages
- Patches
- Source Code

#### Properties

- [Documentation](https://sources.debian.org/doc/api/)
- [OpenAPI](openapi/debian-sources-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/debian-sources-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/debian-sources-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/debian-package.json) — [JSON Schema](https://json-schema.org/specification)
- [Rules](rules/debian-sources-api-rules.yml)
- [Capabilities](capabilities/debian-sources-api-capabilities.yml)

### Debian Bug Tracking System

The Debian BTS at bugs.debian.org tracks bugs against packages and pseudo-packages. Bug reports are accessible as machine-readable mbox files and structured CGI views, with email serving as the canonical interaction surface.

- **Human URL:** [https://www.debian.org/Bugs/](https://www.debian.org/Bugs/)
- **Base URL:** `https://bugs.debian.org`

#### Tags

- Bugs
- Maintainers
- Severity

#### Properties

- [Documentation](https://www.debian.org/Bugs/)
- [OpenAPI](openapi/debian-bts-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/debian-bts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/debian-bts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/debian-bug.json) — [JSON Schema](https://json-schema.org/specification)

### Debian Ultimate Database (UDD)

The Ultimate Debian Database aggregates Debian-wide data into a single Postgres database and exposes web tools for bugs, maintainer dashboards, Lintian results, reproducibility, and more.

- **Human URL:** [https://wiki.debian.org/UltimateDebianDatabase](https://wiki.debian.org/UltimateDebianDatabase)
- **Base URL:** `https://udd.debian.org`

#### Tags

- Aggregated Data
- Lintian
- Reproducibility
- SQL

#### Properties

- [Documentation](https://wiki.debian.org/UltimateDebianDatabase)
- [OpenAPI](openapi/debian-udd-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/debian-udd-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/debian-udd-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Debian)
- [LinkedIn](https://www.linkedin.com/company/debian)
- [Website](https://www.debian.org/)
- [Wiki](https://wiki.debian.org/)
- [Documentation](https://www.debian.org/doc/)
- [Git Lab](https://salsa.debian.org/)
- [Mailing  Lists](https://lists.debian.org/)
- [Privacy Policy](https://www.debian.org/legal/privacy)
- [License](https://www.debian.org/social_contract)
- [JSON-LD](json-ld/debian-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/debian-vocabulary.yml)
- [Integrations](https://www.debian.org/partners/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
