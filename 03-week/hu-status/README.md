<!-- HU-STATUS TEMPLATE - do NOT remove the <!-- ... --> markers or the table headers.
     Your weekly grade is read AUTOMATICALLY from this file:
       03-week/hu-status/README.md  (inside YOUR fork). English. -->

# Weekly Status - Week 03

<!-- CONFIG-START - must match your profile repo (username/username) CONFIG -->
- FULL_NAME: Brahiam Yara
- GITHUB_USER: BrayanYara1
- TEAM: Group 2
- SPRINT_GOAL: Retrospective (Aug 17-23): establish Salud Activa context, MVP 1.0 story breakdown, and the Turnos domain model.
<!-- CONFIG-END -->

## 1. User stories worked this week
| HU ID | Title | Status (todo/doing/done) | Evidence (PR or commit URL) |
|---|---|---|---|
| HU-007 | Request Medical Appointment - Turnos domain model, invariants, and events | doing | [Domain-model commit](https://github.com/BrayanYara1/ProyectoDistribuidos2026/commit/614d401aa0e25085f1c89ab3a2965959f96449ec) |

The HU-007 mapping is retrospective: the Aug 17 domain-model artifact predates the current HU numbering. `doing` records domain/design progress only; it does not claim the full appointment feature is complete.

## 2. My individual contribution
- Documented the Salud Activa context, candidate architecture, ADR-001, and MVP 1.0 story breakdown.
- Modeled the Turnos context, including its aggregate root, entities, invariants, and domain events.
- Documented data ownership and access-control boundaries for the MVP.

## 3. Blockers and risks
- No technical blocker is documented in the linked project evidence.

## 4. Plan for next week
- Refine the user-story backlog, acceptance criteria, traceability, architecture, and data model.

## 5. Compliance self-check
- [ ] Conventional Commits - `type(scope): summary`
- [ ] Per-environment HU branch + PR to that environment (hu-xxx-dev -> develop, ...)
- [ ] Testable acceptance criteria
- [ ] Tests added/updated (unit / integration)
- [ ] DDD / hexagonal boundaries respected (domain has no I/O)
- [ ] No secrets; config via environment variables

## 6. Evidence links
- [Turnos domain model](https://github.com/BrayanYara1/ProyectoDistribuidos2026/commit/614d401aa0e25085f1c89ab3a2965959f96449ec)
- [MVP 1.0 story breakdown and data ownership](https://github.com/BrayanYara1/ProyectoDistribuidos2026/commit/cc7cd39c4eb2ca7210aca5717c9603fd280a07bf)
- [Context map, ADR-001, and MVP backlog](https://github.com/BrayanYara1/ProyectoDistribuidos2026/commit/7ea77a08f16e9e92e2adb0aea8283f131de2456d)
- [Project context/domain documentation update](https://github.com/code-corhuila/appt-mgmt-docs/commit/f323b2bc6d43a4145c19eb2735dd5c42471251b1)
