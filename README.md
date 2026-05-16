# Andres Gonzalez
**Software Developer | Backend & Full-Stack | Distributed Systems, IAM, Cloud**

Software Developer focused on building production-ready backend and full-stack systems, with strong experience in identity platforms (IAM), distributed architectures, and enterprise integrations.

---

## Tech Stack

**Backend:** NestJS · ASP.NET Core · Spring Boot · Django  
**Languages:** Java · C# · TypeScript · Go · Python · C++  
**Architecture:** Microservices · Event-Driven · DDD · TDD · Clean Architecture  
**APIs & Messaging:** Kafka · gRPC · REST · GraphQL  
**Databases:** PostgreSQL · MongoDB · Oracle · SQL Server  
**Cloud & DevOps:** AWS · Azure · Docker · Jenkins · GitHub Actions · CI/CD  
**Security:** OAuth2 · OIDC · JWT · SAML · ADFS · Microsoft Entra ID  
**Frontend:** Vue.js · React · Next.js  
**AI Integration:** LLM API integration · Chatbot backend development

---

## Featured Projects

[Multi-Tenant IAM Backend Platform](https://github.com/aszender/Multi-Tenant-IAM-Backend-Platform)

Multi-tenant IAM backend focused on secure organization boundaries — tenant isolation, permission-based RBAC, refresh token rotation, membership modeling, auditability, and protected API access across multiple organizations.

Key focus areas

* Tenant isolation enforced across guards, services, and repository-level queries to prevent cross-tenant object access
* Permission-based RBAC with tenant-scoped memberships, roles, permissions, and explicit route authorization metadata
* Secure authentication flow with JWT access tokens, opaque refresh token rotation, hashed token storage, reuse denial, and expiration checks
* Audit events for authentication, tenant, membership, role, and permission-sensitive mutations
* Operational backend patterns including correlation IDs, safe error responses, strict validation, health/readiness checks, metrics, OpenAPI, and security-focused tests

`NestJS` · `TypeScript` · `PostgreSQL` · `Prisma` · `JWT` · `RBAC` · `Docker`

[Commerce Sync Platform](https://github.com/aszender/commerce-sync-platform)

Integration backend for syncing commerce orders across unreliable external platforms — webhook ingestion, scheduled polling, vendor connectors, rate limits, replayable failures, and canonical order mapping.

Key focus areas

* HMAC-validated webhook ingestion with durable inbox, Redis idempotency, and Kafka handoff for fast acknowledgement and async processing
* Scheduled polling with per-tenant Redis locks, durable sync watermarks, and out-of-order protection using remote update timestamps
* Vendor connector pattern hiding auth, pagination, rate limits, and provider-specific fields behind a stable canonical Order model
* Token-bucket rate limiting in atomic Redis Lua, bounded retries, and durable DLQ with auditable replay endpoint
* OpenTelemetry traces and metrics across API, worker, and scheduler roles, wired to Jaeger, Prometheus, and Grafana

`NestJS` · `TypeScript` · `PostgreSQL` · `Drizzle` · `Kafka` · `Redis` · `OpenTelemetry` · `Docker`

[PayFlow](https://github.com/aszender/Payflow)

Go payment gateway API modeling a regulated payment lifecycle — idempotent commands, state-machine transitions, bank failure handling, distributed rate limiting, and full audit history.

Key focus areas

* Idempotent payment processing with atomic database transactions for payment state, audit trail, and outbox event persistence
* Payment lifecycle modeled through explicit state transitions to prevent invalid status changes and duplicate side effects
* Circuit breaker and retry with exponential backoff and jitter for simulated bank API failures
* Transactional outbox pattern for reliable payment event delivery to Kafka
* Redis + Lua atomic scripts for distributed rate limiting and idempotency coordination

`Go` · `PostgreSQL` · `Redis` · `Lua` · `Kafka` · `Docker` · `chi` · `slog`

[AI SOC Investigator](https://github.com/aszender/AI-Soc-Alert)

Governed AI security investigation system — deterministic threat rules, LLM-assisted triage, prompt-injection guardrails, human approval gates, MCP tooling, and auditable incident response workflows.

Key focus areas

* Multi-agent supervisor pattern with triage, enrichment, and response agents under least-privilege permissions and token budget governance
* Deterministic rules engine for known threat patterns before LLM escalation, reducing unnecessary model calls and hallucination risk
* Input/output guardrails for prompt injection, unsafe actions, and unsupported security conclusions
* Human-in-the-loop approval gates for destructive actions with structured audit trail and trace IDs
* MCP server exposing investigation tools to AI hosts such as Claude Desktop, VS Code, and MCP Inspector

`Python` · `FastAPI` · `MCP` · `LLM Integration` · `Multi-Agent` · `Pydantic` · `Docker`

[Enterprise Microservices Platform](https://github.com/aszender/enterprise-microservices-platform)

Java/Spring microservices reference implementation focused on distributed consistency — transactional outbox, Kafka inbox/retry/DLQ, gRPC reservation flows, concurrency-safe inventory, and reproducible integration tests.

Key focus areas

* Transactional outbox for reliable Kafka publishing across products and orders without losing events after database commits
* Kafka inbox idempotency with retry/DLQ handling for safe event consumption under at-least-once delivery
* Concurrency-safe inventory reservations using atomic SQL updates, order-level idempotency, and PostgreSQL-backed tests
* Service-to-service communication using Kafka for asynchronous events and gRPC for synchronous reservation flows
* Production-style backend foundations: Flyway migrations, BigDecimal money handling, JWT security, OpenTelemetry, Prometheus, Grafana, and CI

`Java` · `Spring Boot` · `Apache Kafka` · `gRPC` · `PostgreSQL` · `Redis` · `Flyway` · `Testcontainers` · `OpenTelemetry` · `Docker`

## Engineering Approach

- Prioritize correctness, maintainability, and clarity over feature quantity  
- Make explicit design decisions with well-defined boundaries  
- Apply the same architectural and testing principles across multiple languages and stacks  

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andres-gonzalez-29132245/)



