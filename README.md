# Moesif (moesif)

Moesif is an API analytics, monitoring, monetization, and governance platform for API and AI product teams. The platform unifies API observability (analytics, logs, metrics, traces via OpenTelemetry), usage-based monetization (billing meters, product catalog, prepaid credits, Stripe integration), quotas and governance (rate limiting, contract enforcement), and customer-experience tooling (behavioral cohorts, emails, embedded metrics, developer portal). Moesif has expanded into AI agent and LLM analytics with usage-based billing for AI apps, GenAI-powered "Ask AI" analytics queries, and content monetization for LLM training.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/moesif/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/moesif/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Analytics
- Monitoring
- Monetization
- Governance
- Observability
- Billing
- AI Agents
- LLM Analytics
- OpenTelemetry
- Developer Portal
- Platform
- Insights

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-22

## APIs

### Moesif Management API

The Moesif Management API exposes the platform's full control plane for analytics, monetization, and governance. Capabilities include querying events, users, and companies; managing applications, workspaces, and dashboards; defining billing meters, product catalog entries, subscriptions, and balance transactions; configuring governance rules and quotas; managing cohorts, email templates, and metrics; and chat-style "Ask Question" analytics queries powered by GenAI.

- **Human URL:** [https://www.moesif.com/](https://www.moesif.com/)
- **Base URL:** `https://api.moesif.com`

#### Tags

- Analytics
- Monetization
- Monitoring
- Observability
- Governance
- Billing
- AI Agents

#### Properties

- [Documentation](https://www.moesif.com/docs/api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/moesif/refs/heads/main/openapi/moesif-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](rules/moesif-rules.yml)
- [Plans](plans/moesif-plans-pricing.yml)
- [Rate Limits](rate-limits/moesif-rate-limits.yml)
- [Fin Ops](finops/moesif-finops.yml)
- [Postman Collection](collections/moesif.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moesif.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moesif Collector API

The Moesif Collector API is the high-volume ingestion endpoint that receives API event data from server, client, and gateway SDKs. It accepts HTTP API call records, user/company entity updates, and custom action events that feed Moesif's analytics, monetization, and governance pipelines.

- **Human URL:** [https://www.moesif.com/docs/](https://www.moesif.com/docs/)
- **Base URL:** `https://api.moesif.net`

#### Tags

- Ingestion
- Events
- Telemetry
- OpenTelemetry

#### Properties

- [Documentation](https://www.moesif.com/docs/api/)
- [SDK](https://www.moesif.com/docs/server-integration/)
- [Postman Collection](collections/moesif.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moesif.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/moesif)
- [LinkedIn](https://www.linkedin.com/company/moesif)
- [Twitter](https://twitter.com/moesif)
- [Website](https://www.moesif.com/)
- [Documentation](https://www.moesif.com/docs/)
- [API Reference](https://www.moesif.com/docs/api)
- [Pricing](https://www.moesif.com/pricing)
- [Sign Up](https://www.moesif.com/wrap)
- [Blog](https://www.moesif.com/blog)
- [SDK](https://www.moesif.com/docs/server-integration/)
- [Integrations](https://www.moesif.com/integrations)
- [SDK](https://github.com/Moesif/moesif-nodejs)
- [SDK](https://github.com/Moesif/moesifdjango)
- [SDK](https://github.com/Moesif/moesifwsgi)
- [SDK](https://github.com/Moesif/moesiftornado)
- [SDK](https://github.com/Moesif/moesifpythonrequest)
- [SDK](https://github.com/Moesif/moesif-servlet)
- [SDK](https://github.com/Moesif/moesif-dotnet)
- [SDK](https://github.com/Moesif/moesifmiddleware-go)
- [SDK](https://github.com/Moesif/moesif-laravel)
- [SDK](https://github.com/Moesif/moesif-slim)
- [SDK](https://github.com/Moesif/moesif-rack)
- [SDK](https://github.com/Moesif/moesif-play-filter)
- [SDK](https://github.com/Moesif/moesif-android)
- [SDK](https://github.com/Moesif/moesif-browser-js)
- [SDK](https://github.com/Moesif/moesif-aws-lambda-nodejs)
- [SDK](https://github.com/Moesif/moesif-aws-lambda-python)
- [SDK](https://github.com/Moesif/moesif-aws-lambda-go)
- [Plugin](https://github.com/Moesif/moesif-cloudflare)
- [Plugin](https://github.com/Moesif/kong-plugin-moesif)
- [Plugin](https://github.com/Moesif/lua-resty-moesif)
- [Plugin](https://github.com/Moesif/express-gateway-plugin-moesif)
- [Tool](https://github.com/Moesif/auth0-logs-to-moesif)
- [Sample](https://github.com/Moesif/moesif-developer-portal)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
