# Adaptive ML

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

Adaptive ML builds Adaptive Engine, an enterprise platform for developing, evaluating, and serving specialized open-source large language models via reinforcement-learning post-training. The three-phase workflow (Adapt, Evaluate, Serve) lets teams fine-tune smaller models to outperform commercial APIs, measure them with custom AI judges and graders, and feed production signals back into training. Adaptive Engine is self-hosted (Kubernetes/Helm) and exposes an OpenAI-compatible REST API for chat completions and embeddings, plus interactions, comparisons, outcomes, dataset/recipe management, and chunked uploads. Tooling includes the Python adaptive-sdk and adaptive-harmony libraries and the adpt CLI. Adaptive ML was acquired by Datadog.

**Areas:** Company · Artificial Intelligence · LLM · Fine-Tuning · Reinforcement Learning · Model Evaluation · Inference · OpenAI-Compatible · MLOps

## Adaptive ML on APIs.io

Everything profiled for Adaptive ML is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/adaptive-ml/](https://apis.io/providers/adaptive-ml/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Adaptive ML artifacts::rest API](https://apis.io/apis/adaptive-ml/adaptive-ml-artifacts-rest-api/) — The artifacts::rest API from Adaptive ML — 1 operation(s) for artifacts::rest.
- [Adaptive ML Chunked Upload API](https://apis.io/apis/adaptive-ml/adaptive-ml-chunked-upload-api/) — Upload large files in chunks
- [Adaptive ML Completions API](https://apis.io/apis/adaptive-ml/adaptive-ml-completions-api/) — The Completions API from Adaptive ML — 1 operation(s) for completions.
- [Adaptive ML Datasets API](https://apis.io/apis/adaptive-ml/adaptive-ml-datasets-api/) — The Datasets API from Adaptive ML — 1 operation(s) for datasets.
- [Adaptive ML Embeddings API](https://apis.io/apis/adaptive-ml/adaptive-ml-embeddings-api/) — The Embeddings API from Adaptive ML — 1 operation(s) for embeddings.
- [Adaptive ML Feedback API](https://apis.io/apis/adaptive-ml/adaptive-ml-feedback-api/) — The Feedback API from Adaptive ML — 2 operation(s) for feedback.
- [Adaptive ML image::rest API](https://apis.io/apis/adaptive-ml/adaptive-ml-image-rest-api/) — The image::rest API from Adaptive ML — 1 operation(s) for image::rest.
- [Adaptive ML Interactions API](https://apis.io/apis/adaptive-ml/adaptive-ml-interactions-api/) — Load interactions in the db
- [Adaptive ML Recipes API](https://apis.io/apis/adaptive-ml/adaptive-ml-recipes-api/) — Recipe operations

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Adaptive Ml Webhooks](https://apis.io/asyncapis/adaptive-ml/adaptive-ml-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [adaptive-ml](https://apis.io/servers/adaptive-ml/adaptive-ml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Adaptive Ml Agentic Access](https://apis.io/agentic-access/adaptive-ml/adaptive-ml-agentic-access/)

#### Collections (9)

Postman and Open Collection request collections.

- [concorde artifacts::rest API](https://apis.io/collections/adaptive-ml/open-adaptive-ml-artifacts-rest-api/)
- [concorde artifacts::rest Chunked Upload API](https://apis.io/collections/adaptive-ml/open-adaptive-ml-chunked-upload-api/)
- [concorde artifacts::rest Completions API](https://apis.io/collections/adaptive-ml/open-adaptive-ml-completions-api/)
- [concorde artifacts::rest Datasets API](https://apis.io/collections/adaptive-ml/open-adaptive-ml-datasets-api/)
- [concorde artifacts::rest Embeddings API](https://apis.io/collections/adaptive-ml/open-adaptive-ml-embeddings-api/)
- [concorde artifacts::rest Feedback API](https://apis.io/collections/adaptive-ml/open-adaptive-ml-feedback-api/)
- [concorde artifacts::rest image::rest API](https://apis.io/collections/adaptive-ml/open-adaptive-ml-image-rest-api/)
- [concorde artifacts::rest Interactions API](https://apis.io/collections/adaptive-ml/open-adaptive-ml-interactions-api/)
- [concorde artifacts::rest Recipes API](https://apis.io/collections/adaptive-ml/open-adaptive-ml-recipes-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Adaptive Ml Openapi Overlay](https://apis.io/overlays/adaptive-ml/adaptive-ml-openapi-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Adaptive Ml Authentication](https://apis.io/security/adaptive-ml/adaptive-ml-authentication/)
- [Adaptive Ml Domain Security](https://apis.io/security/adaptive-ml/adaptive-ml-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.adaptive-ml.com)
- [Documentation](https://docs.adaptive-ml.com/v0.14/introduction)
- [Getting started](https://docs.adaptive-ml.com/quickstart)
- [API reference](https://docs.adaptive-ml.com/v0.14/reference/api)
- [Sign up](https://www.adaptive-ml.com/book-a-demo)
- [Support](https://www.adaptive-ml.com/contact-us)
- [Blog](https://www.adaptive-ml.com/blog)
- [Privacy policy](https://www.adaptive-ml.com/privacy)
- [GitHub](https://github.com/adaptive-ml)

## API Evangelist rating

**Kin Score 39.7** — developing · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 46.2 |
| Contract governance | 4.5 |
| Operational transparency | 26.3 |
| Developer ergonomics | 61.3 |
| Access clarity | 23.7 |

**Agent readiness 23.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 19.1** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/adaptive-ml/](https://apis.io/providers/adaptive-ml/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Adaptive ML: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/adaptive-ml/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
