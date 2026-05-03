# Visa Acceptance

Visa Acceptance Solutions (powered by CyberSource) is the developer platform for accepting payments online, in-person, and via mobile. The platform provides REST APIs for the complete payment lifecycle including authorization, capture, refund, void, reversal, invoicing, and pay-by-link.

**Developer Portal:** https://developer.visaacceptance.com/  
**API Reference:** https://developer.visaacceptance.com/api-reference-assets/index.html  
**Sandbox:** https://developer.visaacceptance.com/hello-world/sandbox.html

## APIs

### Visa Acceptance Payments API

REST API for accepting and processing payments.

- **OpenAPI Spec:** [openapi/visa-acceptance-payments-openapi.yml](openapi/visa-acceptance-payments-openapi.yml)
- **Documentation:** https://developer.visaacceptance.com/docs.html
- **Getting Started:** https://developer.visaacceptance.com/docs/vas/en-us/platform/developer/all/rest/rest-getting-started/restgs-intro.html
- **Base URL (Test):** https://apitest.visaacceptance.com

## Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/visa-acceptance-payments.yaml](capabilities/shared/visa-acceptance-payments.yaml) | Per-API capability definition for the Payments API |

### Workflow Capabilities

| File | Description |
|------|-------------|
| [capabilities/payment-acceptance-workflow.yaml](capabilities/payment-acceptance-workflow.yaml) | Full payment lifecycle workflow (authorize, capture, refund, void, invoice, pay-by-link) |

## JSON Schemas

| File | Description |
|------|-------------|
| [json-schema/visa-acceptance-payment-schema.json](json-schema/visa-acceptance-payment-schema.json) | Schema for payment transactions |

## JSON Structure

| File | Description |
|------|-------------|
| [json-structure/visa-acceptance-payment-structure.json](json-structure/visa-acceptance-payment-structure.json) | Structure documentation for payment objects |

## JSON-LD Context

| File | Description |
|------|-------------|
| [json-ld/visa-acceptance-context.jsonld](json-ld/visa-acceptance-context.jsonld) | Linked data context mapping payment concepts to schema.org |

## Examples

| File | Description |
|------|-------------|
| [examples/visa-acceptance-authorize-payment-example.json](examples/visa-acceptance-authorize-payment-example.json) | Authorize a payment |
| [examples/visa-acceptance-capture-payment-example.json](examples/visa-acceptance-capture-payment-example.json) | Capture a payment |
| [examples/visa-acceptance-refund-payment-example.json](examples/visa-acceptance-refund-payment-example.json) | Refund a payment |
| [examples/visa-acceptance-create-invoice-example.json](examples/visa-acceptance-create-invoice-example.json) | Create an invoice |
| [examples/visa-acceptance-create-pay-by-link-example.json](examples/visa-acceptance-create-pay-by-link-example.json) | Generate a payment link |

## Rules

| File | Description |
|------|-------------|
| [rules/visa-acceptance-rules.yml](rules/visa-acceptance-rules.yml) | Spectral ruleset for Visa Acceptance API conventions |

## Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/visa-acceptance-vocabulary.yml](vocabulary/visa-acceptance-vocabulary.yml) | Domain vocabulary for payment processing concepts |

## Tags

Payments, E-Commerce, Fintech, Credit Cards, Invoicing, Payment Links, Digital Wallets

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
