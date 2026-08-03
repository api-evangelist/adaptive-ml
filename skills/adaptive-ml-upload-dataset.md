---
name: Upload a large dataset via chunked upload
description: Upload large training/evaluation files to Adaptive Engine using the chunked-upload session API (init, part, status, abort).
api: openapi/adaptive-ml-openapi-original.json
operations: [Initialize Chunked Upload, Upload Part, Get Upload Session Status, Abort Chunked Upload]
---

# Upload a large dataset (chunked upload)

Large files are uploaded through an explicit chunked-upload session, which makes
the upload resumable and idempotent-by-session. Authenticate with
`Authorization: Bearer <ADAPTIVE_API_KEY>` against `ADAPTIVE_URL/api/v1`.

## Steps
1. **Initialize** — `POST /api/v1/upload/init` (`Initialize Chunked Upload`) with
   `total_parts_count` (and optional `content_type`/`metadata`). Returns a
   session id.
2. **Upload parts** — `POST /api/v1/upload/part` (`Upload Part`) for each chunk,
   referencing the session id and part number.
3. **Check status** — `POST /api/v1/upload/status` (`Get Upload Session Status`)
   to confirm all parts landed.
4. **Abort if needed** — `DELETE /api/v1/upload/abort` (`Abort Chunked Upload`)
   to cancel a session and discard uploaded parts.

## Notes
- There is no generic `Idempotency-Key` header; the session id is the unit of
  idempotency/retry. See `conventions/adaptive-ml-conventions.yml`.
- Once uploaded, datasets are downloadable per project via `Download dataset`.
