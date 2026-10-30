# Laminar

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

Laminar is an open-source, OpenTelemetry-native observability and debugging platform built for AI agents and LLM applications. It traces every LLM call, tool call, and sub-agent a run produces, renders each trace as a readable transcript rather than a raw span tree, and turns that data into answers: a record-and-replay Debugger that serves everything before your change from cache so each iteration takes seconds, and Signals that let you describe outcomes and failures in plain language and extract structured events across all traces for clustering and alerting. The platform adds evaluations, datasets and labeling queues, a playground, full-text search, custom dashboards, and read-only ClickHouse SQL over trace data from the UI, the lmnr-cli, or a hosted MCP server. Laminar ships TypeScript and Python SDKs with auto-instrumentation for the Vercel AI SDK, Claude Agent SDK, OpenAI Agents SDK, LangChain/LangGraph, Pydantic AI, Browser Use, Playwright and more, and can run as managed Laminar Cloud or fully self-hosted via Docker Compose or Kubernetes/Helm.

**Areas:** Observability · LLM · AI Agents · Tracing · OpenTelemetry · Evaluation · Monitoring · Developer Tools · Open Source

## Laminar on APIs.io

Everything profiled for Laminar is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/laminar/](https://apis.io/providers/laminar/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Laminar SQL Query API](https://apis.io/apis/laminar/laminar-sql-query-api/) — Run SELECT-only ClickHouse SQL over a project's observability data via POST /v1/sql/query. Authenticates with a project API key as a bearer token, accepts a…
- [Laminar OpenTelemetry Trace Ingest API](https://apis.io/apis/laminar/laminar-otlp-trace-ingest-api/) — The standard OpenTelemetry trace ingest endpoint at /v1/traces. Laminar accepts OTLP over gRPC, HTTP+protobuf, and (since May 2026) HTTP+JSON, so any…
- [Laminar Evaluations API](https://apis.io/apis/laminar/laminar-evaluations-api/) — The lower-level LaminarClient.evals surface for wiring evaluations into an existing pipeline: create an evaluation, pre-register each datapoint so a row is…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [laminar](https://apis.io/servers/laminar/laminar/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Laminar Authentication](https://apis.io/security/laminar/laminar-authentication/)
- [Laminar Domain Security](https://apis.io/security/laminar/laminar-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Laminar Plans](https://apis.io/plans/laminar/laminar-plans/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://laminar.sh/)
- [Documentation](https://laminar.sh/docs)
- [Getting started](https://laminar.sh/docs/getting-started)
- [API reference](https://laminar.sh/docs/sdk/client)
- [Pricing](https://laminar.sh/pricing)
- [Sign up](https://laminar.sh/sign-in)
- [Support](https://discord.gg/nNFUUDAKub)
- [Blog](https://laminar.sh/blog)
- [Terms of service](https://laminar.sh/policies/terms)
- [Privacy policy](https://laminar.sh/policies/privacy)
- [GitHub](https://github.com/lmnr-ai)
- [Status](https://status.laminar.sh)

## API Evangelist rating

**Kin Score 46.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 26.3 |
| Developer ergonomics | 78.6 |
| Access clarity | 76.3 |

**Agent readiness 14.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 22.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/laminar/](https://apis.io/providers/laminar/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Laminar: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/laminar/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
