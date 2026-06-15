# Tempo (tempo)

Tempo is an open source, high-scale distributed tracing backend from Grafana Labs. Designed for cost-efficient, object storage-backed trace storage with minimal operational overhead. Integrates with popular open telemetry standards including OpenTelemetry, Jaeger, Zipkin, and W3C Trace Context. Provides HTTP query APIs for trace retrieval, search, tag discovery, and metrics generation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tempo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tempo/refs/heads/main/apis.yml)

## Tags

- Distributed Tracing
- Observability
- OpenTelemetry
- Grafana
- Monitoring

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-19

## APIs

### Tempo HTTP API

Tempo exposes an HTTP API for querying traces, searching spans, discovering tag keys and values, and generating metrics from trace data. The API is compatible with Jaeger and Zipkin query protocols in addition to the native Tempo protocol. Used by Grafana dashboards, the Tempo CLI, and external integrations.

- **Human URL:** [https://grafana.com/docs/tempo/latest/api_docs/](https://grafana.com/docs/tempo/latest/api_docs/)
- **Base URL:** `http://localhost:3200`

#### Tags

- Distributed Tracing
- Observability
- Trace Querying
- OpenTelemetry

#### Properties

- [Documentation](https://grafana.com/docs/tempo/latest/api_docs/)
- [GitHub Repository](https://github.com/grafana/tempo)
- [OpenAPI](openapi/tempo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tempo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tempo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tempo TraceQL API

TraceQL is a query language developed for Grafana Tempo that allows filtering and selecting spans within traces. The TraceQL search API endpoint enables rich span-level filtering using a pipeline syntax with attribute matchers, duration filters, and structural operators.

- **Human URL:** [https://grafana.com/docs/tempo/latest/traceql/](https://grafana.com/docs/tempo/latest/traceql/)
- **Base URL:** `http://localhost:3200`

#### Tags

- Distributed Tracing
- Query Language
- TraceQL
- Observability

#### Properties

- [Documentation](https://grafana.com/docs/tempo/latest/traceql/)
- [Reference](https://grafana.com/docs/tempo/latest/traceql/query-editor/)
- [Postman Collection](collections/tempo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tempo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tempohq)
- [Website](https://grafana.com/oss/tempo/)
- [Documentation](https://grafana.com/docs/tempo/latest/)
- [GitHub Repository](https://github.com/grafana/tempo)
- [GitHub Organization](https://github.com/grafana)
- [Helm  Chart](https://grafana.github.io/helm-charts)
- [Docker  Hub](https://hub.docker.com/r/grafana/tempo)
- [Release Notes](https://github.com/grafana/tempo/releases)
- [Community](https://community.grafana.com/c/grafana-tempo/)
- [Slack](https://grafana.slack.com/archives/C01BULREPHA)
- [Blog](https://grafana.com/blog/tag/traces/)
- [Getting Started](https://grafana.com/docs/tempo/latest/getting-started/)
- [OpenAPI](openapi/tempo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON-LD](json-ld/tempo-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/tempo-trace-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/tempo-trace-structure.json)
- [Spectral Rules](rules/tempo-rules.yml)
- [Vocabulary](vocabulary/tempo-vocabulary.yml)
- [Integrations](https://grafana.com/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
