# Envoy (envoy)

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

**APIs.json:** [https://www.envoyproxy.io/](https://www.envoyproxy.io/)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud Native
- Load Balancing
- Proxy
- Service Mesh

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Envoy Admin API

The Envoy Admin API provides local administrative access to a running Envoy proxy instance, exposing endpoints for inspecting clusters, listeners, configuration, statistics, health status, and runtime settings.

- **Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/operations/admin](https://www.envoyproxy.io/docs/envoy/latest/operations/admin)

#### Tags

- Admin
- Management
- Observability

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/operations/admin)
- [OpenAPI](openapi/envoy-admin-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/envoy-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/envoy-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Envoy xDS APIs

The xDS (x Discovery Service) APIs provide dynamic configuration for Envoy proxies via a management server, including LDS, RDS, CDS, EDS, SDS, and ADS. xDS APIs are served over gRPC or REST and allow management servers to push Listener, Route, Cluster, Endpoint, and Secret configurations to Envoy proxies at runtime without restarts.

- **Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol](https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol)

#### Tags

- Discovery Service
- Dynamic Configuration
- gRPC
- xDS

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol)
- [Reference](https://www.envoyproxy.io/docs/envoy/latest/configuration/overview/xds_api)
- [GitHub Repository](https://github.com/envoyproxy/envoy)
- [Postman Collection](collections/envoy-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/envoy-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/envoy-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/envoy-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Envoy API V3

The Envoy API v3 is the current stable protobuf-based configuration and extension API for Envoy proxy. It defines the configuration types for all Envoy subsystems including listeners, clusters, routes, endpoints, HTTP filters, network filters, transport sockets, and access logging. The API is defined using Protocol Buffers and published in the envoy-api repository.

- **Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/api/api](https://www.envoyproxy.io/docs/envoy/latest/api/api)

#### Tags

- Configuration
- Extensions
- Filters
- Protobuf

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/api/api)
- [GitHub Repository](https://github.com/envoyproxy/envoy)
- [JSON Schema](json-schema/envoy-cluster.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/envoy-listener.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/envoy-route-configuration.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/envoy-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/envoy-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/envoy-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/envoy-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Envoy Gateway API

Envoy Gateway manages Envoy Proxy as a standalone or Kubernetes-based application gateway, implementing and extending the Kubernetes Gateway API. It provides Gateway API extensions including BackendTrafficPolicy, ClientTrafficPolicy, SecurityPolicy, and EnvoyPatchPolicy for advanced traffic management without requiring direct Envoy configuration knowledge.

- **Human URL:** [https://gateway.envoyproxy.io/](https://gateway.envoyproxy.io/)

#### Tags

- Cloud Native
- Gateway
- Kubernetes
- Traffic Management

#### Properties

- [Documentation](https://gateway.envoyproxy.io/docs/)
- [Reference](https://gateway.envoyproxy.io/docs/concepts/gateway-api/)
- [Getting Started](https://gateway.envoyproxy.io/docs/)
- [GitHub Repository](https://github.com/envoyproxy/gateway)
- [Postman Collection](collections/envoy-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/envoy-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/envoy-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/envoy-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Envoy AI Gateway API

The Envoy AI Gateway manages unified access to Generative AI services built on Envoy Gateway. It provides OpenAI-compatible and Anthropic-compatible API endpoints for routing LLM traffic across multiple AI backends with backend rate limiting, policy control, and security configuration via Kubernetes custom resources.

- **Human URL:** [https://aigateway.envoyproxy.io/](https://aigateway.envoyproxy.io/)

#### Tags

- AI
- Cloud Native
- Gateway
- LLM

#### Properties

- [Documentation](https://aigateway.envoyproxy.io/docs/)
- [Reference](https://aigateway.envoyproxy.io/docs/api/)
- [Getting Started](https://aigateway.envoyproxy.io/docs/getting-started/basic-usage/)
- [GitHub Repository](https://github.com/envoyproxy/ai-gateway)
- [Changelog](https://aigateway.envoyproxy.io/release-notes/)
- [OpenAPI](openapi/envoy-ai-gateway-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/envoy-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/envoy-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/envoy-inc)
- [Website](https://www.envoyproxy.io/)
- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/)
- [Getting Started](https://www.envoyproxy.io/docs/envoy/latest/start/start)
- [Blog](https://blog.envoyproxy.io/)
- [Changelog](https://github.com/envoyproxy/envoy/releases)
- [GitHub Organization](https://github.com/envoyproxy)
- [GitHub Repository](https://github.com/envoyproxy/envoy)
- [Community](https://www.envoyproxy.io/community)
- [JSON Schema](json-schema/envoy-bootstrap.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/envoy-cluster.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/envoy-listener.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/envoy-route-configuration.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/envoy-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
