# Andres Gonzalez

**Software Developer | Backend & Distributed Systems | IAM, Cloud & Site Reliability**

Software Developer building and operating secure, reliable, and maintainable backend and full-stack systems. My experience includes distributed systems, identity platforms, enterprise integrations, cloud applications, observability, production troubleshooting, incident response, and operational automation.

I work across multiple languages and ecosystems, applying consistent development principles around correctness, security, reliability, testing, and clear architectural boundaries.

Based in Vancouver, Canada.

---

## Tech Stack

**Backend:** NestJS · ASP.NET Core · Spring Boot · Django  
**Languages:** Java · C# · TypeScript · Go · Python · C++  
**Architecture:** Microservices · Event-Driven · DDD · TDD · Clean Architecture  
**APIs & Messaging:** Kafka · gRPC · REST · GraphQL  
**Databases:** PostgreSQL · MongoDB · Oracle · SQL Server  
**Cloud & DevOps:** AWS · Azure · GCP · Terraform · Infrastructure as Code (IaC) · Docker · Kubernetes · Jenkins · GitHub Actions · CI/CD  
**Site Reliability:** Linux · Observability · Incident Response · Prometheus · Grafana · OpenTelemetry · Health Checks · Resilience Patterns  
**Security:** OAuth2 · OIDC · JWT · SAML · ADFS · Microsoft Entra ID  
**Frontend:** Vue.js · React · Next.js  
**AI Integration:** LLM API integration · Chatbot backend development

---

## Featured Projects

### [Reconduit](https://github.com/aszender/Reconduit)

Open-source, multi-tenant data reconciliation platform with durable processing, configurable matching, enterprise authentication, and an operations console.

- Durable ingestion with idempotency, retries, dead-letter handling, leases, and processing checkpoints
- Configurable schemas, mappings, matching rules, field authority, and explainable reconciliation evidence
- Operator workflows for investigating differences, recording decisions, and reviewing audit history
- Microsoft Entra multi-tenant authentication with verified admin-consent onboarding and application roles
- Privacy-safe OpenTelemetry, HTTP hardening, tenant-aware rate limiting, Docker, and reproducible CI
- 176 automated tests across backend, persistence, architecture, worker, and frontend layers

`C#` · `ASP.NET Core` · `.NET 10` · `PostgreSQL` · `React` · `TypeScript` · `Entra ID` · `OpenTelemetry` · `Docker`

---

### [PayFlow](https://github.com/aszender/Payflow)

Go payment backend modeling reliable payment processing under concurrency and external service failure.

- Idempotent payment commands and explicit lifecycle transitions
- Atomic persistence of payment state, audit history, and transactional outbox events
- Kafka publishing through a bounded-concurrency outbox worker
- Circuit breaker, exponential backoff, jitter, and simulated bank failure handling
- Prometheus metrics, a pre-provisioned Grafana dashboard, OpenTelemetry tracing through Jaeger, and health/readiness checks
- Kubernetes manifests for a local or single-node stack plus CI with integration tests, race detection, vulnerability analysis, and Docker build verification

`Go` · `PostgreSQL` · `Kafka` · `Redis` · `Kubernetes` · `Prometheus` · `Grafana` · `Jaeger` · `OpenTelemetry` · `Docker`

---

### [Enterprise Microservices Platform](https://github.com/aszender/enterprise-microservices-platform)

Java and Spring platform demonstrating consistency and failure handling across distributed commerce services.

- Product, order, and inventory bounded contexts
- Transactional outbox for reliable event publishing after database commits
- Idempotent Kafka inbox with retries and dead-letter handling
- Concurrency-safe inventory reservations backed by atomic database operations
- Kafka for asynchronous events and gRPC for synchronous reservation workflows
- PostgreSQL integration tests, Testcontainers, Flyway migrations, observability, and CI

`Java` · `Spring Boot` · `Kafka` · `gRPC` · `PostgreSQL` · `Redis` · `Flyway` · `Testcontainers`

---

### [Commerce Sync Platform](https://github.com/aszender/commerce-sync-platform)

Integration backend for synchronizing commerce orders across unreliable external providers.

- HMAC-validated webhook ingestion with durable inbox and idempotent processing
- Scheduled polling with distributed locks, durable watermarks, and out-of-order protection
- Provider abstraction for authentication, pagination, rate limits, and canonical order mapping
- Kafka-based asynchronous processing with bounded retries and replayable dead-letter records
- Redis and Lua token-bucket rate limiting
- Prometheus alerts, SLO targets, Grafana dashboards, and operational tracing across API, worker, and scheduler processes

`TypeScript` · `NestJS` · `PostgreSQL` · `Kafka` · `Redis` · `Prometheus` · `Grafana` · `OpenTelemetry` · `Docker`

---

### [Multi-Tenant IAM Platform](https://github.com/aszender/Multi-Tenant-IAM-Backend-Platform)

Tenant-scoped identity and access-management backend with explicit authorization and data-isolation boundaries.

- Organization isolation enforced across guards, services, and repository queries
- Permission-based RBAC with tenant-local memberships, roles, and route authorization
- Short-lived JWT access tokens and opaque refresh-token rotation
- Hashed token storage, expiration checks, revocation, and reuse denial
- Argon2 password hashing and security-sensitive audit events
- PostgreSQL-backed CI tests covering authorization and cross-tenant access attempts

`TypeScript` · `NestJS` · `PostgreSQL` · `Prisma` · `JWT` · `RBAC` · `Argon2` · `Docker`

---

### [AI SOC Investigator](https://github.com/aszender/AI-Soc-Alert)

Reference implementation for governed, LLM-assisted security alert investigation.

- Deterministic threat rules before LLM escalation
- Supervisor-led triage, enrichment, and response workflows
- Input guardrails for prompt injection and output validation for unsupported conclusions
- Token-budget governance and human approval gates for high-risk actions
- MCP tools for integration with compatible AI hosts
- Traceable investigation decisions exposed through FastAPI

`Python` · `FastAPI` · `MCP` · `LLM Integration` · `Pydantic` · `pytest` · `Docker`

---

## Development Approach

- Prioritize correctness, maintainability, reliability, and clarity over feature quantity  
- Make explicit design decisions with well-defined boundaries  
- Design failure behavior as deliberately as success behavior  
- Prefer idempotent operations and explicit state transitions  
- Keep distributed side effects observable and recoverable  
- Test business invariants, isolation, concurrency, and integration boundaries  
- Apply consistent architectural and testing principles across multiple languages and stacks  

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andres-gonzalez-29132245/)
