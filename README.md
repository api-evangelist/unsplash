# Unsplash (unsplash)

Unsplash is a platform providing the world's largest collection of high-quality, freely usable photographs. The Unsplash API gives developers programmatic access to search, browse, and retrieve photos, collections, topics, and user profiles. Photos are provided under the Unsplash License. Authentication uses Client-ID for public access or OAuth 2.0 for user-delegated operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Photos
- Images
- Photography
- Stock Photos
- Creative
- Open Source
- Media

## Timestamps

- **Created:** 2024-11-13
- **Modified:** 2026-05-19

## APIs

### Unsplash API

REST API providing access to Unsplash's full photo library with endpoints for photo search, random photos, editorial feed browsing, photo detail and statistics, collection management, topic browsing, and user profiles. Returns JSON responses with multiple photo size URLs (raw, full, regular, small, thumb) via imgix CDN. Rate limit: 50 req/hr (demo), 1000 req/hr (production). Download tracking via /photos/{id}/download is required per Unsplash API guidelines.

- **Human URL:** [https://unsplash.com/developers](https://unsplash.com/developers)
- **Base URL:** `https://api.unsplash.com`

#### Tags

- Photos
- Search
- Collections
- Topics
- Statistics

#### Properties

- [Documentation](https://unsplash.com/documentation)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/openapi/unsplash-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/rules/unsplash-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/json-schema/unsplash-photo-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/unsplash.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/unsplash.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/unsplash)
- [Website](https://unsplash.com)
- [Documentation](https://unsplash.com/documentation)
- [Developers](https://unsplash.com/developers)
- [Guidelines](https://help.unsplash.com/en/articles/2511245-unsplash-api-guidelines)
- [Git Hub](https://github.com/unsplash)
- [Changelog](https://unsplash.com/documentation/changelog)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/vocabulary/unsplash-vocabulary.yml)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/unsplash/refs/heads/main/json-ld/unsplash-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
