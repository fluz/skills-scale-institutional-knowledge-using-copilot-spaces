# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (verified by [Security Engineer](octoacme-roles-and-personas.md#security-engineer))
- Release notes drafted (by [Technical Writer](octoacme-roles-and-personas.md#technical-writer) in collaboration with [Release Manager](octoacme-roles-and-personas.md#release-manager))
- Rollback / mitigation plan documented
- Smoke tests prepared and validated (by [QA/Test Automation Engineer](octoacme-roles-and-personas.md#qatest-automation-engineer))
- [Release Manager](octoacme-roles-and-personas.md#release-manager) confirms release readiness

## Deployment Checklist
Coordinated by [Release Manager](octoacme-roles-and-personas.md#release-manager):
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (by [QA/Test Automation Engineer](octoacme-roles-and-personas.md#qatest-automation-engineer))
- [ ] Security signoff obtained (by [Security Engineer](octoacme-roles-and-personas.md#security-engineer))
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (by [Release Manager](octoacme-roles-and-personas.md#release-manager))
- [ ] Documentation published (by [Technical Writer](octoacme-roles-and-personas.md#technical-writer))

## Rollback & Incident Playbook
Managed by [Release Manager](octoacme-roles-and-personas.md#release-manager) with support from [Security Engineer](octoacme-roles-and-personas.md#security-engineer) (if security-related):
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items
  - Coordinate with [QA/Test Automation Engineer](octoacme-roles-and-personas.md#qatest-automation-engineer) for post-rollback validation

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
