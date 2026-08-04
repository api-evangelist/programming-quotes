# Programming Quotes (programming-quotes)

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

Free, open-source REST API serving a curated collection of programming-related quotes. Public endpoints return random quotes, paginated lists, author filters, and single quote lookups; authenticated endpoints support voting, favoriting, and quote authorship (CRUD). Originally seeded from the skolakoda community project on GitHub, the API is widely used as a demo data source and a free data feed for developer portfolio sites, tutorials, CLIs, and IDE extensions.

**APIs.json:** [https://github.com/skolakoda/programming-quotes-api](https://github.com/skolakoda/programming-quotes-api)

## Tags

- Personality
- Public APIs
- Open Source
- Quotes
- Programming
- Developer Tools

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Programming Quotes

Public read endpoints (no auth) plus authenticated write endpoints over a MongoDB-backed corpus of programming quotes. Provides random quote lookups, paginated lists, author filtering, and full CRUD for authenticated contributors.

- **Human URL:** [https://github.com/skolakoda/programming-quotes-api](https://github.com/skolakoda/programming-quotes-api)
- **Base URL:** `https://programming-quotes-api.azurewebsites.net/api`

#### Tags

- Personality
- Quotes
- Programming

#### Properties

- [Documentation](https://github.com/skolakoda/programming-quotes-api#readme)
- [Source Code](https://github.com/skolakoda/programming-quotes-api)
- [OpenAPI](openapi/programming-quotes-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Sign Up](https://github.com/skolakoda/programming-quotes-api#auth)
- [JSON Schema](json-schema/programming-quotes-quote-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/programming-quotes-quote-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/programming-quotes-quote-update-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/programming-quotes-vote-input-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/programming-quotes-auth-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/programming-quotes-auth-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/programming-quotes-quote-structure.json)
- [JSON Structure](json-structure/programming-quotes-quote-input-structure.json)
- [JSON Structure](json-structure/programming-quotes-quote-update-structure.json)
- [JSON Structure](json-structure/programming-quotes-vote-input-structure.json)
- [JSON Structure](json-structure/programming-quotes-auth-request-structure.json)
- [JSON Structure](json-structure/programming-quotes-auth-response-structure.json)
- [Examples](examples/programming-quotes-quote-example.json)
- [Examples](examples/programming-quotes-quote-input-example.json)
- [Examples](examples/programming-quotes-quote-update-example.json)
- [Examples](examples/programming-quotes-vote-input-example.json)
- [Examples](examples/programming-quotes-auth-request-example.json)
- [Examples](examples/programming-quotes-auth-response-example.json)

## Common Properties

- [Website](https://github.com/skolakoda/programming-quotes-api)
- [Source Code](https://github.com/skolakoda/programming-quotes-api)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [GitHub Organization](https://github.com/skolakoda)
- [License](https://github.com/skolakoda/programming-quotes-api)
- [Spectral Ruleset](rules/programming-quotes-rules.yml)
- [Vocabulary](vocabulary/programming-quotes-vocabulary.yml)
- [J S O N L D Context](json-ld/programming-quotes-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
