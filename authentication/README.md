# Authentication

Practical notes on authentication and authorization for modern web applications, APIs, and multi-tenant SaaS platforms.

This section focuses on production trade-offs: browser security, session management, token rotation, authorization boundaries, tenant context, membership validation, and tenant-aware access control.

---

## Articles

- [Session vs JWT Authentication](./session-vs-jwt-authentication.md)  
  Compare session-based and JWT-based authentication, including browser storage, XSS, CSRF, revocation, mobile clients, and multi-tenant concerns.

- [Refresh Token Rotation](./refresh-token-rotation.md)  
  Design secure long-lived sessions with short-lived access tokens, refresh-token rotation, token families, replay detection, logout, and revocation.

- [Role-Based Access Control (RBAC)](./rbac.md)  
  Design tenant-scoped roles, permissions, resource policies, support access, auditability, and authorization caching.

- [Multi-Tenant Authentication](./multi-tenant-authentication.md)  
  Explain how authentication, tenant context, membership validation, RBAC, and resource ownership work together in SaaS applications.

---

## Recommended Reading Order

1. [Session vs JWT Authentication](./session-vs-jwt-authentication.md)
2. [Refresh Token Rotation](./refresh-token-rotation.md)
3. [Role-Based Access Control (RBAC)](./rbac.md)
4. [Multi-Tenant Authentication](./multi-tenant-authentication.md)

---

## Related Sections

- [Multi-Tenant SaaS Architecture](../saas/multi-tenant-architecture.md)
