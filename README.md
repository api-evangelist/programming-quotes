# Programming Quotes (programming-quotes)

Free, open-source REST API serving a curated collection of programming-related quotes. Public endpoints return random quotes, paginated lists, author filters, and single quote lookups; authenticated endpoints support voting, favoriting, and quote authorship (CRUD). Originally seeded from the skolakoda community project on GitHub, the API is widely used as a demo data source and a free data feed for developer portfolio sites, tutorials, CLIs, and IDE extensions.

**URL:** [Visit APIs.json URL](https://github.com/skolakoda/programming-quotes-api)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Personality, Public APIs, Open Source, Quotes, Programming, Developer Tools

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Programming Quotes

Public read endpoints (no auth) plus authenticated write endpoints over a MongoDB-backed corpus of programming quotes. Provides random quote lookups, paginated lists, author filtering, and full CRUD for authenticated contributors.

**Human URL:** [https://github.com/skolakoda/programming-quotes-api](https://github.com/skolakoda/programming-quotes-api)

**Base URL:** `https://programming-quotes-api.azurewebsites.net/api`

#### Tags:

 - Personality, Quotes, Programming

#### Properties

- [Documentation](https://github.com/skolakoda/programming-quotes-api#readme)
- [SourceCode](https://github.com/skolakoda/programming-quotes-api)
- [OpenAPI](openapi/programming-quotes-openapi.yml)
- [SignUp](https://github.com/skolakoda/programming-quotes-api#auth)
- [Naftiko Capability — Quotes](capabilities/programming-quotes-quotes.yaml)
- [Naftiko Capability — Authentication](capabilities/programming-quotes-authentication.yaml)

## Common Properties

- [Website](https://github.com/skolakoda/programming-quotes-api)
- [SourceCode](https://github.com/skolakoda/programming-quotes-api)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [GitHubOrganization](https://github.com/skolakoda)
- [License — Unlicensed (community / open-source)](https://github.com/skolakoda/programming-quotes-api)
- [Spectral Ruleset](rules/programming-quotes-rules.yml)
- [Vocabulary](vocabulary/programming-quotes-vocabulary.yml)
- [JSON-LD Context](json-ld/programming-quotes-context.jsonld)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Programming Quotes — OpenAPI 3.0.3](openapi/programming-quotes-openapi.yml)

### JSON Schema

- [Quote](json-schema/programming-quotes-quote-schema.json)
- [QuoteInput](json-schema/programming-quotes-quote-input-schema.json)
- [QuoteUpdate](json-schema/programming-quotes-quote-update-schema.json)
- [VoteInput](json-schema/programming-quotes-vote-input-schema.json)
- [AuthRequest](json-schema/programming-quotes-auth-request-schema.json)
- [AuthResponse](json-schema/programming-quotes-auth-response-schema.json)

### JSON Structure

- [Quote](json-structure/programming-quotes-quote-structure.json)
- [QuoteInput](json-structure/programming-quotes-quote-input-structure.json)
- [QuoteUpdate](json-structure/programming-quotes-quote-update-structure.json)
- [VoteInput](json-structure/programming-quotes-vote-input-structure.json)
- [AuthRequest](json-structure/programming-quotes-auth-request-structure.json)
- [AuthResponse](json-structure/programming-quotes-auth-response-structure.json)

### JSON-LD

- [Programming Quotes Context](json-ld/programming-quotes-context.jsonld)

### Examples

- [Quote example](examples/programming-quotes-quote-example.json)
- [QuoteInput example](examples/programming-quotes-quote-input-example.json)
- [QuoteUpdate example](examples/programming-quotes-quote-update-example.json)
- [VoteInput example](examples/programming-quotes-vote-input-example.json)
- [AuthRequest example](examples/programming-quotes-auth-request-example.json)
- [AuthResponse example](examples/programming-quotes-auth-response-example.json)

## Capabilities

Naftiko capabilities — one self-contained file per OpenAPI tag, each with inline `consumes` plus both REST and MCP exposers.

### Programming Quotes

| Capability | Operations | Tools | Persona |
|------------|-----------:|------:|---------|
| [Programming Quotes — Quotes](capabilities/programming-quotes-quotes.yaml) | 8 | 8 | Developer / Bot Operator / Educator / Contributor |
| [Programming Quotes — Authentication](capabilities/programming-quotes-authentication.yaml) | 1 | 1 | Contributor |

## Vocabulary

- [Programming Quotes Vocabulary](vocabulary/programming-quotes-vocabulary.yml) — Unified taxonomy mapping 3 resources, 9 actions, 2 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Programming Quotes Spectral Rules](rules/programming-quotes-rules.yml) — 38 opinionated Spectral rules enforcing Programming Quotes API conventions (kebab-case paths, camelCase parameters and operationIds, JWT bearer security on writes, "Programming Quotes" summary prefix, Title-Case tags, error responses with `message`).

## Notes

- **Source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Personality
- **x-type:** opensource (community)
- **x-tier:** 3 (bulk-registered from public-apis)
- Current canonical live URL: `https://programming-quotes-api.azurewebsites.net/api`. Community mirrors at `programming-quotesapi.vercel.app`, `api.programming-quotes.onrender.com`, and `programming-quotes-api.herokuapp.com` are documented as alternate servers in the OpenAPI spec.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
