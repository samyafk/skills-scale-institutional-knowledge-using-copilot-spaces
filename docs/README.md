# OctoAcme Project Management Docs

This `docs/` folder centralizes OctoAcme project management knowledge so teams can run projects consistently, onboard faster, and keep a shared source of truth for delivery decisions.

## Workflow and lifecycle
- **Initiation:** define the problem, success metrics, stakeholders, timeline, risks, and go/no-go decision.
- **Planning:** run kickoff, prioritize and estimate backlog items, define acceptance criteria/Definition of Done, and map dependencies.
- **Execution:** deliver in small increments using board states such as Backlog, Ready, In Progress, In Review, QA, and Done.
- **Release:** confirm readiness, deploy safely, verify outcomes, and communicate release status.
- **Retrospective:** capture lessons learned and track improvement actions with owners and due dates.

## Roles and ownership
- **Project Manager (PM):** delivery coordination, timelines, risk/dependency tracking, and stakeholder communication.
- **Product Manager (PdM):** customer outcomes, prioritization, success metrics, and value validation.
- **Developers:** implementation, testing, code review collaboration, and technical risk mitigation.
- **QA/Testing:** validate acceptance criteria and release readiness.
- **Stakeholders/Sponsors:** provide input, decisions, and approvals.

## Communication and escalation
- Team cadence includes standups, weekly delivery/PM-PdM syncs, sprint or milestone demos, and monthly stakeholder updates.
- Risks and blockers are tracked in a risk register and status updates.
- Escalation path is **team triage → PM → Product Lead → Sponsor**, with security incidents routed to security on-call.

## Quality, release safeguards, and continuous improvement
- Quality expectations include unit tests for new logic, integration tests when needed, end-to-end smoke tests for critical flows, CI lint/testing, security scanning, and manual QA where appropriate.
- Release safeguards include completed acceptance criteria, passing CI/security checks, release notes, rollback planning, staging verification, and post-deploy checks.
- Retrospectives after sprints, releases, or incidents drive continuous improvement by turning learnings into backlog action items.
