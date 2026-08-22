# Ludo.ai (ludo-ai)

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

Ludo.ai is a game design hub that uses artificial intelligence to help developers generate production-ready game assets including images, 3D models, audio, and animations. The platform entered beta for its Model Context Protocol (MCP) integration, exposing its asset generation suite as a headless API that enables vibe coding where developers can trigger asset creation directly from AI assistants like Claude or Cursor.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ludo-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ludo-ai/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Artificial Intelligence
- Asset Generation
- Game Design
- Game Development

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### Ludo.ai REST API

The Ludo.ai REST API provides programmatic access to the full suite of AI-powered game asset generation capabilities. Developers can generate sprites, icons, UI assets, textures, and backgrounds through image generation endpoints, convert 2D images to 3D GLB models with PBR textures, create animated spritesheets from static images, and produce sound effects, music tracks, and character voices.

- **Human URL:** [https://ludo.ai/api-mcp-integration](https://ludo.ai/api-mcp-integration)
- **Base URL:** `https://api.ludo.ai/api/`

#### Tags

- 3D Models
- Animation
- Asset Generation
- Audio
- Game Development
- Images
- Sprites

#### Properties

- [Documentation](https://ludo.ai/api-mcp-integration)
- [OpenAPI](openapi/ludo-ai-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ludo-ai-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ludo-ai-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ludo.ai MCP Server

The Ludo.ai MCP Server exposes the platform's asset generation tools via the Model Context Protocol, allowing AI assistants like Claude and Cursor to generate game assets through natural language conversations. The server provides over 20 tools including createImage, editImage, animateSprite, create3DModel, createSoundEffect, createMusic, createVoice, and createVideo.

- **Human URL:** [https://ludo.ai/docs/api-mcp](https://ludo.ai/docs/api-mcp)
- **Base URL:** `https://mcp.ludo.ai/mcp`

#### Tags

- AI Assistants
- Asset Generation
- Game Development
- Model Context Protocol
- Vibe Coding

#### Properties

- [Documentation](https://ludo.ai/docs/api-mcp)
- [GitHub Repository](https://github.com/Ludo-AI/ludo-mcp)
- [Postman Collection](collections/ludo-ai-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ludo-ai-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ludo.ai Unity Plugin

The Ludo.ai Unity Plugin integrates AI-powered asset generation directly into the Unity game engine. It provides a native interface for Unity developers to access Ludo.ai's image generation, 3D model creation, audio production, and animation tools without leaving the editor. The plugin connects to the Ludo.ai API to deliver generated assets directly into Unity projects, streamlining the game development workflow.

- **Human URL:** [https://github.com/Ludo-AI/ludo-unity-plugin](https://github.com/Ludo-AI/ludo-unity-plugin)
- **Base URL:** `https://api.example.com`

#### Tags

- Asset Generation
- Game Development
- Plugin
- Unity

#### Properties

- [Documentation](https://github.com/Ludo-AI/ludo-unity-plugin)
- [Postman Collection](collections/ludo-ai-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ludo-ai-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/ludoai)
- [JSON-LD](json-ld/ludo-ai-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/ludo-ai-game-asset-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Website](https://ludo.ai/)
- [Portal](https://ludo.ai/api-mcp-integration)
- [Documentation](https://ludo.ai/docs)
- [Blog](https://ludo.ai/blog/introducing-ludo-ai-api-mcp-integration)
- [GitHub Organization](https://github.com/Ludo-AI)
- [Login](https://ludo.ai/)
- [M C P Server](https://github.com/Ludo-AI/ludo-mcp)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
