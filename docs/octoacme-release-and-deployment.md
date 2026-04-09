# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

> **Role guidance:** See [Roles & Personas](octoacme-roles-and-personas.md) for release ownership. Key roles: **Project Manager** (release coordination), **QA Lead / Quality Engineer** (sign-off), **Tech Lead / Architect** (deployment approval), **Support / Customer Success** (customer communication), **Sponsor / Executive Stakeholder** (major release approval).

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- QA Lead / Quality Engineer sign-off received

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (QA Lead)
- [ ] Deploy to production (automated pipeline preferred; Tech Lead / Architect approves)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and Support / Customer Success (Project Manager)
- [ ] Support / Customer Success has updated customer-facing documentation

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items
  - Notify Support / Customer Success of customer impact immediately

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
