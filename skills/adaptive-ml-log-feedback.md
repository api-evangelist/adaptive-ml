---
name: Log interactions and feedback for training/evaluation
description: Record prompts/completions, pairwise comparisons, and outcomes so Adaptive Engine can score models and drive RL post-training.
api: openapi/adaptive-ml-openapi-original.json
operations: [Add interaction, Add comparison, Add outcome]
---

# Log interactions and feedback

Feed production signals back into Adaptive Engine to evaluate and continuously
improve models. Authenticate with `Authorization: Bearer <ADAPTIVE_API_KEY>`
against `ADAPTIVE_URL/api/v1`.

## Steps
1. **Record an interaction** — `POST /api/v1/interactions` (`Add interaction`):
   log a prompt/completion record (optionally with feedback/score metadata).
2. **Record a comparison** — `POST /api/v1/comparison` (`Add comparison`): log a
   pairwise preference between two completions (supports ties).
3. **Record an outcome** — `POST /api/v1/outcome` (`Add outcome`): attach an
   outcome/metric to a logged interaction.

## Notes
- As of v0.14.0, `Feedback` is renamed to `Score`; use `score.*` / `metrics.*`
  equivalents in the SDK/GraphQL. See `changelog/adaptive-ml-changelog.yml`.
- Interactions/comparisons/outcomes are the raw signal for graders and RL
  recipes; they are scoped to a project.
