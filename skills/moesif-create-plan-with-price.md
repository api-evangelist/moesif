---
name: moesif-create-plan-with-price
description: Create a new Moesif Plan and add a Price to it.
api: openapi/moesif-product-catalog-api-openapi.yml
operations:
- createMoesifPlan
- createMoesifPrice
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/moesif-product-catalog-api-openapi.yml ; every operationId checked against the contract
---

# moesif-create-plan-with-price

Create a new Moesif Plan and add a Price to it.

## Steps

1. 1. Call `createMoesifPlan` with the required plan fields in the request body.
2. 2. Call `createMoesifPrice` with the price fields in the request body, including the `plan_id` returned from the previous step.

## Rules

- Auth: Include a `Authorization: Bearer <managementAPIToken>` header for all requests.
- Idempotency: Not applicable; the API does not define an idempotency key.
