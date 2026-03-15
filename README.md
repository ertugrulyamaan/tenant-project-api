# Tenant Project API

A backend system designed to explore and demonstrate core concepts of multi-tenant SaaS architecture using NestJS.

This project focuses on building a tenant-aware collaboration backend where multiple organizations can securely manage projects and members within a shared infrastructure.

⚠️ This repository is currently in early development stage.

---

## Purpose

Modern SaaS platforms must support multiple organizations (tenants) operating on the same system while ensuring:

- strict data isolation
- secure authentication and authorization
- scalable backend design
- maintainable domain boundaries

The goal of this project is to simulate how a real SaaS backend core is engineered rather than building a simple CRUD application.

---

## Initial Scope (Phase 1)

- User authentication (JWT)
- Tenant creation and membership
- Tenant-scoped project management
- Role-based access control (basic)
- PostgreSQL-backed data layer
- Clean modular NestJS architecture

---

## Out of Scope (for now)

To maintain focus and avoid over-engineering, the following are intentionally excluded in early phases:

- Multi-database tenancy
- Billing systems
- Notification services
- Real-time communication
- AI features
- Advanced distributed infrastructure
- Full audit platform

These may be explored in later iterations.

---

## Development Status

This project is being built incrementally with a focus on:

- clear architectural decisions
- production-oriented backend thinking
- testable and observable design
- iterative improvement

Current stage:  
**Project initialization and core infrastructure setup**

---

## Tech Stack (Planned)

- NestJS
- TypeScript
- PostgreSQL
- Prisma
- JWT Authentication
- Argon2
- Jest
- Prometheus metrics
- Docker (local development)

---

## Philosophy

This repository prioritizes:

- system design clarity over rapid feature delivery
- correctness over complexity
- engineering depth over demo completeness

---

## Roadmap (Early)

- [ ] Project bootstrap
- [ ] Database schema & Prisma setup
- [ ] Authentication module
- [ ] Tenant domain
- [ ] Membership model
- [ ] Project domain
- [ ] Authorization rules
- [ ] Observability basics
- [ ] Integration tests
- [ ] Documentation refinement

---

## License

For educational and portfolio purposes.