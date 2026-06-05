# Envoy (envoy)

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
