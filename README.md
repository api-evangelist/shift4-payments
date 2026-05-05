# Shift4 Payments (shift4-payments)

Shift4 Payments is a leading integrated payments and commerce technology provider and a Fortune 1000 company. The company processes payments for hospitality, retail, gaming, sports, e-commerce, and other verticals, offering checkout flows, custom payment forms, hosted UI components, and a developer API that supports global payment methods, subscriptions, fraud prevention, and 3D Secure. Developers integrate Shift4 through a REST API, JavaScript library, webhooks, and a sandbox testing environment.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/shift4-payments/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Payments, Fintech, Commerce, Checkout

## Timestamps

- **Created:** 2026-05-04
- **Modified:** 2026-05-05

## APIs

### Shift4 Payments API
The Shift4 Payments API enables merchants and platforms to accept and manage payments, including one-time charges, subscriptions, refunds, and regional payment methods, with support for fraud tools and 3D Secure.

**Human URL:** [https://dev.shift4.com/docs/api](https://dev.shift4.com/docs/api)

**Base URL:** `https://api.shift4.com`

#### Tags:

 - Payments, Charges, Refunds, Customers, Cards, Tokens, Subscriptions, Plans, Checkout, Disputes, Fraud, Webhooks, Events

#### Properties

- [Documentation](https://dev.shift4.com/docs)
- [API Reference](https://dev.shift4.com/docs/api)
- [Sandbox](https://dev.shift4.com/docs)
- [OpenAPI](openapi/shift4-api-openapi.yml)
- [Java SDK](https://github.com/shift4developer/shift4-java)
- [Node.js SDK](https://github.com/shift4developer/shift4-node)
- [Python SDK](https://github.com/shift4developer/shift4-python)
- [Ruby SDK](https://github.com/shift4developer/shift4-ruby)
- [PHP SDK](https://github.com/shift4developer/shift4-php)
- [.NET SDK](https://github.com/shift4developer/shift4-net)
- [iOS SDK](https://github.com/shift4developer/shift4-ios)
- [Android SDK](https://github.com/shift4developer/shift4-android)

### Shift4 Checkout
Shift4 Checkout provides a drop-in, frictionless checkout overlay that can be added to a website with copy-paste integration for fast and secure payment acceptance.

**Human URL:** [https://dev.shift4.com/docs/checkout](https://dev.shift4.com/docs/checkout)

#### Tags:

 - Checkout, Hosted Payments

#### Properties

- [Documentation](https://dev.shift4.com/docs/checkout)

### Shift4 JavaScript Library
The Shift4 JavaScript library provides secure, customizable HTML/CSS components for building on-page payment forms and multi-step checkout pages.

**Human URL:** [https://dev.shift4.com/docs/js](https://dev.shift4.com/docs/js)

#### Tags:

 - JavaScript, SDK, Components

#### Properties

- [Documentation](https://dev.shift4.com/docs/js)
- [SDK](https://dev.shift4.com/docs/js)
- [Code Examples](https://dev.shift4.com/examples)

## Common Properties

- [Website](https://www.shift4.com)
- [Developer Portal](https://dev.shift4.com)
- [Documentation](https://dev.shift4.com/docs)
- [API Reference](https://dev.shift4.com/docs/api)
- [Code Examples](https://dev.shift4.com/examples)
- [Support](https://dev.shift4.com/support)
- [GitHub Organization](https://github.com/shift4developer)
- [WooCommerce Plugin](https://github.com/shift4developer/shift4-woocommerce)
- [Salesforce B2C Commerce Cartridge](https://github.com/shift4developer/shift4-salesforce-b2c)
- [Vocabulary](vocabulary/shift4-payments-vocabulary.yml)
- [Spectral Rules](rules/shift4-api-rules.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Shift4 Payments API](openapi/shift4-api-openapi.yml)

### JSON Schema

- [Shift4 Charge](json-schema/shift4-charge-schema.json)
- [Shift4 Customer](json-schema/shift4-customer-schema.json)
- [Shift4 Card](json-schema/shift4-card-schema.json)
- [Shift4 Token](json-schema/shift4-token-schema.json)
- [Shift4 Subscription](json-schema/shift4-subscription-schema.json)
- [Shift4 Plan](json-schema/shift4-plan-schema.json)
- [Shift4 Refund](json-schema/shift4-refund-schema.json)
- [Shift4 Event](json-schema/shift4-event-schema.json)
- [Shift4 Checkout Session](json-schema/shift4-checkout-session-schema.json)

### JSON Structure

- [Shift4 Charge Structure](json-structure/shift4-charge-structure.json)
- [Shift4 Customer Structure](json-structure/shift4-customer-structure.json)
- [Shift4 Subscription Structure](json-structure/shift4-subscription-structure.json)

### JSON-LD

- [Shift4 Payments Context](json-ld/shift4-payments-context.jsonld)

## Examples

- [Create Charge](examples/shift4-api-create-charge-example.json)
- [Create Customer](examples/shift4-api-create-customer-example.json)
- [Create Token](examples/shift4-api-create-token-example.json)
- [Create Refund](examples/shift4-api-create-refund-example.json)
- [Create Subscription](examples/shift4-api-create-subscription-example.json)
- [Create Checkout Session](examples/shift4-api-create-checkout-session-example.json)
- [List Events](examples/shift4-api-list-events-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Charges](capabilities/shared/charges.yaml) — 6 operations for charge create/get/update/capture and listing
- [Refunds](capabilities/shared/refunds.yaml) — 3 operations for issuing and reading refunds
- [Customers](capabilities/shared/customers.yaml) — 5 operations for customer CRUD
- [Subscriptions and Plans](capabilities/shared/subscriptions.yaml) — 7 operations spanning plans and subscriptions
- [Checkout and Payment Links](capabilities/shared/checkout.yaml) — 4 operations for hosted checkout and links
- [Disputes and Fraud Warnings](capabilities/shared/disputes.yaml) — 3 operations for chargeback and fraud workflows
- [Webhooks and Events](capabilities/shared/webhooks-events.yaml) — 6 operations for events and webhook endpoint management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|---------------|-------|---------|
| [Payment Processing](capabilities/payment-processing.yaml) | Charges, Refunds, Checkout, Disputes | 5 | E-commerce platforms, SaaS billing teams, payment ops engineers |
| [Subscription Billing](capabilities/subscription-billing.yaml) | Customers, Plans, Subscriptions | 5 | SaaS and membership billing teams |
| [Fraud and Disputes](capabilities/fraud-and-disputes.yaml) | Disputes, Fraud Warnings | 3 | Risk and operations teams |

## Vocabulary

- [Shift4 Payments Vocabulary](vocabulary/shift4-payments-vocabulary.yml) — Domain vocabulary covering 22 core terms, lifecycle statuses for charges/refunds/subscriptions/payment methods/checkout sessions/disputes, and the Shift4 event taxonomy

## Rules

- [Shift4 API Rules](rules/shift4-api-rules.yml) — 15 Spectral rules enforcing Shift4 API conventions (operationId, tags, summaries, BasicAuth scheme, server URL, list-response shape, amount/currency/created field types)

## Maintainers

**FN:** API Evangelist

**URL:** https://apievangelist.com
