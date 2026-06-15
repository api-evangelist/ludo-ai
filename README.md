# Ludo.ai (ludo-ai)

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
