# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **See also:** The [Project Management Overview](octoacme-project-management-overview.md) provides a high-level summary of Core Roles. Each process document ([Initiation](octoacme-project-initiation.md), [Planning](octoacme-project-planning.md), [Execution & Tracking](octoacme-execution-and-tracking.md), [Risk Management & Communication](octoacme-risks-and-communication.md), [Retrospective](octoacme-retrospective-and-continuous-improvement.md), [Release & Deployment](octoacme-release-and-deployment.md)) references relevant roles from this document.

---

## Role Index

| Role | Short Description |
|---|---|
| [Developers](#developers) | Implement and deliver software features |
| [Product Managers](#product-managers) | Define what to build and measure outcomes |
| [Project Managers](#project-managers) | Coordinate delivery, schedules, and communications |
| [Engineering Manager](#engineering-manager) | Lead and support the engineering team; bridge delivery and people management |
| [Design / UX](#design--ux) | Define user experience, interaction patterns, and visual design |
| [QA Lead / Quality Engineer](#qa-lead--quality-engineer) | Own quality strategy, test coverage, and acceptance validation |
| [Tech Lead / Architect](#tech-lead--architect) | Set technical direction and ensure architectural soundness |
| [Support / Customer Success](#support--customer-success) | Represent customer feedback, manage escalations, and drive adoption |
| [Sponsor / Executive Stakeholder](#sponsor--executive-stakeholder) | Provide executive sponsorship, funding, and strategic alignment |

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

### Interaction with Other Roles
- **Tech Lead / Architect:** Receive technical direction, coding standards, and architectural guidance; escalate design ambiguities.
- **Engineering Manager:** Discuss workload, career growth, and team blockers.
- **QA Lead / Quality Engineer:** Collaborate on test strategies and fix defects surfaced in QA.
- **Product Manager:** Clarify acceptance criteria and flag scope or feasibility concerns.
- **Project Manager:** Provide estimates, status updates, and flag blockers for escalation.
- **Design / UX:** Implement designs, request clarification on edge cases, and provide feedback on feasibility.

### Handoff & Responsibility
- Developers hand off completed work to QA Lead for acceptance testing.
- Before handing off, the Developer ensures CI passes, documentation is updated, and the PR is reviewed and approved.

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Write and maintain acceptance criteria for backlog items

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interaction with Other Roles
- **Project Manager:** Align on scope, timeline, and priorities; co-own the project roadmap.
- **Tech Lead / Architect:** Discuss feasibility, trade-offs, and technical dependencies.
- **Design / UX:** Collaborate on user research, wireframes, and feature specs.
- **Sponsor / Executive Stakeholder:** Brief on strategic progress, risk, and outcomes.
- **Support / Customer Success:** Gather customer feedback and bug reports to inform the backlog.
- **QA Lead / Quality Engineer:** Define acceptance criteria and review test coverage for new features.

### Handoff & Responsibility
- Product Manager hands off prioritized backlog items (with acceptance criteria) to the Project Manager and Tech Lead for planning.
- Validates delivered features against success metrics before sign-off.

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

### Interaction with Other Roles
- **Product Manager:** Align on scope and priorities; escalate trade-off decisions.
- **Engineering Manager:** Coordinate team capacity, staffing, and blockers.
- **Tech Lead / Architect:** Track technical risks and dependencies.
- **Sponsor / Executive Stakeholder:** Provide progress updates and escalate business-impacting risks.
- **QA Lead / Quality Engineer:** Ensure testing milestones are planned and tracked.
- **Support / Customer Success:** Communicate release timelines and known issues.

### Handoff & Responsibility
- Project Manager owns the Risk Register and escalation paths.
- Hands off release readiness confirmation to the Release team after all checklist items are complete.
- Closes the project by facilitating the retrospective and archiving project artifacts.

---

## Engineering Manager

### Role Summary
Engineering Managers lead and support their engineering teams, balancing people management with technical delivery. They act as the bridge between the delivery team and organizational leadership, ensuring engineers have what they need to succeed.

### Responsibilities
- Manage engineer performance, growth, and well-being
- Allocate team capacity and manage hiring or contractor needs
- Remove organizational blockers and escalate resource constraints
- Partner with Project Managers on team-level planning and risk
- Represent the engineering team in cross-functional discussions
- Foster a culture of quality, collaboration, and continuous improvement

### Goals
- Build a high-performing, healthy, and engaged engineering team
- Ensure sustainable delivery velocity
- Align team capabilities with project and product needs

### Typical Communication
- 1:1s with direct reports (weekly or biweekly)
- Engineering team meetings and planning sessions
- Cross-functional syncs with PM, Product Manager, and Tech Lead

### Interaction with Other Roles
- **Project Manager:** Share team capacity, flag staffing risks, and escalate delivery blockers that require organizational action.
- **Tech Lead / Architect:** Align on technical direction and ensure engineers have the support needed to execute.
- **Developers:** Provide career coaching, performance feedback, and unblock day-to-day obstacles.
- **Product Manager:** Represent engineering needs and constraints in roadmap discussions.
- **Sponsor / Executive Stakeholder:** Escalate critical team or resource risks that require executive action.

### Handoff & Responsibility
- Engineering Manager ensures team capacity is confirmed before a project enters the Planning phase.
- Coordinates staffing changes and communicates impact to the Project Manager promptly.

---

## Design / UX

### Role Summary
Design and UX professionals define how users interact with OctoAcme products. They translate user needs and business requirements into intuitive workflows, wireframes, prototypes, and visual designs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define interaction patterns and information architecture
- Maintain a design system and ensure visual consistency
- Collaborate with Product Managers to validate user needs
- Review implemented features against design specifications

### Goals
- Deliver user experiences that are intuitive, accessible, and delightful
- Reduce rework through early design validation
- Ensure design and engineering alignment throughout delivery

### Typical Communication
- Design reviews with engineering and product
- Usability test reports and research summaries
- Design handoff notes and specification files (e.g., Figma)

### Interaction with Other Roles
- **Product Manager:** Collaborate on problem framing, user stories, and feature prioritization.
- **Tech Lead / Architect:** Discuss technical constraints that impact design feasibility.
- **Developers:** Hand off finalized designs with annotations; clarify edge cases during implementation.
- **QA Lead / Quality Engineer:** Provide design specs for QA validation of visual and interaction requirements.
- **Support / Customer Success:** Incorporate customer feedback and pain points into design iterations.

### Handoff & Responsibility
- Design / UX hands off finalized designs to Developers at the start of the implementation sprint.
- Designs are considered ready for handoff when they have passed an internal design review and edge cases are documented.
- Conducts a design QA pass before a feature is marked done.

---

## QA Lead / Quality Engineer

### Role Summary
The QA Lead owns the quality strategy for the project, ensuring that features meet acceptance criteria, are free of critical defects, and are production-ready. They partner closely with Developers and Product Managers throughout the delivery lifecycle.

### Responsibilities
- Define the test strategy, test plan, and acceptance criteria validation approach
- Design and maintain automated and manual test suites
- Execute functional, regression, integration, and smoke tests
- Track and triage defects; prioritize with the Product Manager and Tech Lead
- Validate that Definition of Done criteria are met before releases
- Champion quality practices across the team (shift-left testing)

### Goals
- Prevent defects from reaching production
- Build confidence in every release through comprehensive test coverage
- Continuously improve the test suite and quality process

### Typical Communication
- Defect reports and test execution summaries
- Test plan reviews with PM and Tech Lead
- QA status updates in sprint reviews and release readiness meetings

### Interaction with Other Roles
- **Developers:** Collaborate on unit and integration test strategies; triage and verify defect fixes.
- **Tech Lead / Architect:** Align on testability requirements and CI/CD quality gates.
- **Product Manager:** Validate acceptance criteria and escalate ambiguous requirements.
- **Project Manager:** Report test status and flag quality risks in the Risk Register.
- **Design / UX:** Receive design specs for visual regression and interaction testing.
- **Support / Customer Success:** Receive bug reports and validate fixes against reported customer issues.

### Handoff & Responsibility
- QA Lead approves a release when all acceptance criteria are met and critical defects are resolved.
- Provides a test sign-off report to the Project Manager before production deployment.
- Hands off known issues documentation to Support / Customer Success after each release.

---

## Tech Lead / Architect

### Role Summary
The Tech Lead or Architect sets the technical direction for the project, ensures architectural soundness, and guides the engineering team in making sound design and implementation decisions. They balance short-term delivery with long-term maintainability.

### Responsibilities
- Define and communicate the technical architecture and design patterns
- Lead technical design reviews and spike investigations
- Establish and enforce coding standards, security practices, and non-functional requirements
- Identify and mitigate technical risks and dependencies
- Support Developers in breaking down complex problems
- Evaluate build vs. buy trade-offs and third-party integrations

### Goals
- Deliver a scalable, secure, and maintainable architecture
- Reduce technical debt and prevent architectural drift
- Enable the team to move fast while maintaining quality

### Typical Communication
- Architecture decision records (ADRs) and technical design docs
- Code review feedback and pair programming sessions
- Weekly technical sync with Engineering Manager and Project Manager

### Interaction with Other Roles
- **Engineering Manager:** Align on team skills, growth areas, and technical staffing needs.
- **Developers:** Provide architectural guidance, code review feedback, and mentorship.
- **Product Manager:** Advise on technical feasibility and trade-offs during backlog refinement.
- **QA Lead / Quality Engineer:** Define testability requirements and CI/CD quality gates.
- **Project Manager:** Communicate technical risks and dependencies; provide effort estimates.
- **Design / UX:** Assess technical feasibility of proposed designs and interaction patterns.

### Handoff & Responsibility
- Tech Lead approves the technical design before development begins (design review gate).
- Signs off on architectural changes before merging to the main branch.
- Hands off architectural documentation to the Engineering Manager for team onboarding.

---

## Support / Customer Success

### Role Summary
Support and Customer Success professionals act as the voice of the customer within the project team. They manage customer-facing communications, escalate production issues, and ensure customers adopt and succeed with delivered features.

### Responsibilities
- Triage and escalate customer-reported bugs and feature requests
- Create and maintain customer-facing documentation, FAQs, and release notes
- Communicate upcoming changes and release timelines to customers
- Gather feedback from customers and relay actionable insights to the Product Manager
- Coordinate with the QA Lead to validate fixes for customer-reported issues
- Track customer satisfaction metrics and adoption of new features

### Goals
- Ensure customers are successful with OctoAcme products
- Minimize customer-impacting downtime and unresolved issues
- Provide a clear, proactive communication channel between customers and the product team

### Typical Communication
- Customer release announcement emails and in-app notifications
- Weekly sync with Product Manager and Project Manager
- Defect escalations to QA Lead and engineering team

### Interaction with Other Roles
- **Product Manager:** Provide customer feedback and bug reports to inform backlog prioritization.
- **Project Manager:** Receive release timelines and known issues to prepare customers.
- **QA Lead / Quality Engineer:** Submit customer-reported bugs; validate that customer issues are resolved in upcoming releases.
- **Developers:** Escalate critical production issues that require immediate attention.
- **Design / UX:** Share customer usability feedback to inform design improvements.

### Handoff & Responsibility
- Support / Customer Success receives a release summary and known issues list from the Project Manager before each release.
- After release, Support validates that customer-facing documentation is updated and communicates changes to customers.
- Escalates unresolved production issues to the Project Manager for Risk Register tracking.

---

## Sponsor / Executive Stakeholder

### Role Summary
The Sponsor or Executive Stakeholder provides strategic alignment, executive sponsorship, and funding for the project. They are accountable for the business outcomes and remove organizational barriers that the project team cannot resolve independently.

### Responsibilities
- Champion the project at the executive level and secure necessary funding and resources
- Define and communicate strategic priorities and success criteria
- Approve major scope changes, budget overruns, or timeline extensions
- Remove high-level organizational blockers
- Receive and act on escalated risks that have business-wide impact
- Sign off on project closure and retrospective outcomes

### Goals
- Ensure the project delivers measurable business value
- Protect the project from conflicting organizational priorities
- Maintain executive visibility into project health and risks

### Typical Communication
- Monthly project health updates from the Project Manager
- Escalation briefings for high-impact risks or blockers
- Executive summary in release notes and project closure reports

### Interaction with Other Roles
- **Project Manager:** Receive regular status updates; authorize escalated decisions and scope changes.
- **Product Manager:** Align on strategic priorities and validate that outcomes match business goals.
- **Engineering Manager:** Discuss team capacity risks that require executive intervention.
- **Support / Customer Success:** Review customer satisfaction outcomes and escalated incidents.

### Handoff & Responsibility
- The Sponsor formally authorizes the project to proceed at the end of the Initiation phase (go/no-go decision).
- Approves any changes to project scope, budget, or timeline that exceed the Project Manager's authority.
- Signs off on project closure after reviewing the final retrospective and outcome metrics.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When assigning ownership in a checklist or process document, refer back to this document to identify the appropriate role.

