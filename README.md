# Laminar

Laminar is an open-source, OpenTelemetry-native observability and debugging platform built for AI
agents and LLM applications. It traces every LLM call, tool call, and sub-agent a run produces,
renders each trace as a readable transcript rather than a raw span tree, and turns that data into
answers: a record-and-replay Debugger that serves everything before your change from cache, and
Signals that let you describe outcomes and failures in plain language and extract structured events
across all traces. The platform adds evaluations, datasets and labeling queues, a playground, full-text
search, custom dashboards, and read-only ClickHouse SQL over trace data from the UI, the `lmnr-cli`,
or a hosted MCP server. Runs as managed Laminar Cloud or fully self-hosted (Docker Compose or
Kubernetes/Helm).

- Website: https://laminar.sh/
- Docs: https://laminar.sh/docs
- Source: https://github.com/lmnr-ai/lmnr (Apache-2.0)
- Status: https://status.laminar.sh
- API base: `https://api.lmnr.ai` (`/v1/sql/query`, `/v1/traces`, `/v1/mcp`)

## Artifacts

| Artifact | Path | Method |
|---|---|---|
| Packages / SDKs | `packages/laminar-packages.yml` | searched |
| MCP server | `mcp/laminar-mcp.yml` | searched (published) |
| Agent Skill | `skills/laminar-laminar.md` + `skills/_index.yml` | searched (provider-published, verbatim) |
| llms.txt | `llms/laminar-llms.txt` | searched (verbatim) |
| Authentication | `authentication/laminar-authentication.yml` | searched |
| Conventions | `conventions/laminar-conventions.yml` | searched |
| Changelog | `changelog/laminar-changelog.yml` | searched |
| CLI | `cli/laminar-cli.yml` | searched |
| Lifecycle | `lifecycle/laminar-lifecycle.yml` | searched |
| Conformance | `conformance/laminar-conformance.yml` | searched |
| Plans | `plans/laminar-plans.yml` | searched |
| Well-Known | `well-known/laminar-well-known.yml` | searched (all 404 — verified absence) |
| Domain security | `security/laminar-domain-security.yml` | probed |

Laminar publishes **no OpenAPI**, so no `openapi/`, `overlays/`, `errors/`, `data-model/`,
`agentic-access/` or `arazzo/` artifacts were derived. No AsyncAPI or consumer webhook surface, no
`.well-known` documents, no vulnerability-disclosure program and no trust center / named
certifications were found — each recorded as a verified absence rather than fabricated.

> **Provenance caveat.** This repo originated as a VC-portfolio stub tagged "cybersecurity" and backed
> by insight-partners / techstars. That backing was **not** verified against this company during
> enrichment — the name "Laminar" collides across several companies. See `x-backed-by-note` in
> `apis.yml`.
