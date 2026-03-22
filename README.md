# Sergejs Ponomarenko — Code Showcase

**Backend Developer | Python (FastAPI) & Java (Spring Boot) | Redis · S3 · PostgreSQL | Riga / EU Remote**  
Industry experience since January 2025 and ongoing.

This hub links to code samples and full projects I have been authorized to
share for employment purposes. Proprietary business logic and credentials
have been removed from all sanitized showcases.

---

## Projects

### Spotly — Travel & Location Discovery App
`Python` `FastAPI` `PostgreSQL` `PostGIS` `SQLAlchemy` `AWS S3` `Firebase` `APScheduler`

Backend for a mobile location discovery and AR souvenir collection app,
built against a database of ~2.7 million OpenStreetMap places. Sanitized
code showcase — selected systems only.

Highlights: zoom-adaptive map clustering (three-tier SQL + Python fallback),
dual-database architecture, JWT auth with token versioning, cross-database
AR souvenir claim with manual saga compensation.

→ [spotly-backend-showcase](https://github.com/SergejsP84/spotly-backend-showcase)

---

### Transcripto — Speech Processing & Call Analysis SaaS
`Python` `Quart` `PostgreSQL` `Redis` `Whisper` `pyannote` `GPT-4o-mini` `NVIDIA NeMo`

Backend for an AI-powered transcription and call quality analysis platform.
Sanitized code showcase — selected systems only.

Highlights: distributed worker pipeline (diarization → LLM analysis → PDF
reports) via chained Redis queues, pre-flight quota enforcement, subscription
system with resource rollover, multi-method auth (email + Firebase OAuth).

→ [transcripto-backend-showcase](https://github.com/SergejsP84/transcripto-backend-showcase)

---

### Spotly Admin Panel — Moderation & Audit Systems
`C#` `ASP.NET Core 8` `EF Core 8` `PostgreSQL` `ClosedXML`

Backend excerpts from a location-discovery platform admin panel. Sanitized
code showcase — two self-contained systems.

Highlights: append-only audit trail with snapshot diffing and 10 structured
event types, moderation statistics with per-user pivot tables and Excel
export, settings hot-reload from DB.

→ [.NET-showcase](https://github.com/SergejsP84/.NET-showcase)

---

### Mafia — Multiplayer Party Game
`Java 17` `Spring Boot 3.5` `MySQL` `Spring Security` `JWT` `MapStruct`

Personal project — a REST API backend for a multiplayer Mafia party game.
Full project, work in progress.

Highlights: automated phase transitions via scheduler, rule-based win
condition engine using predicates, thread-safe in-memory game state with
lightweight mutex for phase advancement, idempotent night action submission.

→ [Mafia_Backend](https://github.com/SergejsP84/Mafia_Backend)

---

### PropMan — Property Rental Management System *(Graduation Project)*
`Java 21` `Spring Boot 3.2` `MySQL` `Spring Security` `JWT` `Docker` `Apache POI`

Full-featured rental management platform with three user roles (Admin /
Manager / Tenant). Conceptually similar to Airbnb. Full project.

*Built as a graduation project — represents an earlier stage of development.
Given what I know now, I would replace the in-memory search intersection
with proper DB-side filtering and add async processing for the scheduled
lifecycle jobs.*

Highlights: booking availability with overlap detection pushed to DB,
multi-currency support with admin-managed exchange rates, automated booking
lifecycle scheduler, per-user JWT secret keys for independent session
invalidation.

→ [PropManProject](https://github.com/SergejsP84/PropManProject)

---

## Stack Summary

| | Technologies |
|---|---|
| **Languages** | Python, Java, C# |
| **Frameworks** | FastAPI, Quart, Spring Boot, ASP.NET Core |
| **Databases** | PostgreSQL, PostGIS, MySQL, SQLAlchemy (async) |
| **Auth** | JWT, Firebase Admin SDK, Spring Security |
| **Queues / Cache** | Redis |
| **Cloud / Storage** | AWS S3, Firebase |
| **AI / ML** | OpenAI GPT-4o-mini, Whisper, pyannote, NVIDIA NeMo |
| **Other** | APScheduler, Docker, Apache POI, ClosedXML |
