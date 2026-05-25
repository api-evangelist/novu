# Novu (novu)

Novu is the open-source notification infrastructure for developers. A single REST API and workflow engine route a triggered event across in-app inbox, email, SMS, push, chat (Slack / Discord / MS Teams / WhatsApp) and custom channels — with subscriber preferences, topics, digest, snooze, and full workflow orchestration on top. Ships with the embeddable React Inbox component, the Novu Framework for code-first workflow authoring, language SDKs for nine ecosystems, a Postman collection, an MCP server, GitHub Action sync, the Maily block-based email editor, framework starters for Next.js / Remix / Nuxt / SvelteKit, and webhook bridges for Stripe / Clerk / Segment.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/novu/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Notifications, Messaging, In App, Email, SMS, Push, Chat, Workflows, Open Source, Subscribers, Topics, Inbox, Workflow Orchestration, Multi Channel, Digest, MCP, Framework, React

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-25

## APIs

### Novu REST API

Server-side REST API exposing 135 operations across Events, Subscribers, Workflows, Topics, Integrations, Layouts, Messages, Notifications, Environments, Environment Variables, Domains, Channel Connections, Channel Endpoints, Translations, Activity, and Contexts. Authenticated with an ApiKey scheme delivered in the Authorization header. Honors IETF RateLimit-* headers, Idempotency-Key, and a published OpenAPI 3 document available at /openapi.json on every region.

**Human URL:** [https://docs.novu.co/api-reference/overview](https://docs.novu.co/api-reference/overview)

**Base URL:** `https://api.novu.co`

#### Tags:

 - REST, Events, Subscribers, Workflows, Topics, Integrations, Messages, Notifications, Environments, Domains, Idempotency, Rate Limits

#### Properties

- [Documentation](https://docs.novu.co/api-reference/overview)
- [APIReference](https://docs.novu.co/api-reference/overview)
- [OpenAPI](openapi/novu-openapi.yml)
- [OpenAPI — Live OpenAPI 3 spec](https://api.novu.co/openapi.json)
- [Swagger](https://api.novu.co/api)
- [Postman](https://github.com/novuhq/novu-postman)
- [Authentication](https://docs.novu.co/api-reference/overview#authentication)
- [RateLimits](rate-limits/novu-rate-limits.yml)
- [Quickstart](https://docs.novu.co/platform/quickstart/nextjs)
- [SDK — TypeScript / Node.js SDK](https://www.npmjs.com/package/@novu/api)
- [SDK — Python SDK](https://pypi.org/project/novu-py/)
- [SDK — Go SDK](https://github.com/novuhq/novu-go)
- [SDK — PHP SDK](https://github.com/novuhq/php-novu)
- [SDK — C# SDK](https://github.com/novuhq/novu-csharp)
- [SDK — Java SDK](https://github.com/novuhq/novu-java)
- [SDK — Elixir SDK](https://github.com/novuhq/novu-elixir)
- [SDK — Kotlin SDK](https://github.com/novuhq/novu-kotlin)
- [SDK — Ruby SDK](https://github.com/novuhq/novu-ruby)
- [SDK — Rust SDK](https://github.com/novuhq/novu-rust)
- [SDK — .NET SDK](https://github.com/novuhq/novu-dotnet)
- [CodeExamples](https://github.com/novuhq/examples)

#### Naftiko Capabilities

- [novu-events.yaml](capabilities/novu-events.yaml) — 4 ops — Trigger / Bulk / Broadcast / Cancel
- [novu-subscribers.yaml](capabilities/novu-subscribers.yaml) — 35 ops — Subscriber lifecycle (v1 + v2)
- [novu-workflows.yaml](capabilities/novu-workflows.yaml) — 9 ops — Workflow CRUD and activation
- [novu-topics.yaml](capabilities/novu-topics.yaml) — 11 ops — Topic creation and membership
- [novu-integrations.yaml](capabilities/novu-integrations.yaml) — 10 ops — Channel provider integrations
- [novu-environments.yaml](capabilities/novu-environments.yaml) — 7 ops — Environment CRUD
- [novu-environment-variables.yaml](capabilities/novu-environment-variables.yaml) — 6 ops — Per-environment variables
- [novu-messages.yaml](capabilities/novu-messages.yaml) — 3 ops — Message inspection
- [novu-notifications.yaml](capabilities/novu-notifications.yaml) — 2 ops — Notification event inspection
- [novu-layouts.yaml](capabilities/novu-layouts.yaml) — 8 ops — Layout templates
- [novu-translations.yaml](capabilities/novu-translations.yaml) — 9 ops — Translation strings
- [novu-domains.yaml](capabilities/novu-domains.yaml) — 15 ops — Sender domain verification
- [novu-channel-connections.yaml](capabilities/novu-channel-connections.yaml) — 5 ops — OAuth channel hookups
- [novu-channel-endpoints.yaml](capabilities/novu-channel-endpoints.yaml) — 5 ops — Channel endpoint resolution
- [novu-activity.yaml](capabilities/novu-activity.yaml) — 1 op — Workflow activity feed
- [novu-contexts.yaml](capabilities/novu-contexts.yaml) — 5 ops — Tenant / context objects

### Novu REST API (EU Region)

EU-hosted instance of the Novu REST API for customers requiring data residency in the European Union. Exposes the same 135 operations, schemas, security, and rate-limit policy as the global instance. Enterprise data residency can extend to UK, Singapore, Australia, Japan, and South Korea.

**Human URL:** [https://docs.novu.co/api-reference/overview](https://docs.novu.co/api-reference/overview)

**Base URL:** `https://eu.api.novu.co`

#### Tags:

 - REST, EU, Data Residency

#### Properties

- [Documentation](https://docs.novu.co/api-reference/overview)
- [OpenAPI](openapi/novu-openapi.yml)
- [Authentication](https://docs.novu.co/api-reference/overview#authentication)
- [RateLimits](rate-limits/novu-rate-limits.yml)

### Novu Inbox / In-App API

Client-side API and React Inbox component for rendering an embedded in-app notification center, marking notifications as read / archived / snoozed, and managing per-user notification preferences directly in the browser. Ships with @novu/react, @novu/react-native, and @novu/js (vanilla) packages, plus pre-built Notion / Linear / Novu themes and full headless API access.

**Human URL:** [https://docs.novu.co/platform/inbox/overview](https://docs.novu.co/platform/inbox/overview)

**Base URL:** `https://api.novu.co`

#### Tags:

 - In App, Inbox, React, React Native, Client SDK, Headless

#### Properties

- [Documentation](https://docs.novu.co/platform/inbox/overview)
- [Quickstart](https://docs.novu.co/platform/quickstart/react)
- [SDK — React Inbox SDK](https://www.npmjs.com/package/@novu/react)
- [SDK — React Native Inbox SDK](https://www.npmjs.com/package/@novu/react-native)
- [SDK — Headless JS Inbox SDK](https://www.npmjs.com/package/@novu/js)
- [SDK — Next.js Inbox helpers](https://www.npmjs.com/package/@novu/nextjs)
- [CodeExamples — Inbox Playground](https://github.com/novuhq/inbox-playground)

### Novu Framework (Code-First Workflows)

Code-first workflow framework that lets developers define notification workflows in TypeScript / JavaScript using `@novu/framework`, then sync them to Novu Cloud (or a self-hosted instance) via the `npx novu-sync` CLI or the `novuhq/actions-novu-sync` GitHub Action. Supports Express, Next.js, NestJS, Remix, SvelteKit, Nuxt, H3, AWS Lambda, and any node-runtime HTTP handler. The framework owns the workflow source-of-truth — the Dashboard editor stays in sync via a deterministic bridge URL.

**Human URL:** [https://docs.novu.co/framework/overview](https://docs.novu.co/framework/overview)

**Base URL:** `https://docs.novu.co/framework`

#### Tags:

 - Framework, Code First, Workflows, TypeScript, Next.js, Express, NestJS, Remix, SvelteKit, Nuxt, AWS Lambda

#### Properties

- [Documentation](https://docs.novu.co/framework/overview)
- [Quickstart](https://docs.novu.co/framework/quickstart/nextjs)
- [SDK — @novu/framework](https://www.npmjs.com/package/@novu/framework)
- [CLI — npx novu-sync](https://www.npmjs.com/package/novu)
- [CodeExamples — Next.js + React Email](https://github.com/novuhq/novu-framework-nextjs-react-email-example)
- [CodeExamples — Remix](https://github.com/novuhq/novu-framework-remix-example)
- [CodeExamples — Nuxt](https://github.com/novuhq/novu-framework-nuxt-example)
- [CodeExamples — Nuxt + VueEmail](https://github.com/novuhq/novu-framework-nuxt-vue-email-example)
- [CodeExamples — Newsletter App](https://github.com/novuhq/novu-framework-newsletter-app-example)

### Novu MCP Server

Official Model Context Protocol server exposing the Novu REST API surface as MCP tools so AI agents (Claude Desktop, Cursor, agent frameworks) can trigger workflows, manage subscribers, list workflows, and inspect activity without bespoke wrapping. Distributed as a stdio server runnable via `npx @novu/mcp-server`.

**Human URL:** [https://github.com/novuhq/novu-mcp-server](https://github.com/novuhq/novu-mcp-server)

**Base URL:** `https://github.com/novuhq/novu-mcp-server`

#### Tags:

 - MCP, AI Agents, LLM, Tools, Notifications

#### Properties

- [Documentation](https://github.com/novuhq/novu-mcp-server)
- [SourceCode](https://github.com/novuhq/novu-mcp-server)

## Common Properties

- [Website](https://novu.co)
- [Portal](https://docs.novu.co)
- [Documentation](https://docs.novu.co)
- [SignUp](https://web.novu.co/auth/signup)
- [Login](https://web.novu.co)
- [Pricing](https://novu.co/pricing)
- [Plans](plans/novu-plans-pricing.yml)
- [FinOps](finops/novu-finops.yml)
- [RateLimits](rate-limits/novu-rate-limits.yml)
- [Blog](https://novu.co/blog)
- [GitHub](https://github.com/novuhq)
- [GitHubOrganization](https://github.com/novuhq)
- [GitHubRepository — novuhq/novu (main monorepo, 39k+ stars)](https://github.com/novuhq/novu)
- [SourceCode](https://github.com/novuhq/novu)
- [License — MIT License](https://github.com/novuhq/novu/blob/next/LICENSE)
- [SDK](https://docs.novu.co/sdks/introduction)
- [CLI — Novu CLI](https://docs.novu.co/community/run-in-local-machine)
- [Framework — Novu Framework](https://docs.novu.co/framework/overview)
- [Inbox — Novu Inbox](https://docs.novu.co/platform/inbox/overview)
- [Integrations](https://docs.novu.co/platform/integrations)
- [ChangeLog](https://novu.co/changelog)
- [ReleaseNotes](https://github.com/novuhq/novu/releases)
- [StatusPage](https://status.novu.co)
- [TermsOfService](https://novu.co/terms)
- [PrivacyPolicy](https://novu.co/privacy)
- [Community — Novu Discord](https://discord.gg/novu)
- [StackOverflow](https://stackoverflow.com/questions/tagged/novu)
- [YouTube](https://www.youtube.com/@novuhq)
- [LLMsTxt](https://docs.novu.co/llms.txt)
- [SpectralRules](rules/novu-spectral-rules.yml)
- [Vocabulary](vocabulary/novu-vocabulary.yml)
- [JSON-LD](json-ld/novu-context.jsonld)
- [Tools — Novu MCP Server](https://github.com/novuhq/novu-mcp-server)
- [Tools — Maily — block-based email editor (used by Novu Cloud)](https://github.com/novuhq/maily.to)
- [Tools — actions-novu-sync — GitHub Action to sync workflows to Novu Cloud](https://github.com/novuhq/actions-novu-sync)
- [Tools — Stripe → Novu webhook bridge](https://github.com/novuhq/stripe-to-novu-webhooks)
- [Tools — Clerk → Novu webhook bridge](https://github.com/novuhq/clerk-to-novu-webhooks)
- [Tools — Segment → Novu webhook bridge](https://github.com/novuhq/segment-to-novu-webhooks)
- [Tools — Community Kubernetes manifests for self-hosting](https://github.com/novuhq/community-k8s)
- [Tutorials — Inbox Playground](https://github.com/novuhq/inbox-playground)
- [Tutorials — Novu Examples](https://github.com/novuhq/examples)
- [Tutorials — Awesome Novu](https://github.com/novuhq/awesome-novu)
- [Tutorials](https://docs.novu.co/guides)
- [Skills — Novu Skill Set for AI Agents](https://github.com/novuhq/skills)

## Features

| Name | Description |
|------|-------------|
| Multi-channel Workflow Orchestration | Author a single workflow tree that fans out across in-app, email, SMS, push, and chat with branching, delay, and digest steps. |
| Embedded React Inbox | Drop-in `<Inbox />` React (and React Native) component with per-user preferences, read / archive / snooze, themes (Novu / Notion / Linear), and full headless API access. |
| Subscriber Identity | First-class Subscribers resource with credentials per channel, locale, timezone, preferences, and bulk import. |
| Topics for Fan-out | Named broadcast groups subscribed by users for one-call fan-out to thousands of subscribers. |
| Digest Engine | Aggregate high-frequency triggers into a single delivery using configurable digest windows and back-off keys. |
| Code-First Framework | Define workflows in TypeScript using @novu/framework and sync to Novu Cloud via novu-sync or a GitHub Action. |
| Block-Based Email Editor | WYSIWYG block-based editor (open-sourced as Maily.to) powered by React Email under the hood. |
| Tenant / Context Objects | Reusable tenant and organization context objects referenced by trigger payloads for multi-tenant routing. |
| Idempotency + RateLimit Headers | IETF-style RateLimit-* headers on every response, Idempotency-Key on every mutating request. |
| MCP Server | Official Model Context Protocol server exposing the Novu REST API to AI agents. |
| Self-Hosting | Apache-/MIT-licensed monorepo with Docker Compose and community Kubernetes manifests for fully self-hosted deployments. |
| 9 Language SDKs | TypeScript, Python, Go, PHP, C#, Java, Elixir, Kotlin, Ruby, Rust, .NET clients. |

## Use Cases

| Name | Description |
|------|-------------|
| Product Onboarding | Welcome sequences combining transactional email, in-app inbox messages, and reminders. |
| Transactional Notifications | Order confirmations, password resets, magic links, payment receipts, and shipping updates. |
| Real-Time Collaboration Alerts | Comment mentions, document shares, and review requests delivered to the in-app inbox and email. |
| Subscription Lifecycle | Trial reminders, renewal warnings, dunning, and cancellation flows driven by billing events. |
| Authentication Events | Sign-up confirmations, MFA prompts, suspicious-login alerts, and OTP codes. |
| Marketing Broadcasts | Product announcements and weekly digests fanned out via topics. |
| Operational Alerts | On-call paging, deploy notifications, and incident updates routed through Slack / MS Teams. |
| Multi-Tenant SaaS | Per-customer routing using tenant context and subscriber data inheritance. |
| AI Agent Notifications | Agent workflows triggering Novu via the MCP server to keep humans in the loop. |

## Integrations

| Name | Description |
|------|-------------|
| SendGrid | Outbound email integration via SendGrid credentials. |
| Mailgun | Outbound email integration via Mailgun. |
| Resend | Outbound email integration via Resend. |
| Postmark | Outbound transactional email via Postmark. |
| AWS SES | Outbound email via Amazon Simple Email Service. |
| Twilio | SMS delivery via Twilio. |
| MessageBird | SMS delivery via MessageBird. |
| Plivo | SMS delivery via Plivo. |
| Firebase Cloud Messaging | Mobile push delivery via FCM. |
| Apple Push Notification Service | iOS push delivery via APNs. |
| OneSignal | Push delivery via OneSignal. |
| Slack | Chat notifications to Slack channels and users. |
| Microsoft Teams | Chat notifications to MS Teams channels. |
| Discord | Chat notifications to Discord channels. |
| WhatsApp | Conversational notifications via WhatsApp. |
| Stripe | Billing-event-to-notification bridge via stripe-to-novu-webhooks. |
| Clerk | Authentication-event-to-notification bridge via clerk-to-novu-webhooks. |
| Segment | CDP-event-to-notification bridge via segment-to-novu-webhooks. |
| React | First-class React Inbox component and Next.js helpers. |
| GitHub Actions | actions-novu-sync syncs framework workflows to Novu Cloud on every push. |

## Solutions

| Name | Description |
|------|-------------|
| Novu Cloud | Managed Novu hosted by the Novu team. Free / Pro / Team / Enterprise plans. |
| Self-Hosted Open Source | Run the full Novu monorepo on your own infrastructure under MIT license. Docker Compose for development, community Kubernetes manifests for production. |
| Novu EU Cloud | EU-resident Novu Cloud deployment at eu.api.novu.co. |
| Enterprise (HIPAA, SSO, SCIM) | HIPAA BAA, custom SSO, SCIM directory sync, and custom data-residency regions (US, EU, UK, Singapore, Australia, Japan, South Korea). |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [novu-openapi.yml](openapi/novu-openapi.yml) — Novu API v3.15 (135 operations across 93 paths, 16 tags, 392 component schemas)

### JSON Schema

- [novu-trigger-event-request-dto-schema.json](json-schema/novu-trigger-event-request-dto-schema.json)
- [novu-trigger-event-response-dto-schema.json](json-schema/novu-trigger-event-response-dto-schema.json)
- [novu-bulk-trigger-event-dto-schema.json](json-schema/novu-bulk-trigger-event-dto-schema.json)
- [novu-subscriber-response-dto-schema.json](json-schema/novu-subscriber-response-dto-schema.json)
- [novu-create-subscriber-request-dto-schema.json](json-schema/novu-create-subscriber-request-dto-schema.json)
- [novu-bulk-subscriber-create-dto-schema.json](json-schema/novu-bulk-subscriber-create-dto-schema.json)
- [novu-create-environment-request-dto-schema.json](json-schema/novu-create-environment-request-dto-schema.json)
- [novu-update-environment-request-dto-schema.json](json-schema/novu-update-environment-request-dto-schema.json)
- [novu-environment-response-dto-schema.json](json-schema/novu-environment-response-dto-schema.json)
- [novu-topic-response-dto-schema.json](json-schema/novu-topic-response-dto-schema.json)
- [novu-create-integration-request-dto-schema.json](json-schema/novu-create-integration-request-dto-schema.json)
- [novu-update-integration-request-dto-schema.json](json-schema/novu-update-integration-request-dto-schema.json)
- [novu-integration-response-dto-schema.json](json-schema/novu-integration-response-dto-schema.json)
- [novu-message-response-dto-schema.json](json-schema/novu-message-response-dto-schema.json)
- [novu-create-workflow-dto-schema.json](json-schema/novu-create-workflow-dto-schema.json)
- [novu-update-workflow-dto-schema.json](json-schema/novu-update-workflow-dto-schema.json)
- [novu-workflow-response-dto-schema.json](json-schema/novu-workflow-response-dto-schema.json)
- [novu-layout-response-dto-schema.json](json-schema/novu-layout-response-dto-schema.json)
- [novu-subscriber-payload-dto-schema.json](json-schema/novu-subscriber-payload-dto-schema.json)
- [novu-error-dto-schema.json](json-schema/novu-error-dto-schema.json)

### JSON Structure

20 lightweight JSON Structure mirrors of the JSON Schema set in [`json-structure/`](json-structure/).

### JSON-LD

- [novu-context.jsonld](json-ld/novu-context.jsonld) — Unified Novu JSON-LD 1.1 context (20 types, 105 properties) aligning subscriber, workflow, message, topic, and integration properties to schema.org and dcterms namespaces

### Examples

- [novu-trigger-event-example.json](examples/novu-trigger-event-example.json)
- [novu-trigger-event-bulk-example.json](examples/novu-trigger-event-bulk-example.json)
- [novu-broadcast-event-example.json](examples/novu-broadcast-event-example.json)
- [novu-create-subscriber-example.json](examples/novu-create-subscriber-example.json)
- [novu-bulk-create-subscribers-example.json](examples/novu-bulk-create-subscribers-example.json)
- [novu-create-topic-example.json](examples/novu-create-topic-example.json)
- [novu-add-subscribers-to-topic-example.json](examples/novu-add-subscribers-to-topic-example.json)
- [novu-create-environment-example.json](examples/novu-create-environment-example.json)
- [novu-create-integration-example.json](examples/novu-create-integration-example.json)
- [novu-workflow-response-example.json](examples/novu-workflow-response-example.json)
- [novu-list-messages-example.json](examples/novu-list-messages-example.json)
- [novu-error-response-example.json](examples/novu-error-response-example.json)

## Capabilities

Naftiko capabilities organized as self-contained per-tag workflows. Every file ships with both a REST (port 8080) and an MCP (port 9090) exposer routed through its own inline `consumes` block.

| Capability | Tag | Tools | File |
|------------|-----|-------|------|
| Novu Events | Events | 4 | [novu-events.yaml](capabilities/novu-events.yaml) |
| Novu Subscribers | Subscribers | 35 | [novu-subscribers.yaml](capabilities/novu-subscribers.yaml) |
| Novu Workflows | Workflows | 9 | [novu-workflows.yaml](capabilities/novu-workflows.yaml) |
| Novu Topics | Topics | 11 | [novu-topics.yaml](capabilities/novu-topics.yaml) |
| Novu Integrations | Integrations | 10 | [novu-integrations.yaml](capabilities/novu-integrations.yaml) |
| Novu Environments | Environments | 7 | [novu-environments.yaml](capabilities/novu-environments.yaml) |
| Novu Environment Variables | Environment Variables | 6 | [novu-environment-variables.yaml](capabilities/novu-environment-variables.yaml) |
| Novu Messages | Messages | 3 | [novu-messages.yaml](capabilities/novu-messages.yaml) |
| Novu Notifications | Notifications | 2 | [novu-notifications.yaml](capabilities/novu-notifications.yaml) |
| Novu Layouts | Layouts | 8 | [novu-layouts.yaml](capabilities/novu-layouts.yaml) |
| Novu Translations | Translations | 9 | [novu-translations.yaml](capabilities/novu-translations.yaml) |
| Novu Domains | Domains | 15 | [novu-domains.yaml](capabilities/novu-domains.yaml) |
| Novu Channel Connections | Channel Connections | 5 | [novu-channel-connections.yaml](capabilities/novu-channel-connections.yaml) |
| Novu Channel Endpoints | Channel Endpoints | 5 | [novu-channel-endpoints.yaml](capabilities/novu-channel-endpoints.yaml) |
| Novu Activity | Activity | 1 | [novu-activity.yaml](capabilities/novu-activity.yaml) |
| Novu Contexts | Contexts | 5 | [novu-contexts.yaml](capabilities/novu-contexts.yaml) |

## Vocabulary

- [Novu Vocabulary](vocabulary/novu-vocabulary.yml) — Unified taxonomy mapping 14 resources, 12 actions, 16 capability workflows, and 9 personas across the operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Novu Spectral Ruleset](rules/novu-spectral-rules.yml) — 37 rules across 12 categories (info / openapi / servers / paths / operations / parameters / responses / schemas / security / methods / general / tags) enforcing Novu API conventions.

## Plans, Rate Limits, and FinOps

- [Plans](plans/novu-plans-pricing.yml) — API Commons Plans 0.1 alignment for the Free, Pro ($30/mo), Team ($250/mo), and Enterprise tiers.
- [Rate Limits](rate-limits/novu-rate-limits.yml) — API Commons Rate Limits 0.1 alignment capturing per-tier RPS envelopes (60 / 240 / 600), monthly workflow-run quotas (10K / 30K / 250K / 10M+), overage at $1.20/1K runs, and the RateLimit-* / Idempotency-Key header surface.
- [FinOps](finops/novu-finops.yml) — FinOps Framework / FOCUS 1.3 alignment for cost allocation against the workflow-run unit, with channel provider pass-through called out as a separate cost domain.

## Maintainers

**FN:** Kin Lane

**Email:** kinlane@gmail.com
