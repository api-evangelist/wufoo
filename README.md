# Wufoo

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Wufoo is an online form-builder owned by SurveyMonkey Inc. It lets non-developers
build registration forms, surveys, contact forms, application forms, and payment
forms through a drag-and-drop interface, then collect and report on submissions.
Wufoo exposes a v3 REST API (Basic Auth, JSON/XML) over Forms, Entries, Fields,
Users, Reports, Widgets, Comments, and Webhooks, plus push webhooks that POST
form data to subscriber URLs at submission time.

**Areas:** Forms · Form Builder · Surveys · Data Collection · Webhook · Payments · SurveyMonkey

## Wufoo on APIs.io

Everything profiled for Wufoo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/wufoo/](https://apis.io/providers/wufoo/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Wufoo Webhooks](https://apis.io/apis/wufoo/wufoo-webhooks/) — Wufoo webhooks POST form-submission payloads to a subscriber URL at the moment an entry is created. Up to 10 webhooks per form, with optional handshake key…
- [Wufoo Comments API](https://apis.io/apis/wufoo/wufoo-comments-api/) — Read comments attached to entries.
- [Wufoo Entries API](https://apis.io/apis/wufoo/wufoo-entries-api/) — Read and create form submissions.
- [Wufoo Fields API](https://apis.io/apis/wufoo/wufoo-fields-api/) — Read the field structure of a form or report.
- [Wufoo Forms API](https://apis.io/apis/wufoo/wufoo-forms-api/) — Read forms and their metadata.
- [Wufoo Login API](https://apis.io/apis/wufoo/wufoo-login-api/) — Exchange credentials for an API key.
- [Wufoo Reports API](https://apis.io/apis/wufoo/wufoo-reports-api/) — Read reports built on top of forms.
- [Wufoo Users API](https://apis.io/apis/wufoo/wufoo-users-api/) — Read account user information.
- [Wufoo Webhooks API](https://apis.io/apis/wufoo/wufoo-webhooks-api/) — Subscribe to and unsubscribe from form submission webhooks.
- [Wufoo Widgets API](https://apis.io/apis/wufoo/wufoo-widgets-api/) — Read widgets inside reports.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (9)

Multi-step workflows that chain operations into a business task.

- [Wufoo Add a Form Webhook](https://apis.io/arazzos/wufoo/wufoo-add-form-webhook-workflow/)
- [Wufoo Browse Form Entries](https://apis.io/arazzos/wufoo/wufoo-browse-form-entries-workflow/)
- [Wufoo Moderate Form Comments](https://apis.io/arazzos/wufoo/wufoo-moderate-form-comments-workflow/)
- [Wufoo Provision Builder User Forms](https://apis.io/arazzos/wufoo/wufoo-provision-builder-user-forms-workflow/)
- [Wufoo Export Report Entries](https://apis.io/arazzos/wufoo/wufoo-report-entries-export-workflow/)
- [Wufoo Report Entry Stats](https://apis.io/arazzos/wufoo/wufoo-report-entry-stats-workflow/)
- [Wufoo Report Widget Overview](https://apis.io/arazzos/wufoo/wufoo-report-widget-overview-workflow/)
- [Wufoo Rotate a Form Webhook](https://apis.io/arazzos/wufoo/wufoo-rotate-form-webhook-workflow/)
- [Wufoo Submit a Form Entry](https://apis.io/arazzos/wufoo/wufoo-submit-form-entry-workflow/)

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Wufoo Webhooks](https://apis.io/asyncapis/wufoo/wufoo-webhooks-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [form.entry.created](https://apis.io/channels/wufoo/form-entry-created/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Wufoo Agentic Access](https://apis.io/agentic-access/wufoo/wufoo-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [Wufoo Entry](https://apis.io/schemas/wufoo/wufoo-entry/)
- [Wufoo Field](https://apis.io/schemas/wufoo/wufoo-field/)
- [Wufoo Form](https://apis.io/schemas/wufoo/wufoo-form/)
- [Wufoo Report](https://apis.io/schemas/wufoo/wufoo-report/)
- [Wufoo User](https://apis.io/schemas/wufoo/wufoo-user/)
- [Wufoo Webhook Payload](https://apis.io/schemas/wufoo/wufoo-webhook-payload/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Wufoo Entry Structure](https://apis.io/json-structure/wufoo/wufoo-entry-structure/)
- [Wufoo Form Structure](https://apis.io/json-structure/wufoo/wufoo-form-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Wufoo Context](https://apis.io/jsonld/wufoo/wufoo-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Wufoo Vocabulary](https://apis.io/vocabularies/wufoo/wufoo-vocabulary/)

#### Examples (6)

Example requests and responses.

- [Wufoo Rest V3 List Entries Example](https://apis.io/examples/wufoo/wufoo-rest-v3-list-entries-example/)
- [Wufoo Rest V3 List Form Fields Example](https://apis.io/examples/wufoo/wufoo-rest-v3-list-form-fields-example/)
- [Wufoo Rest V3 List Forms Example](https://apis.io/examples/wufoo/wufoo-rest-v3-list-forms-example/)
- [Wufoo Rest V3 Put Webhook Example](https://apis.io/examples/wufoo/wufoo-rest-v3-put-webhook-example/)
- [Wufoo Rest V3 Submit Entry Example](https://apis.io/examples/wufoo/wufoo-rest-v3-submit-entry-example/)
- [Wufoo Webhooks Form Submission Example](https://apis.io/examples/wufoo/wufoo-webhooks-form-submission-example/)

#### Collections (19)

Postman and Open Collection request collections.

- [Wufoo REST Comments API](https://apis.io/collections/wufoo/open-wufoo-comments-api/)
- [Wufoo REST Comments Entries API](https://apis.io/collections/wufoo/open-wufoo-entries-api/)
- [Wufoo REST Comments Fields API](https://apis.io/collections/wufoo/open-wufoo-fields-api/)
- [Wufoo REST Comments Forms API](https://apis.io/collections/wufoo/open-wufoo-forms-api/)
- [Wufoo REST Comments Login API](https://apis.io/collections/wufoo/open-wufoo-login-api/)
- [Wufoo REST Comments Reports API](https://apis.io/collections/wufoo/open-wufoo-reports-api/)
- [Wufoo REST API](https://apis.io/collections/wufoo/open-wufoo-rest-v3/)
- [Wufoo REST Comments Users API](https://apis.io/collections/wufoo/open-wufoo-users-api/)
- [Wufoo REST Comments Webhooks API](https://apis.io/collections/wufoo/open-wufoo-webhooks-api/)
- [Wufoo REST Comments Widgets API](https://apis.io/collections/wufoo/open-wufoo-widgets-api/)
- [Wufoo REST Comments API](https://apis.io/collections/wufoo/postman-wufoo-comments-api/)
- [Wufoo REST Comments Entries API](https://apis.io/collections/wufoo/postman-wufoo-entries-api/)
- [Wufoo REST Comments Fields API](https://apis.io/collections/wufoo/postman-wufoo-fields-api/)
- [Wufoo REST Comments Forms API](https://apis.io/collections/wufoo/postman-wufoo-forms-api/)
- [Wufoo REST Comments Login API](https://apis.io/collections/wufoo/postman-wufoo-login-api/)
- [Wufoo REST Comments Reports API](https://apis.io/collections/wufoo/postman-wufoo-reports-api/)
- [Wufoo REST Comments Users API](https://apis.io/collections/wufoo/postman-wufoo-users-api/)
- [Wufoo REST Comments Webhooks API](https://apis.io/collections/wufoo/postman-wufoo-webhooks-api/)
- [Wufoo REST Comments Widgets API](https://apis.io/collections/wufoo/postman-wufoo-widgets-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Wufoo — asyncapi rules](https://apis.io/rules/wufoo/wufoo-asyncapi-spectral-rules/)
- [Wufoo — jsonschema rules](https://apis.io/rules/wufoo/wufoo-jsonschema-spectral-rules/)
- [Wufoo — rest v3 rules](https://apis.io/rules/wufoo/wufoo-rest-v3-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Wufoo Authentication](https://apis.io/security/wufoo/wufoo-authentication/)
- [Wufoo Domain Security](https://apis.io/security/wufoo/wufoo-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Wufoo Plans Pricing](https://apis.io/plans/wufoo/wufoo-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Wufoo Rate Limits](https://apis.io/rate-limits/wufoo/wufoo-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Wufoo Finops](https://apis.io/finops/wufoo/wufoo-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.wufoo.com/)
- [Documentation](https://wufoo.github.io/docs/)
- [Getting started](https://help.surveymonkey.com/en/wufoo/integrations/wufoo-api/)
- [API reference](https://wufoo.github.io/docs/)
- [Pricing](https://www.wufoo.com/pricing/)
- [Support](https://help.surveymonkey.com/wufoo/)
- [Blog](https://www.wufoo.com/blog/)
- [Terms of service](https://www.wufoo.com/terms-of-use/)
- [Privacy policy](https://www.wufoo.com/privacy/)
- [GitHub](https://github.com/wufoo)
- [Status](https://status.wufoo.com/)

## API Evangelist rating

**Kin Score 50.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 67.3 |
| Contract governance | 27.3 |
| Operational transparency | 18.4 |
| Developer ergonomics | 75.0 |
| Access clarity | 35.5 |

**Agent readiness 22.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 18.8** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/wufoo/](https://apis.io/providers/wufoo/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Wufoo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/wufoo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
