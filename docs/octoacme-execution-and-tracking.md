# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

> **Role guidance:** See [Roles & Personas](octoacme-roles-and-personas.md) for who owns each execution activity. Key roles: **Project Manager** (tracks progress, escalates blockers), **Tech Lead / Architect** (technical decisions), **QA Lead / Quality Engineer** (test execution), **Engineering Manager** (team health), **Developers** (implementation), **Design / UX** (design QA).

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks (PM + Product Manager + Tech Lead + Engineering Manager)
- Demo/Review at the end of each sprint or milestone (Team + Stakeholders + Support / Customer Success)

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed (QA Lead / Quality Engineer owns sign-off)
- Design QA: Design / UX reviews implemented features before they are marked Done

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Manager, Engineering Manager, and dependent teams
- Level 3: Sponsor / Executive Stakeholder escalation for business-impacting issues (see [Roles & Personas](octoacme-roles-and-personas.md))

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled (include Support / Customer Success as needed)
- [ ] Risk register updated weekly (Project Manager)
- [ ] QA Lead engaged and test execution tracked
- [ ] Design / UX design QA scheduled for completed features
