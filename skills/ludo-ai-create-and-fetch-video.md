---
name: ludo-ai-create-and-fetch-video
description: Create a new video asset and retrieve its processing results.
api: openapi/ludo-ai-openapi.json
operations:
- createVideo
- getVideoResults
generated: '2026-10-02'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/ludo-ai-openapi.json ; every operationId checked against the contract
---

# ludo-ai-create-and-fetch-video

Create a new video asset and retrieve its processing results.

## Steps

1. 1. Call `createVideo` with the required request body fields (e.g., `prompt`, `duration`, `resolution`).
2. 2. Call `getVideoResults` with the query parameter `videoId` returned from `createVideo` to obtain the generated video URL and status.

## Rules

- Include an `Authorization` header with the API key (ApiKey scheme).
- If the operation fails, handle HTTP error responses as defined by the API (e.g., 4xx for client errors, 5xx for server errors).
