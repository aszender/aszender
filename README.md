# Andres Gonzalez
**Software Engineer | Backend & Full-Stack | Distributed Systems, IAM, Cloud**

Software engineer focused on building production-ready backend and full-stack systems, with strong experience in identity platforms (IAM), distributed architectures, and enterprise integrations.

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

### [Multi-Tenant-IAM-Backend-Platform](https://github.com/aszender/Multi-Tenant-IAM-Backend-Platform)
Enterprise IAM backend with strict tenant isolation — every query scoped by organization from JWT to repository layer, hierarchical RBAC, and transactional user provisioning.
 
**Key focus areas**
- Multi-tenant data isolation enforced at the repository level (compound org + resource queries, not just controller guards)
- Hierarchical RBAC with ranked roles (ORG_ADMIN → ORG_USER → READ_ONLY) and last-admin protection
- Atomic registration: organization + user + membership created in a single Prisma transaction
- Global exception filter with structured error responses and centralized error handling
 
`NestJS` · `TypeScript` · `PostgreSQL` · `Prisma` · `Docker`

---

### [PayFlow](https://github.com/aszender/Payflow)
Payment gateway API in Go simulating how fintech systems process bank payments — full transaction lifecycle with the reliability and auditability expected in regulated environments.

**Key focus areas**
- Idempotent payment processing with atomic DB transactions (payment + audit + outbox in one commit)
- Circuit breaker + retry with exponential backoff and jitter on bank API calls
- State machine enforcement with full audit trail per transaction
- Transactional outbox pattern for reliable event delivery to Kafka
- Redis + Lua atomic scripts for distributed rate limiting and idempotency coordination

`Go` · `PostgreSQL` · `Redis` · `Lua` · `Kafka` · `Docker` · `chi` · `slog`

---

### [Enterprise Microservices Platform](https://github.com/aszender/enterprise-microservices-platform)
Production-oriented microservices architecture showcasing enterprise integration patterns and full-stack system design.

**Key focus areas**
- Service-to-service communication using Kafka and gRPC
- Clear separation of domain, application, and infrastructure layers
- Designed around scalability, resilience, and maintainability trade-offs

`Java 17` · `Spring Boot 3` · `Apache Kafka` · `gRPC` · `Redis` · `PostgreSQL` · `Vue 3` · `React 18` · `Docker`

---

### [backend-Integration](https://github.com/aszender/backend-Integration)
Full-stack application focused on API robustness, validation, and consistent error handling.

**Key focus areas**
- JWT-based authentication and authorization
- Centralized error handling and input validation
- Practical backend–frontend integration

`Express` · `TypeScript` · `MongoDB` · `Next.js` · `Zod`

---

## Engineering Approach

- Prioritize correctness, maintainability, and clarity over feature quantity  
- Make explicit design decisions with well-defined boundaries  
- Apply the same architectural and testing principles across multiple languages and stacks  

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andres-gonzalez-29132245/)



