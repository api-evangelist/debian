# Debian (debian)

Debian is a free operating system distribution maintained by the Debian Project, a community of more than a thousand volunteers worldwide. Debian provides a number of developer-facing services including a source-code browsing API at sources.debian.org, the Bug Tracking System (BTS) at bugs.debian.org, and the Ultimate Debian Database (UDD).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public
- **x-type:** opensource

## Tags

- Bug Tracker, Debian, Linux, Open Source, Operating System, Package Management, Source Code

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### Debian Sources API

The Debian Sources API at sources.debian.org provides programmatic access to source code, package metadata, copyright records, and Debian patches for every source package in the archive.

- **Base URL:** https://sources.debian.org/api
- **Human URL:** https://sources.debian.org/doc/api/

#### Properties

- [Documentation](https://sources.debian.org/doc/api/)
- [OpenAPI](openapi/debian-sources-api-openapi.yml)
- [JSONSchema - Package](json-schema/debian-package.json)
- [Rules](rules/debian-sources-api-rules.yml)
- [Capabilities](capabilities/debian-sources-api-capabilities.yml)

### Debian Bug Tracking System

The Debian BTS at bugs.debian.org tracks bugs against packages and pseudo-packages. Bug reports are accessible as machine-readable mbox files and structured CGI views, with email serving as the canonical interaction surface.

- **Base URL:** https://bugs.debian.org
- **Human URL:** https://www.debian.org/Bugs/

#### Properties

- [Documentation](https://www.debian.org/Bugs/)
- [OpenAPI](openapi/debian-bts-api-openapi.yml)
- [JSONSchema - Bug](json-schema/debian-bug.json)

### Debian Ultimate Database (UDD)

The Ultimate Debian Database aggregates Debian-wide data into a single Postgres database and exposes web tools for bugs, maintainer dashboards, Lintian results, reproducibility, and more.

- **Base URL:** https://udd.debian.org
- **Human URL:** https://wiki.debian.org/UltimateDebianDatabase

#### Properties

- [Documentation](https://wiki.debian.org/UltimateDebianDatabase)
- [OpenAPI](openapi/debian-udd-api-openapi.yml)

## Common Properties

- [Website](https://www.debian.org/)
- [Wiki](https://wiki.debian.org/)
- [Documentation](https://www.debian.org/doc/)
- [Salsa GitLab](https://salsa.debian.org/)
- [Mailing Lists](https://lists.debian.org/)
- [JSON-LD](json-ld/debian-context.jsonld)
- [Vocabulary](vocabulary/debian-vocabulary.yml)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
