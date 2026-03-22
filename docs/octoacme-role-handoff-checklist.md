# OctoAcme — Role Handoff & Responsibility Checklist

## Purpose
Clarify when each persona is engaged and what handoffs occur at each phase of a project.
Use this checklist to prevent gaps, reduce context-switching costs, and ensure accountability is always clear.

---

## Phase 1: Initiation

| Activity | Owner | Collaborators |
|---|---|---|
| Define problem statement and business case | Product Manager | Business Analyst, Project Manager |
| Identify and align stakeholders | Project Manager | Product Manager, Business Analyst |
| Gather initial requirements and constraints | Business Analyst | Product Manager, Stakeholders |
| Create Project One-pager | Project Manager | Product Manager, Business Analyst |
| Define high-level success metrics | Product Manager | Business Analyst |
| Identify initial UX/design research needs | UX Designer | Product Manager |
| Approve initiation gate (go/no-go) | Project Manager | Product Manager, Sponsor/Stakeholder |

### Checklist
- [ ] Problem statement documented and agreed by Product Manager and Business Analyst
- [ ] Stakeholder list complete and communication plan in place
- [ ] Initial requirements and constraints captured by Business Analyst
- [ ] UX Designer engaged if user-facing features are in scope
- [ ] Project One-pager approved by sponsor/stakeholder

---

## Phase 2: Planning

| Activity | Owner | Collaborators |
|---|---|---|
| Refine requirements into user stories | Business Analyst | Product Manager, Developers |
| Prioritize backlog | Product Manager | Business Analyst, Project Manager |
| Create wireframes and prototypes | UX Designer | Product Manager, Developers |
| Define test strategy | QA Lead | Developers, Product Manager |
| Estimate effort and set milestones | Project Manager | Developers, QA Lead |
| Create release plan and deployment calendar | Release Manager | Project Manager, QA Lead |
| Identify risks and dependencies | Project Manager | All roles |

### Checklist
- [ ] User stories have clear acceptance criteria (co-authored by Business Analyst and QA Lead)
- [ ] Wireframes or design specs available for all user-facing stories before development begins
- [ ] Test strategy documented and reviewed by QA Lead
- [ ] Release plan and deployment windows agreed with Release Manager
- [ ] Risk register updated with known technical and process risks
- [ ] All roles confirm capacity and availability for the sprint/milestone

---

## Phase 3: Execution

| Activity | Owner | Collaborators |
|---|---|---|
| Implement features | Developers | UX Designer (design review), QA Lead (testability) |
| Write and maintain tests | Developers | QA Lead |
| Conduct design reviews | UX Designer | Developers, Product Manager |
| Triage defects | QA Lead | Developers, Project Manager |
| Track progress and manage blockers | Project Manager | All roles |
| Validate requirements are met | Business Analyst | Developers, QA Lead |
| Update risk register | Project Manager | All roles |

### Checklist
- [ ] Developers implement against agreed acceptance criteria and design specs
- [ ] QA Lead reviews features for testability as they are built
- [ ] UX Designer reviews implemented UI before QA handoff
- [ ] Business Analyst validates delivered features against original requirements
- [ ] Defects are triaged and prioritized by QA Lead in collaboration with Project Manager
- [ ] Project Manager surfaces blockers or risks to stakeholders promptly

---

## Phase 4: Release

| Activity | Owner | Collaborators |
|---|---|---|
| Confirm release readiness (go/no-go) | Release Manager | QA Lead, Project Manager, Product Manager |
| Execute deployment | Release Manager | Developers |
| Run smoke tests and post-deploy verification | QA Lead | Developers, Release Manager |
| Announce release | Product Manager | Release Manager, Project Manager |
| Monitor for issues | Release Manager | Developers, QA Lead |
| Rollback if needed | Release Manager | Developers |

### Checklist
- [ ] All acceptance criteria met and confirmed by QA Lead
- [ ] Release notes drafted and reviewed by Product Manager
- [ ] Rollback plan documented and reviewed by Release Manager and Developers
- [ ] Deployment window scheduled and communicated to stakeholders
- [ ] Post-deploy verification tests passed
- [ ] Release announcement sent to stakeholders and support teams

---

## Phase 5: Close & Retrospective

| Activity | Owner | Collaborators |
|---|---|---|
| Facilitate retrospective | Project Manager | All roles |
| Capture action items | Project Manager | All roles |
| Review success metrics | Product Manager | Business Analyst |
| Archive project artifacts | Project Manager | All roles |

### Checklist
- [ ] Retrospective held and action items documented
- [ ] Success metrics reviewed against baseline (Product Manager + Business Analyst)
- [ ] Open defects triaged and backlogged or closed (QA Lead)
- [ ] Project artifacts archived in the project repo

---

## Quick Reference: Who to Engage and When

| Persona | Initiation | Planning | Execution | Release | Retro |
|---|---|---|---|---|---|
| Project Manager | ✅ Lead | ✅ Lead | ✅ Lead | ✅ Support | ✅ Lead |
| Product Manager | ✅ Lead | ✅ Lead | ✅ Support | ✅ Support | ✅ Support |
| Business Analyst | ✅ Support | ✅ Lead | ✅ Support | — | ✅ Support |
| UX Designer | ✅ Consult | ✅ Lead | ✅ Support | — | ✅ Consult |
| Developers | — | ✅ Support | ✅ Lead | ✅ Support | ✅ Support |
| QA Lead | — | ✅ Support | ✅ Lead | ✅ Lead | ✅ Support |
| Release Manager | — | ✅ Lead | ✅ Consult | ✅ Lead | ✅ Support |

> **Legend:** ✅ Lead = owns this activity; ✅ Support = actively contributes; ✅ Consult = provides input on request; — = typically not engaged

---

## Notes
- Handoff from one phase to the next requires explicit confirmation from the relevant lead (see phase checklists above).
- Roles may overlap on small teams — document clearly who is acting in each capacity.
- This checklist complements `octoacme-roles-and-personas.md` and the lifecycle described in `octoacme-project-management-overview.md`.
