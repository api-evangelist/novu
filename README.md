# Novu (novu)

Novu is the open-source notification infrastructure for developers. A single REST API and workflow engine route a triggered event across in-app inbox, email, SMS, push, chat (Slack / Discord / MS Teams / WhatsApp) and custom channels — with subscriber preferences, topics, digest, snooze, and full workflow orchestration on top. Ships with the embeddable React Inbox component, the Novu Framework for code-first workflow authoring, language SDKs for nine ecosystems, a Postman collection, an MCP server, GitHub Action sync, the Maily block-based email editor, framework starters for Next.js / Remix / Nuxt / SvelteKit, and webhook bridges for Stripe / Clerk / Segment.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/novu/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/novu/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Notifications
- Messaging
- In App
- Email
- SMS
- Push
- Chat
- Workflows
- Open Source
- Subscribers
- Topics
- Inbox
- Workflow Orchestration
- Multi Channel
- Digest
- MCP
- Framework
- React

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### Novu REST API

Server-side REST API exposing 135 operations across Events, Subscribers, Workflows, Topics, Integrations, Layouts, Messages, Notifications, Environments, Environment Variables, Domains, Channel Connections, Channel Endpoints, Translations, Activity, and Contexts. Authenticated with an ApiKey scheme delivered in the Authorization header. Honors IETF RateLimit-* headers, Idempotency-Key, and a published OpenAPI 3 document available at /openapi.json on every region.

- **Human URL:** [https://docs.novu.co/api-reference/overview](https://docs.novu.co/api-reference/overview)
- **Base URL:** `https://api.novu.co`

#### Tags

- REST
- Events
- Subscribers
- Workflows
- Topics
- Integrations
- Messages
- Notifications
- Environments
- Domains
- Idempotency
- Rate Limits

#### Properties

- [Documentation](https://docs.novu.co/api-reference/overview)
- [API Reference](https://docs.novu.co/api-reference/overview)
- [OpenAPI](openapi/novu-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://api.novu.co/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Swagger](https://api.novu.co/api)
- [Postman](https://github.com/novuhq/novu-postman) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Authentication](https://docs.novu.co/api-reference/overview#authentication)
- [Rate Limits](rate-limits/novu-rate-limits.yml)
- [Quickstart](https://docs.novu.co/platform/quickstart/nextjs)
- [SDK](https://www.npmjs.com/package/@novu/api)
- [SDK](https://pypi.org/project/novu-py/)
- [SDK](https://github.com/novuhq/novu-go)
- [SDK](https://github.com/novuhq/php-novu)
- [SDK](https://github.com/novuhq/novu-csharp)
- [SDK](https://github.com/novuhq/novu-java)
- [SDK](https://github.com/novuhq/novu-elixir)
- [SDK](https://github.com/novuhq/novu-kotlin)
- [SDK](https://github.com/novuhq/novu-ruby)
- [SDK](https://github.com/novuhq/novu-rust)
- [SDK](https://github.com/novuhq/novu-dotnet)
- [Code Examples](https://github.com/novuhq/examples)
- [JSON Schema](json-schema/novu-trigger-event-request-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-trigger-event-response-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-bulk-trigger-event-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-subscriber-response-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-create-subscriber-request-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-bulk-subscriber-create-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-create-environment-request-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-update-environment-request-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-environment-response-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-topic-response-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-create-integration-request-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-update-integration-request-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-integration-response-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-message-response-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-create-workflow-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-update-workflow-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-workflow-response-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-layout-response-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-subscriber-payload-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/novu-error-dto-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/novu-trigger-event-request-dto-structure.json)
- [JSON Structure](json-structure/novu-subscriber-response-dto-structure.json)
- [JSON Structure](json-structure/novu-workflow-response-dto-structure.json)
- [JSON Structure](json-structure/novu-message-response-dto-structure.json)
- [JSON Structure](json-structure/novu-topic-response-dto-structure.json)
- [JSON Structure](json-structure/novu-integration-response-dto-structure.json)
- [Example](examples/novu-trigger-event-example.json)
- [Example](examples/novu-trigger-event-bulk-example.json)
- [Example](examples/novu-broadcast-event-example.json)
- [Example](examples/novu-create-subscriber-example.json)
- [Example](examples/novu-bulk-create-subscribers-example.json)
- [Example](examples/novu-create-topic-example.json)
- [Example](examples/novu-add-subscribers-to-topic-example.json)
- [Example](examples/novu-create-environment-example.json)
- [Example](examples/novu-create-integration-example.json)
- [Example](examples/novu-workflow-response-example.json)
- [Example](examples/novu-list-messages-example.json)
- [Example](examples/novu-error-response-example.json)

### Novu REST API (EU Region)

EU-hosted instance of the Novu REST API for customers requiring data residency in the European Union. Exposes the same 135 operations, schemas, security, and rate-limit policy as the global instance. Enterprise data residency can extend to UK, Singapore, Australia, Japan, and South Korea.

- **Human URL:** [https://docs.novu.co/api-reference/overview](https://docs.novu.co/api-reference/overview)
- **Base URL:** `https://eu.api.novu.co`

#### Tags

- REST
- EU
- Data Residency

#### Properties

- [Documentation](https://docs.novu.co/api-reference/overview)
- [OpenAPI](openapi/novu-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.novu.co/api-reference/overview#authentication)
- [Rate Limits](rate-limits/novu-rate-limits.yml)

### Novu Inbox / In-App API

Client-side API and React Inbox component for rendering an embedded in-app notification center, marking notifications as read / archived / snoozed, and managing per-user notification preferences directly in the browser. Ships with @novu/react, @novu/react-native, and @novu/js (vanilla) packages, plus pre-built Notion / Linear / Novu themes and full headless API access.

- **Human URL:** [https://docs.novu.co/platform/inbox/overview](https://docs.novu.co/platform/inbox/overview)
- **Base URL:** `https://api.novu.co`

#### Tags

- In App
- Inbox
- React
- React Native
- Client SDK
- Headless

#### Properties

- [Documentation](https://docs.novu.co/platform/inbox/overview)
- [AsyncAPI](asyncapi/novu-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Quickstart](https://docs.novu.co/platform/quickstart/react)
- [SDK](https://www.npmjs.com/package/@novu/react)
- [SDK](https://www.npmjs.com/package/@novu/react-native)
- [SDK](https://www.npmjs.com/package/@novu/js)
- [SDK](https://www.npmjs.com/package/@novu/nextjs)
- [Code Examples](https://github.com/novuhq/inbox-playground)
- [Postman Collection](collections/novu.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Framework (Code-First Workflows)

Code-first workflow framework that lets developers define notification workflows in TypeScript / JavaScript using `@novu/framework`, then sync them to Novu Cloud (or a self-hosted instance) via the `npx novu-sync` CLI or the `novuhq/actions-novu-sync` GitHub Action. Supports Express, Next.js, NestJS, Remix, SvelteKit, Nuxt, H3, AWS Lambda, and any node-runtime HTTP handler. The framework owns the workflow source-of-truth — the Dashboard editor stays in sync via a deterministic bridge URL.

- **Human URL:** [https://docs.novu.co/framework/overview](https://docs.novu.co/framework/overview)
- **Base URL:** `https://docs.novu.co/framework`

#### Tags

- Framework
- Code First
- Workflows
- TypeScript
- Next.js
- Express
- NestJS
- Remix
- SvelteKit
- Nuxt
- AWS Lambda

#### Properties

- [Documentation](https://docs.novu.co/framework/overview)
- [Quickstart](https://docs.novu.co/framework/quickstart/nextjs)
- [SDK](https://www.npmjs.com/package/@novu/framework)
- [C L I](https://www.npmjs.com/package/novu)
- [Code Examples](https://github.com/novuhq/novu-framework-nextjs-react-email-example)
- [Code Examples](https://github.com/novuhq/novu-framework-remix-example)
- [Code Examples](https://github.com/novuhq/novu-framework-nuxt-example)
- [Code Examples](https://github.com/novuhq/novu-framework-nuxt-vue-email-example)
- [Code Examples](https://github.com/novuhq/novu-framework-newsletter-app-example)
- [Postman Collection](collections/novu.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu MCP Server

Official Model Context Protocol server exposing the Novu REST API surface as MCP tools so AI agents (Claude Desktop, Cursor, agent frameworks) can trigger workflows, manage subscribers, list workflows, and inspect activity without bespoke wrapping. Distributed as a stdio server runnable via `npx @novu/mcp-server`.

- **Human URL:** [https://github.com/novuhq/novu-mcp-server](https://github.com/novuhq/novu-mcp-server)
- **Base URL:** `https://github.com/novuhq/novu-mcp-server`

#### Tags

- MCP
- AI Agents
- LLM
- Tools
- Notifications

#### Properties

- [Documentation](https://github.com/novuhq/novu-mcp-server)
- [Source Code](https://github.com/novuhq/novu-mcp-server)
- [Postman Collection](collections/novu.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://novu.co)
- [Portal](https://docs.novu.co)
- [Documentation](https://docs.novu.co)
- [Sign Up](https://web.novu.co/auth/signup)
- [Login](https://web.novu.co)
- [Pricing](https://novu.co/pricing)
- [Plans](plans/novu-plans-pricing.yml)
- [Fin Ops](finops/novu-finops.yml)
- [Rate Limits](rate-limits/novu-rate-limits.yml)
- [Blog](https://novu.co/blog)
- [Git Hub](https://github.com/novuhq)
- [GitHub Organization](https://github.com/novuhq)
- [GitHub Repository](https://github.com/novuhq/novu)
- [Source Code](https://github.com/novuhq/novu)
- [License](https://github.com/novuhq/novu/blob/next/LICENSE)
- [SDK](https://docs.novu.co/sdks/introduction)
- [C L I](https://docs.novu.co/community/run-in-local-machine)
- [Framework](https://docs.novu.co/framework/overview)
- [Inbox](https://docs.novu.co/platform/inbox/overview)
- [Integrations](https://docs.novu.co/platform/integrations)
- [Changelog](https://novu.co/changelog)
- [Release Notes](https://github.com/novuhq/novu/releases)
- [Status Page](https://status.novu.co)
- [Terms of Service](https://novu.co/terms)
- [Privacy Policy](https://novu.co/privacy)
- [Community](https://discord.gg/novu)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/novu)
- [YouTube](https://www.youtube.com/@novuhq)
- [L L Ms Txt](https://docs.novu.co/llms.txt)
- [Spectral Rules](rules/novu-spectral-rules.yml)
- [Vocabulary](vocabulary/novu-vocabulary.yml)
- [J S O N- L D](json-ld/novu-context.jsonld)
- [Tools](https://github.com/novuhq/novu-mcp-server)
- [Tools](https://github.com/novuhq/maily.to)
- [Tools](https://github.com/novuhq/actions-novu-sync)
- [Tools](https://github.com/novuhq/stripe-to-novu-webhooks)
- [Tools](https://github.com/novuhq/clerk-to-novu-webhooks)
- [Tools](https://github.com/novuhq/segment-to-novu-webhooks)
- [Tools](https://github.com/novuhq/community-k8s)
- [Tutorials](https://github.com/novuhq/inbox-playground)
- [Tutorials](https://github.com/novuhq/examples)
- [Tutorials](https://github.com/novuhq/awesome-novu)
- [Tutorials](https://docs.novu.co/guides)
- [Skills](https://github.com/novuhq/skills)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kinlane@gmail.com
