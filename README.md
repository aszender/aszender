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

Production-oriented multi-tenant IAM backend focused on tenant isolation, permission-based RBAC, refresh token rotation, auditability, and secure API boundaries.

Key focus areas

* Tenant isolation enforced across guards, services, and repository-level queries, preventing cross-tenant object access.
* Permission-based RBAC with tenant-scoped memberships, roles, permissions, and explicit route authorization metadata.
* Secure authentication flow with JWT access tokens, opaque refresh token rotation, hashed token storage, reuse denial, and expiration checks.
* Audit events for authentication, tenant, membership, role, and permission-sensitive mutations.
* Operational backend patterns including correlation IDs, safe error responses, strict validation, health/readiness checks, metrics, OpenAPI, and security-focused tests.

`NestJS` · `TypeScript` · `PostgreSQL` · `Prisma` · `JWT` · `RBAC` · `Docker`

[Commerce Sync Platform](https://github.com/aszender/commerce-sync-platform)

Production-oriented integration backend for syncing orders between commerce platforms and downstream systems — webhook ingestion, scheduled polling, and resilient vendor sync patterns built around real-world failure modes.

Key focus areas

* HMAC-validated webhook ingestion with durable inbox, Redis idempotency, and Kafka handoff for fast acknowledgement and async processing
* Scheduled polling with per-tenant Redis locks, durable sync watermarks, and out-of-order protection via remote update timestamps
* Vendor connector pattern hiding auth, pagination, and rate limits behind a stable canonical Order mapping
* Token-bucket rate limiting in atomic Redis Lua, bounded retries, and durable DLQ with auditable replay endpoint
* OpenTelemetry traces and metrics across API, worker, and scheduler roles, wired to Jaeger, Prometheus, and Grafana

`NestJS` · `TypeScript` · `PostgreSQL` · `Drizzle` · `Kafka` · `Redis` · `OpenTelemetry` · `Docker`

[PayFlow](https://github.com/aszender/Payflow)

Payment gateway API in Go simulating how fintech systems process bank payments — full transaction lifecycle with the reliability and auditability expected in regulated environments.

Key focus areas

* Idempotent payment processing with atomic DB transactions (payment + audit + outbox in one commit)
* Circuit breaker + retry with exponential backoff and jitter on bank API calls
* State machine enforcement with full audit trail per transaction
* Transactional outbox pattern for reliable event delivery to Kafka
* Redis + Lua atomic scripts for distributed rate limiting and idempotency coordination

`Go` · `PostgreSQL` · `Redis` · `Lua` · `Kafka` · `Docker` · `chi` · `slog`

[AI SOC Investigator](https://github.com/aszender/AI-Soc-Alert)

Multi-agent AI system for autonomous security alert investigation — deterministic rules for known threats, LLM-powered triage for novel attacks, governed response playbook generation, and MCP tool exposure for AI host integration.

Key focus areas

* Multi-agent supervisor pattern with triage, enrichment, and response agents under least-privilege permissions and token budget governance
* Deterministic rules engine for known patterns before LLM escalation, with input/output guardrails for prompt injection and hallucination detection
* Human-in-the-loop approval gates for destructive actions with structured audit trail and trace IDs
* MCP server exposing investigation tools to AI hosts (Claude Desktop, VS Code, MCP Inspector)

`Python` · `FastAPI` · `MCP` · `LLM Integration` · `Multi-Agent` · `Pydantic` · `Docker`

[Enterprise Microservices Platform](https://github.com/aszender/enterprise-microservices-platform)

Production-oriented microservices architecture showcasing enterprise integration patterns and full-stack system design.

Key focus areas

* Service-to-service communication using Kafka and gRPC
* Clear separation of domain, application, and infrastructure layers
* Designed around scalability, resilience, and maintainability trade-offs

`Java 17` · `Spring Boot 3` · `Apache Kafka` · `gRPC` · `Redis` · `PostgreSQL` · `Vue 3` · `React 18` · `Docker`

## Engineering Approach

- Prioritize correctness, maintainability, and clarity over feature quantity  
- Make explicit design decisions with well-defined boundaries  
- Apply the same architectural and testing principles across multiple languages and stacks  

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andres-gonzalez-29132245/)



