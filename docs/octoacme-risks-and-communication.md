# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

> **Role guidance:** See [Roles & Personas](octoacme-roles-and-personas.md) for ownership responsibilities. Key roles: **Project Manager** (owns Risk Register), **Tech Lead / Architect** (technical risks), **Engineering Manager** (resource/team risks), **QA Lead / Quality Engineer** (quality risks), **Sponsor / Executive Stakeholder** (escalation target for high-impact risks), **Support / Customer Success** (customer impact risks).

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner (see [Roles & Personas](octoacme-roles-and-personas.md) for role definitions)
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution (all roles contribute; PM facilitates)
- Assess: estimate impact and likelihood (PM + Tech Lead + QA Lead)
- Mitigate: reduced via actions, contingency plans (risk owner executes)
- Monitor: review at weekly syncs and update status (PM tracks; escalate to Sponsor if High/High)

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., Engineering Manager, Sponsor, Support / Customer Success)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level → PM → Product Manager → Engineering Manager → Sponsor / Executive Stakeholder
- For security incidents, follow the security incident runbook and notify Security on-call
- Customer-impacting issues: Support / Customer Success notified immediately; PM coordinates response

## Risk & Communication Checklist
- [ ] Risk Register created and shared with all relevant roles
- [ ] Risk owners assigned from [Roles & Personas](octoacme-roles-and-personas.md) (at minimum: PM, Tech Lead, QA Lead)
- [ ] Escalation path documented and shared with Sponsor / Executive Stakeholder
- [ ] Support / Customer Success informed of any customer-facing risks
- [ ] Engineering Manager notified of team capacity or staffing risks
- [ ] Weekly risk review cadence established
