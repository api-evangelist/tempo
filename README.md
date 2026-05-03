# Tempo

Tempo is an open source, high-scale distributed tracing backend from Grafana Labs. Designed for cost-efficient, object storage-backed trace storage with minimal operational overhead. Integrates with popular open telemetry standards including OpenTelemetry, Jaeger, Zipkin, and W3C Trace Context.

**Website:** [https://grafana.com/oss/tempo/](https://grafana.com/oss/tempo/)
**Documentation:** [https://grafana.com/docs/tempo/latest/](https://grafana.com/docs/tempo/latest/)
**GitHub:** [https://github.com/grafana/tempo](https://github.com/grafana/tempo)

**Tags:** Distributed Tracing, Observability, OpenTelemetry, Grafana, Monitoring

**Modified:** 2026-05-03

---

## APIs

### Tempo HTTP API

Tempo exposes an HTTP API for querying traces, searching spans, discovering tag keys and values, and generating metrics from trace data. Compatible with Jaeger and Zipkin query protocols.

**Human URL:** [https://grafana.com/docs/tempo/latest/api_docs/](https://grafana.com/docs/tempo/latest/api_docs/)

**Tags:** Distributed Tracing, Observability, Trace Querying, OpenTelemetry

| Property | URL |
|---|---|
| Documentation | https://grafana.com/docs/tempo/latest/api_docs/ |
| GitHub Repository | https://github.com/grafana/tempo |
| OpenAPI (local) | openapi/tempo-openapi.yml |

---

### Tempo TraceQL API

TraceQL is a query language for Grafana Tempo that allows filtering and selecting spans within traces using a pipeline syntax with attribute matchers, duration filters, and structural operators.

**Human URL:** [https://grafana.com/docs/tempo/latest/traceql/](https://grafana.com/docs/tempo/latest/traceql/)

**Tags:** Distributed Tracing, Query Language, TraceQL, Observability

| Property | URL |
|---|---|
| Documentation | https://grafana.com/docs/tempo/latest/traceql/ |
| Query Editor Reference | https://grafana.com/docs/tempo/latest/traceql/query-editor/ |

---

## Common Properties

| Property | URL |
|---|---|
| Website | https://grafana.com/oss/tempo/ |
| Documentation | https://grafana.com/docs/tempo/latest/ |
| GitHub Repository | https://github.com/grafana/tempo |
| GitHub Organization | https://github.com/grafana |
| Helm Chart | https://grafana.github.io/helm-charts |
| Docker Hub | https://hub.docker.com/r/grafana/tempo |
| Release Notes | https://github.com/grafana/tempo/releases |
| Community | https://community.grafana.com/c/grafana-tempo/ |
| Blog | https://grafana.com/blog/tag/traces/ |
| Getting Started | https://grafana.com/docs/tempo/latest/getting-started/ |

---

## Artifacts

### OpenAPI Specifications

| API | File |
|---|---|
| Tempo HTTP API | [openapi/tempo-openapi.yml](openapi/tempo-openapi.yml) |

### JSON Schema

| Schema | File |
|---|---|
| Trace | [json-schema/tempo-trace-schema.json](json-schema/tempo-trace-schema.json) |

### JSON Structure

| Structure | File |
|---|---|
| Trace | [json-structure/tempo-trace-structure.json](json-structure/tempo-trace-structure.json) |

### JSON-LD

| Context | File |
|---|---|
| Tempo Context | [json-ld/tempo-context.jsonld](json-ld/tempo-context.jsonld) |

### Examples

| Example | File |
|---|---|
| Get Trace | [examples/tempo-get-trace-example.json](examples/tempo-get-trace-example.json) |
| Search Traces (TraceQL) | [examples/tempo-search-traceql-example.json](examples/tempo-search-traceql-example.json) |

### Spectral Rules

| Ruleset | File |
|---|---|
| Tempo API Rules | [rules/tempo-rules.yml](rules/tempo-rules.yml) |

### Naftiko Capabilities

**Shared Definitions:**

| API | File |
|---|---|
| Tempo | [capabilities/shared/tempo.yaml](capabilities/shared/tempo.yaml) |

**Workflow Capabilities:**

| Workflow | Description | File |
|---|---|---|
| Distributed Tracing | Trace retrieval, TraceQL search, tag discovery, and metrics | [capabilities/distributed-tracing.yaml](capabilities/distributed-tracing.yaml) |

### Vocabulary

| Vocabulary | File |
|---|---|
| Tempo Domain Vocabulary | [vocabulary/tempo-vocabulary.yml](vocabulary/tempo-vocabulary.yml) |

---

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
