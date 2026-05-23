# Wufoo

Wufoo is a cloud-based form-builder owned by SurveyMonkey Inc. It lets non-developers
build registration forms, surveys, contact forms, application forms, and payment
forms through a drag-and-drop interface, then collect and report on submissions.
This repository profiles Wufoo's developer surface: the v3 REST API, push
webhooks, official SDKs, pricing, rate limits, and the shared vocabulary of the
platform.

- Homepage: https://www.wufoo.com
- API documentation: https://wufoo.github.io/docs/
- API help article: https://help.surveymonkey.com/en/wufoo/integrations/wufoo-api/
- Status: https://status.wufoo.com/ (Atom: https://status.wufoo.com/history.atom, RSS: https://status.wufoo.com/history.rss)
- Blog: https://www.wufoo.com/blog/ (RSS: https://www.wufoo.com/blog/feed/)
- GitHub: https://github.com/wufoo

## APIs

### Wufoo REST API v3

The v3 REST API exposes Forms, Fields, Entries, Reports, Widgets, Comments, Users,
Webhooks, and Login. It uses HTTP Basic Auth with the account API key as username
(password can be any non-empty string) and returns JSON or XML depending on the
`.json` / `.xml` extension on the request path. Endpoints live under
`https://{subdomain}.wufoo.com/api/v3/`.

- OpenAPI: [openapi/wufoo-rest-v3-openapi.yml](openapi/wufoo-rest-v3-openapi.yml)
- Spectral rules: [rules/wufoo-rest-v3-rules.yml](rules/wufoo-rest-v3-rules.yml)
- Naftiko capabilities (8, one per business surface):
  - [capabilities/rest-v3-forms.yaml](capabilities/rest-v3-forms.yaml)
  - [capabilities/rest-v3-fields.yaml](capabilities/rest-v3-fields.yaml)
  - [capabilities/rest-v3-entries.yaml](capabilities/rest-v3-entries.yaml)
  - [capabilities/rest-v3-reports.yaml](capabilities/rest-v3-reports.yaml)
  - [capabilities/rest-v3-comments.yaml](capabilities/rest-v3-comments.yaml)
  - [capabilities/rest-v3-users.yaml](capabilities/rest-v3-users.yaml)
  - [capabilities/rest-v3-webhooks.yaml](capabilities/rest-v3-webhooks.yaml)
  - [capabilities/rest-v3-login.yaml](capabilities/rest-v3-login.yaml)
- JSON Schema: Form, Field, Entry, Report, User (under [json-schema/](json-schema/))
- JSON Structure: Form, Entry (under [json-structure/](json-structure/))
- Examples: list forms, list fields, list entries, submit entry, put webhook (under [examples/](examples/))

### Wufoo Webhooks

Each form supports up to 10 webhook subscribers. When an entry is submitted, Wufoo
POSTs a form-encoded payload to each subscriber URL. When `metadata=true` is set
at subscription time, the payload includes JSON-encoded `FormStructure` and
`FieldStructure`. When a `handshakeKey` was provided, it is echoed back as
`HandshakeKey` in every payload.

- AsyncAPI: [asyncapi/wufoo-webhooks-asyncapi.yml](asyncapi/wufoo-webhooks-asyncapi.yml)
- Webhook payload schema: [json-schema/wufoo-webhook-payload-schema.json](json-schema/wufoo-webhook-payload-schema.json)
- Example payload: [examples/wufoo-webhooks-form-submission-example.json](examples/wufoo-webhooks-form-submission-example.json)

## Commercial surface

- Plans & pricing: [plans/wufoo-plans-pricing.yml](plans/wufoo-plans-pricing.yml) — Free, Starter ($16.25/mo annual), Professional ($33.25/mo), Advanced ($83.25/mo), Ultimate ($210.25/mo).
- Rate limits: [rate-limits/wufoo-rate-limits.yml](rate-limits/wufoo-rate-limits.yml) — entry submission capped at 50 per user per 5-minute sliding window (HTTP 429 when exceeded); list-forms `limit` max 1000; entries/comments `pageSize` max 100; 10 webhooks per form.
- FinOps: [finops/wufoo-finops.yml](finops/wufoo-finops.yml) — fixed-tier subscription, no metered overage line.

## SDKs (community / former first-party)

| Language | Repo |
|---|---|
| PHP | https://github.com/wufoo/Wufoo-PHP-API-Wrapper |
| Python | https://github.com/wufoo/pyfoo |
| Ruby | https://github.com/wufoo/wuparty |
| Java | https://github.com/wufoo/j-woo |
| jQuery | https://github.com/wufoo/Wufoo-jQuery-API-Wrapper |

## Semantic layer

- Vocabulary: [vocabulary/wufoo-vocabulary.yml](vocabulary/wufoo-vocabulary.yml)
- JSON-LD context: [json-ld/wufoo-context.jsonld](json-ld/wufoo-context.jsonld)

## Authentication summary

```
Authorization: Basic base64(API_KEY:any_password)
```

Each sub-user holds their own API key for permission isolation. HTTPS is required
— SSLv3 and lower are blocked.

## Inventory

| Artifact | Count |
|---|---|
| OpenAPI specs | 1 |
| AsyncAPI specs | 1 |
| Naftiko capabilities | 8 |
| JSON Schemas | 6 |
| JSON Structures | 2 |
| JSON-LD contexts | 1 |
| Vocabulary files | 1 |
| Spectral rulesets | 1 |
| Examples | 6 |
| Plans | 1 |
| Rate-limit files | 1 |
| FinOps files | 1 |
