<!-- HU-STATUS TEMPLATE - do NOT remove the <!-- ... --> markers or the table headers.
     Your weekly grade is read AUTOMATICALLY from this file:
       09-week/hu-status/README.md  (inside YOUR fork). English. -->

# Weekly Status - Week 09

<!-- CONFIG-START - must match your profile repo (username/username) CONFIG -->
- FULL_NAME: Brahiam Yara
- GITHUB_USER: BrayanYara1
- TEAM: Group 2
- SPRINT_GOAL: Retrospective (Sep 28-Oct 04): add appointment-route test coverage/CI and document system UML diagrams.
<!-- CONFIG-END -->

## 1. User stories worked this week
| HU ID | Title | Status (todo/doing/done) | Evidence (PR or commit URL) |
|---|---|---|---|
| HU-002 | Login - sequence flow documented | doing | [UML diagrams](https://github.com/code-corhuila/appt-mgmt-docs/commit/ff3c4530583a96c7d90c9d8a453c7d4e5896c0fe) |
| HU-007 | Request Medical Appointment - availability tests, CI, and sequence flow | doing | [Merged appointment-test PR](https://github.com/BrayanYara1/ProyectoDistribuidos2026/pull/1); [UML diagrams](https://github.com/code-corhuila/appt-mgmt-docs/commit/ff3c4530583a96c7d90c9d8a453c7d4e5896c0fe) |
| HU-008 | Medication Management - data relationships documented | doing | [Healthcare data model](https://github.com/code-corhuila/appt-mgmt-docs/commit/ff3c4530583a96c7d90c9d8a453c7d4e5896c0fe) |

## 2. My individual contribution
- Added automated tests for appointment availability, including required-input and slot-availability cases, and introduced backend CI/coverage configuration in a PR that was merged.
- Added system-context, container, healthcare-data, login-sequence, and appointment-sequence diagrams.
- The tests and UML improve evidence for the listed HUs but do not establish that every acceptance criterion is complete; statuses therefore remain `doing`.

## 3. Blockers and risks
- Appointment creation checks availability before saving; the available evidence does not establish atomic reservation under concurrent requests.

## 4. Plan for next week
- Continue validating the remaining HU acceptance criteria and add integration coverage for untested paths.

## 5. Compliance self-check
- [x] Conventional Commits - `type(scope): summary`
- [ ] Per-environment HU branch + PR to that environment (hu-xxx-dev -> develop, ...)
- [ ] Testable acceptance criteria
- [x] Tests added/updated (unit / integration)
- [ ] DDD / hexagonal boundaries respected (domain has no I/O)
- [ ] No secrets; config via environment variables

## 6. Evidence links
- [Merged PR: appointment availability tests and backend CI](https://github.com/BrayanYara1/ProyectoDistribuidos2026/pull/1)
- [Salud Activa UML diagrams](https://github.com/code-corhuila/appt-mgmt-docs/commit/ff3c4530583a96c7d90c9d8a453c7d4e5896c0fe)
