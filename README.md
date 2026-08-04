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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
