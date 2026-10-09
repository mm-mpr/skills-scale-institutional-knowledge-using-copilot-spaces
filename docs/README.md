# OctoAcme Project Management

This folder is the entry point to OctoAcme’s project management process. OctoAcme aims to deliver customer value through small, testable increments, clear ownership, evidence-informed decisions, and a psychologically safe environment for feedback and learning.

## How projects work

Projects move through five connected phases: **initiation → planning → execution → release → retrospective**. Teams validate the need and success measures, turn approved work into a prioritized backlog and release plan, build and test iteratively, deploy with verification and rollback plans, then capture lessons as owned improvement actions.

## Roles and ways of working

- **Project Manager (PM):** coordinates plans, schedules, risks, dependencies, and communications.
- **Product Manager / Product Lead (PdM):** defines outcomes and success measures, prioritizes the backlog, and aligns stakeholders.
- **Developers:** estimate, design, implement, test, and review changes.
- **QA/Testing:** validates quality and acceptance criteria; stakeholders provide input and approvals.

Teams use project boards and shared project documentation as their source of truth. Standups surface progress and blockers; weekly delivery and PM/Product syncs review work, risks, and actions; demos and milestone reviews gather feedback. Stakeholder updates are sent on an agreed weekly, monthly, or milestone cadence. Escalations move from team triage to the PM, Product Lead, and sponsor as needed.

Quality is built into delivery: work has clear acceptance criteria and a Definition of Done; small pull requests link to issues and run automated tests, linting, and security scans in CI before review and merge. Unit, integration, smoke, and manual QA are used as appropriate. Releases require passing CI and security checks, satisfied acceptance criteria, release notes, and a rollback or mitigation plan.

## Process guides

### Follow the project lifecycle

1. **[Project management overview](./octoacme-project-management-overview.md)** — principles, roles, artifacts, and lifecycle.
2. **[Project initiation](./octoacme-project-initiation.md)** — validate the need, align stakeholders, define success measures, and decide whether to proceed.
3. **[Project planning](./octoacme-project-planning.md)** — create the backlog, estimates, Definition of Done, and release plan.
4. **[Execution and tracking](./octoacme-execution-and-tracking.md)** — manage delivery workflows, quality checks, reporting, and blockers.
5. **[Release and deployment](./octoacme-release-and-deployment.md)** — prepare, deploy, verify, communicate, and roll back releases.
6. **[Retrospective and continuous improvement](./octoacme-retrospective-and-continuous-improvement.md)** — review outcomes and track improvement actions.

### Cross-cutting guidance

- **[Risks and communication](./octoacme-risks-and-communication.md)** — risk registers, stakeholder updates, incident communications, and escalation.
- **[Roles and personas](./octoacme-roles-and-personas.md)** — responsibilities and communication expectations for project roles.

For project-specific questions, start with the project’s PM or Product Lead. These guides describe the shared process; confirm local team cadences and policies with them.
