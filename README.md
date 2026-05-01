# Envoy (envoy)
Envoy is a high-performance, open-source edge and service proxy designed for cloud-native applications and microservice architectures. It provides advanced load balancing, observability, and traffic management features, and serves as the data plane for many service mesh implementations including Istio.

**URL:** [Visit APIs.json URL](https://www.envoyproxy.io/)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Proxy, Service Mesh, Load Balancing, Cloud Native

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-04-28 

## APIs

### Envoy Admin API
The Envoy Admin API provides local administrative access to a running Envoy proxy instance, exposing endpoints for inspecting clusters, listeners, configuration, statistics, health status, and runtime settings.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/operations/admin](https://www.envoyproxy.io/docs/envoy/latest/operations/admin)


#### Tags:

 - Admin, Management, Observability

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/operations/admin)
- [OpenAPI](openapi/envoy-admin-api-openapi.yml)

### Envoy xDS APIs
The xDS (x Discovery Service) APIs provide dynamic configuration for Envoy proxies via a management server, including LDS, RDS, CDS, EDS, SDS, and ADS. xDS APIs are served over gRPC or REST and allow management servers to push Listener, Route, Cluster, Endpoint, and Secret configurations to Envoy proxies at runtime without restarts.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol](https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol)


#### Tags:

 - xDS, Discovery Service, gRPC, Dynamic Configuration

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol)
- [Reference](https://www.envoyproxy.io/docs/envoy/latest/configuration/overview/xds_api)
- [GitHubRepository](https://github.com/envoyproxy/envoy)

### Envoy API v3
The Envoy API v3 is the current stable protobuf-based configuration and extension API for Envoy proxy. It defines the configuration types for all Envoy subsystems including listeners, clusters, routes, endpoints, HTTP filters, network filters, transport sockets, and access logging. The API is defined using Protocol Buffers and published in the envoy-api repository.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/api/api](https://www.envoyproxy.io/docs/envoy/latest/api/api)


#### Tags:

 - Protobuf, Configuration, Extensions, Filters

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/api/api)
- [GitHubRepository](https://github.com/envoyproxy/envoy)
- [JSONSchema](json-schema/envoy-cluster.json)
- [JSONSchema](json-schema/envoy-listener.json)
- [JSONSchema](json-schema/envoy-route-configuration.json)

### Envoy Gateway API
Envoy Gateway manages Envoy Proxy as a standalone or Kubernetes-based application gateway, implementing and extending the Kubernetes Gateway API. It provides Gateway API extensions including BackendTrafficPolicy, ClientTrafficPolicy, SecurityPolicy, and EnvoyPatchPolicy for advanced traffic management without requiring direct Envoy configuration knowledge.

**Human URL:** [https://gateway.envoyproxy.io/](https://gateway.envoyproxy.io/)


#### Tags:

 - Gateway, Kubernetes, Traffic Management, Cloud Native

#### Properties

- [Documentation](https://gateway.envoyproxy.io/docs/)
- [Reference](https://gateway.envoyproxy.io/docs/concepts/gateway-api/)
- [Getting Started](https://gateway.envoyproxy.io/docs/)
- [GitHubRepository](https://github.com/envoyproxy/gateway)

### Envoy AI Gateway API
The Envoy AI Gateway manages unified access to Generative AI services built on Envoy Gateway. It provides OpenAI-compatible and Anthropic-compatible API endpoints for routing LLM traffic across multiple AI backends with backend rate limiting, policy control, and security configuration via Kubernetes custom resources.

**Human URL:** [https://aigateway.envoyproxy.io/](https://aigateway.envoyproxy.io/)


#### Tags:

 - AI, LLM, Gateway, Cloud Native

#### Properties

- [Documentation](https://aigateway.envoyproxy.io/docs/)
- [Reference](https://aigateway.envoyproxy.io/docs/api/)
- [Getting Started](https://aigateway.envoyproxy.io/docs/getting-started/basic-usage/)
- [GitHubRepository](https://github.com/envoyproxy/ai-gateway)
- [Change Log](https://aigateway.envoyproxy.io/release-notes/)
- [OpenAPI](openapi/envoy-ai-gateway-openapi.yml)

## Common Properties

- [Website](https://www.envoyproxy.io/)
- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/)
- [Getting Started](https://www.envoyproxy.io/docs/envoy/latest/start/start)
- [Blog](https://blog.envoyproxy.io/)
- [Change Log](https://github.com/envoyproxy/envoy/releases)
- [GitHub Organization](https://github.com/envoyproxy)
- [GitHubRepository](https://github.com/envoyproxy/envoy)
- [Community](https://www.envoyproxy.io/community)
- [JSONSchema](json-schema/envoy-bootstrap.json)
- [JSONSchema](json-schema/envoy-cluster.json)
- [JSONSchema](json-schema/envoy-listener.json)
- [JSONSchema](json-schema/envoy-route-configuration.json)
- [JSON-LD](json-ld/envoy-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
