# Unsplash

Unsplash is the world's largest open collection of high-quality photographs. The Unsplash API gives developers programmatic access to search, browse, and retrieve photos, collections, topics, and user profiles. Photos are provided under the Unsplash License and are free for commercial and personal use.

**Website:** [unsplash.com](https://unsplash.com)
**Developers:** [unsplash.com/developers](https://unsplash.com/developers)
**Documentation:** [unsplash.com/documentation](https://unsplash.com/documentation)
**GitHub:** [github.com/unsplash](https://github.com/unsplash)

---

## API

### Unsplash API (v1.0.0)

REST API for photo discovery, search, collection management, and user profiles.

- Base URL: `https://api.unsplash.com`
- Auth: `Authorization: Client-ID {YOUR_ACCESS_KEY}` (public) or OAuth 2.0 (user operations)
- Rate limit: 50 req/hr (demo), 1,000 req/hr (production)
- Important: Must call `/photos/{id}/download` when a user downloads a photo

**Operations by resource:**

| Resource | Methods |
|---|---|
| **Photos** | list, get, random, update, statistics, track download |
| **Search** | search photos, collections, users |
| **Collections** | list, get, create, update, delete, add/remove photos |
| **Topics** | list, get, get photos |
| **Users** | get profile, list photos, list collections, statistics |
| **Current User** | get profile, update profile |
| **Stats** | totals, monthly |

- [OpenAPI Specification](openapi/unsplash-openapi.yml)

---

## Artifacts

### OpenAPI
| File | Description |
|---|---|
| [unsplash-openapi.yml](openapi/unsplash-openapi.yml) | Full Unsplash API OpenAPI 3.0.3 specification (31 operations) |

### Spectral Rules
| File | Description |
|---|---|
| [unsplash-rules.yml](rules/unsplash-rules.yml) | Spectral ruleset for Unsplash API conventions |

### Capabilities (Naftiko)
| File | Description |
|---|---|
| [shared/unsplash.yaml](capabilities/shared/unsplash.yaml) | Shared Unsplash API consumed definition |
| [photo-discovery.yaml](capabilities/photo-discovery.yaml) | Photo discovery workflow (8 tools) |

### JSON Schema
| File | Description |
|---|---|
| [unsplash-photo-schema.json](json-schema/unsplash-photo-schema.json) | Photo entity schema |

### JSON Structure
| File | Description |
|---|---|
| [unsplash-photo-structure.json](json-structure/unsplash-photo-structure.json) | Photo field documentation |

### JSON-LD Context
| File | Description |
|---|---|
| [unsplash-context.jsonld](json-ld/unsplash-context.jsonld) | Linked data context mapping Unsplash concepts to schema.org, EXIF, IPTC |

### Examples
| File | Description |
|---|---|
| [unsplash-search-photos-example.json](examples/unsplash-search-photos-example.json) | Photo search request/response |
| [unsplash-get-random-photo-example.json](examples/unsplash-get-random-photo-example.json) | Random photo request/response |

### Vocabulary
| File | Description |
|---|---|
| [unsplash-vocabulary.yml](vocabulary/unsplash-vocabulary.yml) | Domain vocabulary for Unsplash platform concepts |

---

## APIs Index

- [apis.yml](apis.yml)

---

*Maintained by [API Evangelist](https://apievangelist.com)*
