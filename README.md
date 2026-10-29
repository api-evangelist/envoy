# Envoy

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

Envoy is a high-performance, open-source edge and service proxy designed for cloud-native applications and microservice architectures. It provides advanced load balancing, observability, and traffic management features, and serves as the data plane for many service mesh implementations including Istio.

**Areas:** Envoy · Cloud-Native · Load Balancing · Proxy · Service Mesh

## Envoy on APIs.io

Everything profiled for Envoy is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/envoy/](https://apis.io/providers/envoy/)** — or go straight to one of the APIs or properties below.

### APIs (15)

- [Envoy xDS APIs](https://apis.io/apis/envoy/envoy-xds-api/) — The xDS (x Discovery Service) APIs provide dynamic configuration for Envoy proxies via a management server, including LDS, RDS, CDS, EDS, SDS, and ADS. xDS…
- [Envoy API V3](https://apis.io/apis/envoy/envoy-api-v3/) — The Envoy API v3 is the current stable protobuf-based configuration and extension API for Envoy proxy. It defines the configuration types for all Envoy…
- [Envoy Gateway API](https://apis.io/apis/envoy/envoy-gateway-api/) — Envoy Gateway manages Envoy Proxy as a standalone or Kubernetes-based application gateway, implementing and extending the Kubernetes Gateway API. It…
- [Envoy Certificates API](https://apis.io/apis/envoy/envoy-certificates-api/) — TLS certificate inspection endpoints
- [Envoy Clusters API](https://apis.io/apis/envoy/envoy-clusters-api/) — Upstream cluster inspection and status endpoints
- [Envoy Configuration API](https://apis.io/apis/envoy/envoy-configuration-api/) — Configuration dump and inspection endpoints
- [Envoy Health API](https://apis.io/apis/envoy/envoy-health-api/) — Health check management endpoints
- [Envoy Listeners API](https://apis.io/apis/envoy/envoy-listeners-api/) — Listener inspection and drain endpoints
- [Envoy Logging API](https://apis.io/apis/envoy/envoy-logging-api/) — Log level management endpoints
- [Envoy Models API](https://apis.io/apis/envoy/envoy-models-api/) — Model listing endpoints for discovering available AI models configured in the gateway routes.
- [Envoy Runtime API](https://apis.io/apis/envoy/envoy-runtime-api/) — Runtime settings management endpoints
- [Envoy Server API](https://apis.io/apis/envoy/envoy-server-api/) — Server management, lifecycle, and information endpoints
- [Envoy Statistics API](https://apis.io/apis/envoy/envoy-statistics-api/) — Statistics, metrics, and Prometheus endpoints
- [Envoy Text Completions API](https://apis.io/apis/envoy/envoy-text-completions-api/) — Legacy text completions endpoints compatible with the OpenAI completions API.
- [Envoy Chat Completions API](https://apis.io/apis/envoy/envoy-chat-completions-api/) — Chat completions endpoints compatible with the OpenAI Chat API. Routes requests to configured AI backends based on AIGatewayRoute rules.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Envoy Agentic Access](https://apis.io/agentic-access/envoy/envoy-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Envoy Bootstrap Configuration](https://apis.io/schemas/envoy/envoy-bootstrap/)
- [Envoy Cluster](https://apis.io/schemas/envoy/envoy-cluster/)
- [Envoy Listener](https://apis.io/schemas/envoy/envoy-listener/)
- [Envoy Route Configuration](https://apis.io/schemas/envoy/envoy-route-configuration/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Envoy Context](https://apis.io/jsonld/envoy/envoy-context/)

#### Collections (14)

Postman and Open Collection request collections.

- [Envoy Admin API](https://apis.io/collections/envoy/open-envoy-admin-api/)
- [Envoy AI Gateway API](https://apis.io/collections/envoy/open-envoy-ai-gateway/)
- [Envoy Admin Certificates API](https://apis.io/collections/envoy/open-envoy-certificates-api/)
- [Envoy Admin Certificates Chat API](https://apis.io/collections/envoy/open-envoy-chat-api/)
- [Envoy Admin Certificates Clusters API](https://apis.io/collections/envoy/open-envoy-clusters-api/)
- [Envoy Admin Certificates Configuration API](https://apis.io/collections/envoy/open-envoy-configuration-api/)
- [Envoy Admin Certificates Health API](https://apis.io/collections/envoy/open-envoy-health-api/)
- [Envoy Admin Certificates Listeners API](https://apis.io/collections/envoy/open-envoy-listeners-api/)
- [Envoy Admin Certificates Logging API](https://apis.io/collections/envoy/open-envoy-logging-api/)
- [Envoy Admin Certificates Models API](https://apis.io/collections/envoy/open-envoy-models-api/)
- [Envoy Admin Certificates Runtime API](https://apis.io/collections/envoy/open-envoy-runtime-api/)
- [Envoy Admin Certificates Server API](https://apis.io/collections/envoy/open-envoy-server-api/)
- [Envoy Admin Certificates Statistics API](https://apis.io/collections/envoy/open-envoy-statistics-api/)
- [Envoy Admin Certificates Text Completions API](https://apis.io/collections/envoy/open-envoy-text-completions-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Envoy — jsonschema rules](https://apis.io/rules/envoy/envoy-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Envoy Authentication](https://apis.io/security/envoy/envoy-authentication/)
- [Envoy Domain Security](https://apis.io/security/envoy/envoy-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Envoy Plans Pricing](https://apis.io/plans/envoy/envoy-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Envoy Rate Limits](https://apis.io/rate-limits/envoy/envoy-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Envoy Finops](https://apis.io/finops/envoy/envoy-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.envoyproxy.io/)
- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/)
- [Getting started](https://www.envoyproxy.io/docs/envoy/latest/start/start)
- [Changelog](https://github.com/envoyproxy/envoy/releases)
- [Blog](https://blog.envoyproxy.io/)
- [GitHub](https://github.com/envoyproxy)

## API Evangelist rating

**Kin Score 42.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 55.9 |
| Contract governance | 9.8 |
| Operational transparency | 36.8 |
| Developer ergonomics | 44.0 |
| Access clarity | 5.3 |

**Agent readiness 26.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/envoy/](https://apis.io/providers/envoy/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Envoy: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/envoy/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
