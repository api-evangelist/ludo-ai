# Ludo.ai (ludo-ai)
Ludo.ai is an AI-powered game design platform that helps developers generate production-ready game assets including images, 3D models, audio, and animations. The platform offers a REST API for programmatic control, an MCP server for conversational asset generation through AI assistants, and a Unity plugin for in-editor workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ludo-ai/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Game Development, Artificial Intelligence, Asset Generation, Game Design

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-03-24

## APIs

### Ludo.ai REST API
The Ludo.ai REST API provides programmatic access to the full suite of AI-powered game asset generation capabilities. Developers can generate sprites, icons, UI assets, textures, and backgrounds through image generation endpoints, convert 2D images to 3D GLB models with PBR textures, create animated spritesheets from static images, and produce sound effects, music tracks, and character voices. All API requests require an API key passed via the Authentication header, and requests consume credits that vary by endpoint type. The API is currently in beta.

**Human URL:** [https://ludo.ai/api-mcp-integration](https://ludo.ai/api-mcp-integration)


#### Tags:

 - Game Development, Asset Generation, Images, 3D Models, Audio, Animation, Sprites

#### Properties

- [Documentation](https://ludo.ai/api-mcp-integration)
- [OpenAPI](openapi/ludo-ai-rest-api-openapi.yml)

### Ludo.ai MCP Server
The Ludo.ai MCP Server exposes the platform's asset generation tools via the Model Context Protocol, allowing AI assistants like Claude and Cursor to generate game assets through natural language conversations. The server provides over 20 tools including createImage, editImage, animateSprite, create3DModel, createSoundEffect, createMusic, createVoice, and createVideo. Developers can add the MCP server to their AI assistant configuration using the endpoint at mcp.ludo.ai and authenticate with their API key. This enables a vibe coding workflow where production-ready game assets are created directly within the development environment.

**Human URL:** [https://ludo.ai/docs/api-mcp](https://ludo.ai/docs/api-mcp)


#### Tags:

 - Game Development, Model Context Protocol, AI Assistants, Asset Generation, Vibe Coding

#### Properties

- [Documentation](https://ludo.ai/docs/api-mcp)
- [GitHubRepository](https://github.com/Ludo-AI/ludo-mcp)

### Ludo.ai Unity Plugin
The Ludo.ai Unity Plugin integrates AI-powered asset generation directly into the Unity game engine. It provides a native interface for Unity developers to access Ludo.ai's image generation, 3D model creation, audio production, and animation tools without leaving the editor. The plugin connects to the Ludo.ai API to deliver generated assets directly into Unity projects, streamlining the game development workflow.

**Human URL:** [https://github.com/Ludo-AI/ludo-unity-plugin](https://github.com/Ludo-AI/ludo-unity-plugin)


#### Tags:

 - Game Development, Unity, Plugin, Asset Generation

#### Properties

- [Documentation](https://github.com/Ludo-AI/ludo-unity-plugin)

## Common Properties

- [Portal](https://ludo.ai/api-mcp-integration)
- [Documentation](https://ludo.ai/docs)
- [Website](https://ludo.ai/)
- [Blog](https://ludo.ai/blog/introducing-ludo-ai-api-mcp-integration)
- [GitHubOrganization](https://github.com/Ludo-AI)
- [Login](https://ludo.ai/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
