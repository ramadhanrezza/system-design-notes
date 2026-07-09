# System Design Notes

Practical system design and software architecture notes for modern backend engineers.

Unlike interview-focused repositories, this handbook emphasizes real-world engineering decisions, production-inspired architectures, trade-offs, and implementation considerations.

The goal is to explain not only what technologies and patterns exist, but why an engineering team would choose one approach over another.

---

## Published Articles

### SaaS

- [Multi-Tenant SaaS Architecture](./saas/multi-tenant-architecture.md)  
  Design tenant isolation, tenant-aware request flows, authentication boundaries, caching, background jobs, scaling strategies, and migration paths for SaaS platforms.

### Authentication

- [Session vs JWT Authentication](./authentication/session-vs-jwt-authentication.md)  
  Compare session-based and JWT-based authentication for browser applications, APIs, mobile clients, and multi-tenant SaaS platforms.

- [Refresh Token Rotation](./authentication/refresh-token-rotation.md)  
  Design secure long-lived authentication sessions using short-lived access tokens, refresh-token rotation, token families, replay detection, and revocation.

- [Role-Based Access Control (RBAC)](./authentication/rbac.md)  
  Design tenant-scoped roles, permissions, resource policies, support access, auditability, and authorization caching.

- [Multi-Tenant Authentication](./authentication/multi-tenant-authentication.md)  
  Explain how authentication, tenant context, membership validation, RBAC, and resource ownership work together in SaaS applications.

---

## Topics

This handbook will cover:

- Multi-Tenant SaaS
- Authentication and Authorization
- API Design
- Database Design
- Caching
- Event-Driven Architecture
- Docker and Deployment
- Scalability
- Distributed Systems
- Security
- System Design Case Studies

---

## Philosophy

Every article should answer four questions:

1. What problem does this solve?
2. How does it work?
3. What are the trade-offs?
4. When should you use it?

The handbook focuses on practical engineering judgment:

- Start with the problem and constraints.
- Compare realistic alternatives.
- Explain operational and security consequences.
- Prefer diagrams and concrete examples over abstract theory.
- Design for evolution instead of premature complexity.

---

## Repository Structure

```text
system-design-notes/
├── README.md
│
├── saas/
│   ├── README.md
│   └── multi-tenant-architecture.md
│
└── authentication/
    ├── README.md
    ├── session-vs-jwt-authentication.md
    ├── refresh-token-rotation.md
    ├── rbac.md
    └── multi-tenant-authentication.md
```

Only published articles are added to the repository navigation. New folders and documents are introduced when there is useful, complete content to publish.

---

## Suggested Reading Order

1. [Multi-Tenant SaaS Architecture](./saas/multi-tenant-architecture.md)
2. [Session vs JWT Authentication](./authentication/session-vs-jwt-authentication.md)
3. [Refresh Token Rotation](./authentication/refresh-token-rotation.md)
4. [Role-Based Access Control (RBAC)](./authentication/rbac.md)
5. [Multi-Tenant Authentication](./authentication/multi-tenant-authentication.md)

Future articles will expand from these foundations into tenant isolation, API design, database design, caching, event-driven systems, and deployment architecture.

---

## Version 1 Scope

Version 1 of this repository focuses on a small set of high-quality articles tied to real SaaS architecture decisions:

- Multi-tenancy
- Authentication strategy
- Refresh token rotation
- Tenant-scoped authorization
- Multi-tenant authentication flow

The goal is not to cover every system design topic at once. The goal is to publish clear, practical, and well-explained architecture notes that demonstrate engineering judgment.

---

## License

MIT
