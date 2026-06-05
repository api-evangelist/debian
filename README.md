# Debian (debian)

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
