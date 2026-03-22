# OctoAcme Project Management Docs

This folder contains process documents for managing OctoAcme projects. Use this README to navigate the key workflows, roles, and tools adopted by the team to run projects smoothly and consistently.

---

## Project Management Process Summary

OctoAcme's project management process is organized as a lightweight lifecycle that moves work from initiation through planning, execution, release, and retrospective improvement. Projects start with a clear problem statement, defined stakeholders, success metrics, and a high-level timeline, then convert that into an actionable plan with a prioritized backlog, acceptance criteria, dependencies, milestones, and a definition of done. Across the lifecycle, the guiding principles are customer-first delivery, iterative increments, clear ownership, data-informed decisions, and psychological safety.

**Core principles:**
- **Customer-first**: Always prioritize end-user value.
- **Iterative delivery**: Ship in small, testable increments.
- **Clear ownership**: Each project has a defined PM and Product Lead.
- **Data-informed**: Use evidence and metrics to drive decisions.
- **Transparency**: Document everything; share updates regularly.

**High-level lifecycle:** Initiation → Planning → Execution → Release → Retrospective

### Key Roles

| Role | Primary Responsibility |
|------|----------------------|
| **Project Manager** | Coordinates delivery, schedules, risks, and communications |
| **Product Manager** | Defines outcomes, prioritizes the backlog, and measures success |
| **Developers** | Implement features; contribute to design, testing, and risk identification |
| **QA / Testing** | Validates quality and acceptance criteria |
| **Stakeholders** | Provide inputs and approvals |

### Communication Cadence

OctoAcme uses a structured communication rhythm: weekly PM–PdM syncs, twice-weekly team standups, monthly stakeholder updates, and demo/review sessions at the end of each sprint or milestone. Risk and dependency reviews are embedded into these cadences, with a clear escalation path from team-level triage up to sponsor-level escalation when needed.

### Quality Assurance

Quality is built into every phase rather than deferred to the end. Practices include small pull requests linked to issues, automated tests and linting in CI, and at least one peer approval before merge. Releases require completed acceptance criteria, passing CI, draft release notes, rollback planning, and post-deployment verification. After each sprint or release, retrospectives capture lessons learned and feed action items back into the backlog.

---

## Docs Index

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, roles, and artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to kick off a new project: charters, stakeholders, and success metrics |
| [Project Planning](octoacme-project-planning.md) | Scope, backlog, milestones, dependencies, and definition of done |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Sprint cadence, progress tracking, and delivery practices |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk registers, escalation paths, and communication templates |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checks, deployment steps, and post-release verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective formats, action item tracking, and improvement loops |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role |
