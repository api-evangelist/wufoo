# Wufoo (wufoo:wufoo)

Wufoo is an online form-builder owned by SurveyMonkey Inc. It lets non-developers
build registration forms, surveys, contact forms, application forms, and payment
forms through a drag-and-drop interface, then collect and report on submissions.
Wufoo exposes a v3 REST API (Basic Auth, JSON/XML) over Forms, Entries, Fields,
Users, Reports, Widgets, Comments, and Webhooks, plus push webhooks that POST
form data to subscriber URLs at submission time.

**APIs.json:** [https://github.com/api-evangelist/wufoo](https://github.com/api-evangelist/wufoo)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Forms
- Form Builder
- Surveys
- Data Collection
- Webhooks
- Payments
- SurveyMonkey

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Wufoo REST API v3

The Wufoo v3 REST API gives programmatic access to forms, form fields, entries,
reports, widgets, comments, users, and webhooks for a Wufoo account. Endpoints
are per-subdomain (https://{subdomain}.wufoo.com/api/v3/) and authenticate via
HTTP Basic Auth with the account API key as username. Responses are JSON or XML
depending on the .json/.xml extension on the request URL.

- **Human URL:** [https://wufoo.github.io/docs/](https://wufoo.github.io/docs/)
- **Base URL:** `https://{subdomain}.wufoo.com/api/v3`

#### Tags

- Forms
- Entries
- Fields
- Reports
- Widgets
- Comments
- Users
- Webhooks

#### Properties

- [Documentation](https://wufoo.github.io/docs/)
- [API Reference](https://wufoo.github.io/docs/)
- [OpenAPI](openapi/wufoo-rest-v3-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wufoo-rest-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wufoo-rest-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://wufoo.github.io/docs/#authentication)
- [Rate Limits](rate-limits/wufoo-rate-limits.yml)
- [Getting Started](https://help.surveymonkey.com/en/wufoo/integrations/wufoo-api/)
- [Spectral Rules](rules/wufoo-rest-v3-rules.yml)
- [JSON Schema](json-schema/wufoo-form-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wufoo-field-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wufoo-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wufoo-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wufoo-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/wufoo-form-structure.json)
- [JSON Structure](json-structure/wufoo-entry-structure.json)
- [Example](examples/wufoo-rest-v3-list-forms-example.json)
- [Example](examples/wufoo-rest-v3-list-form-fields-example.json)
- [Example](examples/wufoo-rest-v3-list-entries-example.json)
- [Example](examples/wufoo-rest-v3-submit-entry-example.json)
- [Example](examples/wufoo-rest-v3-put-webhook-example.json)

### Wufoo Webhooks

Wufoo webhooks POST form-submission payloads to a subscriber URL at the moment
an entry is created. Up to 10 webhooks per form, with optional handshake key
for verification and optional metadata for richer form/field structure.

- **Human URL:** [https://help.surveymonkey.com/en/wufoo/integrations/wufoo-api/](https://help.surveymonkey.com/en/wufoo/integrations/wufoo-api/)
- **Base URL:** `https://{subscriber}/`

#### Tags

- Webhooks
- Events
- Form Submissions

#### Properties

- [Documentation](https://help.surveymonkey.com/en/wufoo/integrations/wufoo-api/)
- [AsyncAPI](asyncapi/wufoo-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/wufoo-webhook-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/wufoo-webhooks-form-submission-example.json)
- [Postman Collection](collections/wufoo-rest-v3.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wufoo-rest-v3.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://www.wufoo.com)
- [Developer Portal](https://wufoo.github.io/docs/)
- [Documentation](https://wufoo.github.io/docs/)
- [API Reference](https://wufoo.github.io/docs/)
- [Getting Started](https://help.surveymonkey.com/en/wufoo/integrations/wufoo-api/)
- [Sign Up](https://www.wufoo.com/signup/)
- [Login](https://www.wufoo.com/login/)
- [Pricing](https://www.wufoo.com/pricing/)
- [Plans](plans/wufoo-plans-pricing.yml)
- [Rate Limits](rate-limits/wufoo-rate-limits.yml)
- [Features](https://www.wufoo.com/features/)
- [Integrations](https://www.wufoo.com/partners/)
- [Blog](https://www.wufoo.com/blog/)
- [R S S](https://www.wufoo.com/blog/feed/)
- [Support](https://help.surveymonkey.com/wufoo/)
- [Status Page](https://status.wufoo.com/)
- [Status R S S](https://status.wufoo.com/history.rss)
- [Status Atom](https://status.wufoo.com/history.atom)
- [Terms of Service](https://www.wufoo.com/terms-of-use/)
- [Privacy Policy](https://www.wufoo.com/privacy/)
- [GitHub Organization](https://github.com/wufoo)
- [Vocabulary](vocabulary/wufoo-vocabulary.yml)
- [JSON-LD](json-ld/wufoo-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Fin Ops](finops/wufoo-finops.yml)
- [SDK](https://github.com/wufoo/Wufoo-PHP-API-Wrapper)
- [SDK](https://github.com/wufoo/pyfoo)
- [SDK](https://github.com/wufoo/wuparty)
- [SDK](https://github.com/wufoo/j-woo)
- [SDK](https://github.com/wufoo/Wufoo-jQuery-API-Wrapper)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
