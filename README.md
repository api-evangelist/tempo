# Tempo (tempo)

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
