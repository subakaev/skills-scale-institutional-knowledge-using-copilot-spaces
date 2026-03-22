# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Quality Assurance (QA) Lead

### Role Summary
The QA Lead defines the overall test strategy, coordinates manual and automated testing efforts, and serves as the final quality gate before releases. They champion quality standards across the project lifecycle.

### Responsibilities
- Define and maintain the test strategy (unit, integration, end-to-end, regression)
- Coordinate manual and automated QA activities across the team
- Review and approve acceptance criteria from a testability perspective
- Track and triage defects; communicate severity and priority to the team
- Sign off on releases from a quality standpoint
- Maintain the definition of done related to quality requirements

### Goals
- Ensure every release meets agreed quality and acceptance standards
- Reduce escaped defects (bugs found in production)
- Build a reliable, repeatable test automation suite
- Provide fast, actionable feedback to Developers

### Typical Communication
- Sprint planning: review stories for testability and add QA tasks
- Daily standups: surface blocking defects or test coverage gaps
- Pre-release review meetings with Developers and Release Manager
- Defect triage sessions with Developers and Product Managers

### Interactions with Existing Roles
- **Developers**: collaborate on testability, pair on test automation, review fixes for defects
- **Product Managers**: clarify acceptance criteria and edge cases before stories begin
- **Project Managers**: report testing status, flag quality risks to the risk register
- **Release Manager**: confirm release readiness and sign off on test results before deployment

---

## Release Manager

### Role Summary
The Release Manager plans, coordinates, and oversees the deployment of software to staging and production environments. They ensure releases are predictable, low-risk, and well-communicated.

### Responsibilities
- Own the release calendar and coordinate deployment windows
- Maintain release checklists and rollback plans
- Ensure all pre-release requirements are met before deployment
- Communicate release schedules and post-deploy status to stakeholders
- Facilitate post-release verification and incident triage if issues arise
- Manage feature flags and environment configurations during rollouts

### Goals
- Deliver releases on schedule with minimal disruption
- Reduce deployment risk through reliable processes and automation
- Maintain clear communication before, during, and after each release

### Typical Communication
- Release planning meetings with Developers, QA Lead, and Project Manager
- Pre-deployment go/no-go confirmation with QA Lead and relevant stakeholders
- Post-release announcements to stakeholders and support teams
- Incident communication during failed or partial releases

### Interactions with Existing Roles
- **Developers**: coordinate merge cutoffs, deployment steps, and hotfix procedures
- **QA Lead**: receive quality sign-off before promoting to production
- **Product Managers**: align on release scope, timing, and stakeholder messaging
- **Project Managers**: confirm milestones, dependencies, and deployment readiness

---

## Business Analyst

### Role Summary
The Business Analyst bridges business needs and technical implementation. They gather, document, and refine requirements to ensure the team builds the right solutions for the right problems.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Translate requirements into user stories, use cases, and acceptance criteria
- Facilitate workshops and discovery sessions to align stakeholders
- Validate that implemented solutions meet business requirements
- Maintain a shared understanding of scope across business and technical teams
- Identify and document assumptions, constraints, and dependencies

### Goals
- Ensure development work directly addresses documented business needs
- Reduce rework caused by unclear or incomplete requirements
- Improve alignment and shared understanding between stakeholders and the delivery team

### Typical Communication
- Stakeholder discovery and requirements workshops
- Story refinement sessions with Product Managers and Developers
- Regular check-ins with Project Managers on scope and progress
- Review of completed features against acceptance criteria before handoff to QA

### Interactions with Existing Roles
- **Developers**: clarify requirements, answer questions during implementation, validate delivered work
- **Product Managers**: collaborate on backlog refinement, success metrics, and user story quality
- **Project Managers**: surface scope changes, dependencies, and timeline impacts
- **QA Lead**: co-author acceptance criteria to ensure testability

---

## UX Designer

### Role Summary
The UX Designer advocates for the user experience across the product. They create wireframes, prototypes, and design specifications that guide development, and validate usability pre- and post-release.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity design assets
- Define interaction patterns and contribute to the design system
- Collaborate with Product Managers to shape feature direction
- Review implemented features for design fidelity and usability
- Document design decisions and rationale

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce usability issues discovered late in development
- Maintain consistency across the product through shared design standards

### Typical Communication
- Design reviews and critique sessions with Developers and Product Managers
- Usability testing readouts shared with the full team
- Design handoff documentation (specs, assets, annotations) during sprint planning
- Feedback on implemented features before QA sign-off

### Interactions with Existing Roles
- **Developers**: provide design specs, clarify interaction details, review built UI for fidelity
- **Product Managers**: align design direction with product vision and user needs
- **Project Managers**: flag design dependencies and timeline needs for research or iteration cycles
- **QA Lead**: share interaction expectations so test cases cover UX acceptance criteria

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to `octoacme-role-handoff-checklist.md` for guidance on when each persona is engaged across the project lifecycle.

