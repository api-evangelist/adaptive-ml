---
name: Run inference on an Adaptive Engine model
description: Call an Adaptive Engine deployment for OpenAI-compatible chat completions and embeddings, with optional structured output.
api: openapi/adaptive-ml-openapi-original.json
operations: [Chat, Embeddings]
---

# Run inference on Adaptive Engine

Adaptive Engine is self-hosted. All calls go to your deployment base URL
(`ADAPTIVE_URL/api/v1`) and authenticate with a Bearer API key.

## Prerequisites
- `ADAPTIVE_URL` — your deployment URL.
- `ADAPTIVE_API_KEY` — a personal or service-account API key (`Authorization: Bearer <key>`).

## Steps
1. **Chat completion** — `POST /api/v1/chat/completions` (`Chat`). Send an
   OpenAI-shaped `messages` array plus the target model. Set `stream: true` for
   server-sent-event deltas. Constrain output with `response_format` (plain text,
   a JSON Schema, or a Pydantic model in the Python SDK).
2. **Embeddings** — `POST /api/v1/embeddings` (`Embeddings`) for vector
   representations of input text.

## Notes
- The API is OpenAI-compatible: the OpenAI Python/JS client works with
  `base_url=ADAPTIVE_URL/api/v1`, `api_key=ADAPTIVE_API_KEY`.
- Errors are plain HTTP status codes (403 auth/permission, 404 not found, 500
  server error) — see `errors/adaptive-ml-problem-types.yml`.
