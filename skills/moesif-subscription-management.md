---
name: moesif-subscription-management
description: Create a new subscription (or update an existing one) and then retrieve its details.
api: openapi/moesif-subscriptions-api-openapi.yml
operations:
- createSubscription
- getSubscription
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/moesif-subscriptions-api-openapi.yml ; every operationId checked against the contract
---

# moesif-subscription-management

Create a new subscription (or update an existing one) and then retrieve its details.

## Steps

1. 1. Use `createSubscription` with the request body fields defined in the contract to create or update a subscription.
2. 2. Use `getSubscription` with the `id` path parameter returned from the previous step to fetch the subscription details.

## Rules

- Auth: Include the `Authorization: Bearer <managementAPIToken>` header for all requests.
- Idempotency: The `createSubscription` operation is idempotent when the same subscription identifier is provided.
