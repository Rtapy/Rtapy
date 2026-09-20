# Hasan Shirafkan

**Backend Engineer** · Python · Django · FastAPI

I design and build backend systems for complex business domains: marketplaces, digital health, and workforce management. I care about clear boundaries, transactional integrity, and APIs that are tested and documented.

```yaml
location: Tehran, Iran
current:  Sole backend developer, AKA Freelancer (freelance marketplace)
focus:    REST APIs, authentication & authorization, data pipelines, rule engines
education: B.Sc. Computer Engineering (Software), Islamic Azad University, Hamadan
```

---

## Selected Work

### AKA Freelancer · Freelance marketplace
*2026 – present*

Modular monolith in Django, split into bounded-context apps inside a shared monorepo.

- JWT + OTP authentication with Redis-backed state, HttpOnly refresh cookies, CSRF protection, and separate staff / marketplace authorization contexts
- Ownership-scoped profile, portfolio, taxonomy, and media APIs with validation, atomic transactions, and OpenAPI docs
- Test-driven development with pytest: auth, permissions, transaction rollbacks, API contracts

### Phoenix Life · Digital health platform
*2025 – 2026*

Django REST Framework backend with a separate FastAPI rule engine service.

- Refactored an untested legacy FastAPI monolith into a modular, clean-architecture service
- Ingestion pipelines for Excel, image, and PDF lab reports: AI-assisted OCR (OpenAI Vision API), canonical test mapping, reference-range normalization, duplicate prevention. Token consumption reduced by 15%
- YAML-driven rule engine with recursive AND/OR conditions and calculated indicators; structured validation, logging, Dockerized
- JWT authentication, role-based permissions, and laboratory-scoped data access

### Public Libraries Administration · Workforce management
*2024 – 2025*

- Django REST workflows for employees, regional units, shifts, leave and mission approvals, attendance, and daily reporting
- Face-recognition attendance (InsightFace / DeepFace): enrollment, quality-aware multi-frame matching, entry/exit recording. Replaced dedicated hardware across 100 branches, cutting rollout cost by ~80%
- Personnel-code JWT login with role- and regional-unit-scoped authorization; containerized with Docker and Gunicorn

---

## Stack

| Area | Tools |
| --- | --- |
| Languages & frameworks | `Python` `Django` `Django REST Framework` `FastAPI` |
| Data | `PostgreSQL` `Redis` |
| Infrastructure | `Docker` `Nginx` `Linux` `Gunicorn` `GitHub Actions` |
| Quality & docs | `pytest` `TDD` `OpenAPI (Swagger)` |

---

## Engineering Principles

- **Test first.** Auth, permissions, rollbacks, and API contracts are covered before they ship.
- **Explicit boundaries.** Bounded contexts and layered architecture keep services easy to reason about.
- **Atomic by default.** Transactions and duplicate prevention protect data integrity.
- **Secure by default.** HttpOnly cookies, CSRF protection, and scoped authorization from day one.
- **Documented contracts.** Every API ships with OpenAPI documentation.

---

## Contact

[LinkedIn](https://www.linkedin.com/in/hasan-shirafkan-387828292/) · [GitHub](https://github.com/Rtapy) · shirafkanzarinhasan@gmail.com
