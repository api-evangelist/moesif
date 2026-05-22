# Moesif (moesif)

Moesif is an API analytics, monitoring, monetization, and governance platform for API and AI product teams. The platform unifies API observability (analytics, logs, metrics, traces via OpenTelemetry), usage-based monetization (billing meters, product catalog, prepaid credits, Stripe integration), quotas and governance (rate limiting, contract enforcement), and customer-experience tooling (behavioral cohorts, emails, embedded metrics, developer portal). Moesif has expanded into AI agent and LLM analytics with usage-based billing for AI apps, GenAI-powered "Ask AI" analytics queries, and content monetization for LLM training.

**URL:** [APIs.json Index](https://raw.githubusercontent.com/api-evangelist/moesif/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Analytics, Monitoring, Monetization, Governance, Observability, Billing, AI Agents, LLM Analytics, OpenTelemetry, Developer Portal, Platform, Insights

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-22

## APIs

### Moesif Management API

The Moesif Management API exposes the platform's full control plane for analytics, monetization, and governance. Capabilities include querying events, users, and companies; managing applications, workspaces, and dashboards; defining billing meters, product catalog entries, subscriptions, and balance transactions; configuring governance rules and quotas; managing cohorts, email templates, and metrics; and chat-style "Ask Question" analytics queries powered by GenAI.

- **Human URL:** https://www.moesif.com/
- **Base URL:** https://api.moesif.com

**Tags:** Analytics, Monetization, Monitoring, Observability, Governance, Billing, AI Agents

**Properties:**

- [Documentation](https://www.moesif.com/docs/api)
- [OpenAPI](openapi/moesif-openapi.yml)
- [Spectral Ruleset](rules/moesif-rules.yml)
- [Plans & Pricing](plans/moesif-plans-pricing.yml)
- [Rate Limits](rate-limits/moesif-rate-limits.yml)
- [FinOps](finops/moesif-finops.yml)

**Naftiko Capabilities:**

- [Applications](capabilities/moesif-applications.yaml)
- [Balance Transactions](capabilities/moesif-balance-transactions.yaml)
- [Billing Meters](capabilities/moesif-billing-meters.yaml)
- [Billing Reports](capabilities/moesif-billing-reports.yaml)
- [Cohorts](capabilities/moesif-cohorts.yaml)
- [Companies](capabilities/moesif-companies.yaml)
- [Dashboards](capabilities/moesif-dashboards.yaml)
- [Email Templates](capabilities/moesif-email-templates.yaml)
- [Governance Rules](capabilities/moesif-governance-rules.yaml)
- [Metrics](capabilities/moesif-metrics.yaml)
- [Product Catalog](capabilities/moesif-product-catalog.yaml)
- [Properties](capabilities/moesif-properties.yaml)
- [Subscriptions](capabilities/moesif-subscriptions.yaml)
- [Users](capabilities/moesif-users.yaml)
- [Workspaces](capabilities/moesif-workspaces.yaml)

### Moesif Collector API

High-volume ingestion endpoint that receives API event data from server, client, and gateway SDKs. Accepts HTTP API call records, user/company entity updates, and custom action events that feed Moesif's analytics, monetization, and governance pipelines.

- **Human URL:** https://www.moesif.com/docs/
- **Base URL:** https://api.moesif.net

**Tags:** Ingestion, Events, Telemetry, OpenTelemetry

## Common Properties

- [Website](https://www.moesif.com/)
- [Documentation](https://www.moesif.com/docs/)
- [API Reference](https://www.moesif.com/docs/api)
- [Pricing](https://www.moesif.com/pricing)
- [Sign Up](https://www.moesif.com/wrap)
- [Blog](https://www.moesif.com/blog)
- [GitHub Organization](https://github.com/moesif)
- [LinkedIn](https://www.linkedin.com/company/moesif)
- [Twitter](https://twitter.com/moesif)
- [SDK Catalog](https://www.moesif.com/docs/server-integration/)

### Server SDKs

Node.js, Python (Django / WSGI / Tornado / Requests), Java Servlet, .NET, Go, PHP (Laravel / Slim), Ruby Rack, Scala Play, AWS Lambda (Node.js / Python / Go).

### Client SDKs

Browser JavaScript, Android.

### Gateway / Proxy Plugins

Cloudflare Workers, Kong Gateway, NGINX / OpenResty (lua-resty), Express Gateway, Tyk, 3scale, Envoy.

### Reference Samples

[Developer Portal Reference Implementation](https://github.com/Moesif/moesif-developer-portal) plus framework examples (Express, Flask, Rails, ASP.NET, Apollo GraphQL, Web3/Ethereum DApps).

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
