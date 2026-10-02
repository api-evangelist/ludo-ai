---
name: ludo-ai-generate-and-edit-image
description: Generate a new game-ready image and then edit it.
api: openapi/ludo-ai-images-api-openapi.yml
operations:
- createImage
- editImage
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/ludo-ai-images-api-openapi.yml ; every operationId checked against the contract
---

# ludo-ai-generate-and-edit-image

Generate a new game-ready image and then edit it.

## Steps

1. 1. Call `createImage` with the request body fields required for image generation (e.g., prompt, size, format).
2. 2. Call `editImage` with the image ID returned from `createImage` and the edit parameters (e.g., modifications, mask).

## Rules

- Auth: include an API key in the `Authorization` header (scheme `ApiKey`).
- Idempotency: not required for these POST operations.
