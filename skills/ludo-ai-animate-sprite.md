---
name: ludo-ai-animate-sprite
description: Create an animation for a sprite and retrieve the resulting animation data.
api: openapi/ludo-ai-openapi.json
operations:
- animateSprite
- listAnimationPresets
- getSpriteResults
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/ludo-ai-openapi.json ; every operationId checked against the contract
---

# ludo-ai-animate-sprite

Create an animation for a sprite and retrieve the resulting animation data.

## Steps

1. 1. Call `animateSprite` with the required request body fields (e.g., `spriteId`, `animationParameters`).
2. 2. Optionally call `listAnimationPresets` to view available preset animations before animating.
3. 3. Call `getSpriteResults` with the query parameter `spriteId` (or result identifier) to fetch the generated animation.

## Rules

- Auth: Include an API key in the `Authorization` header (scheme `ApiKey`).
- Idempotency: Not required for these POST operations.
- Pagination: Not applicable to the listed operations.
- Errors: The API returns standard HTTP error codes; on rate‑limit exhaustion no specific limit is defined.
