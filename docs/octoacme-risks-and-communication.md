# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
  - All team members can identify risks
  - [Security Engineer](octoacme-roles-and-personas.md#security-engineer) identifies security-specific risks
  - [Business Analyst](octoacme-roles-and-personas.md#business-analyst) identifies business process risks
- Assess: estimate impact and likelihood
  - Led by [Project Manager](octoacme-roles-and-personas.md#project-managers) with input from relevant subject matter experts
- Mitigate: reduced via actions, contingency plans
  - Mitigation plans assigned to appropriate role owners
- Monitor: review at weekly syncs and update status
  - [Project Manager](octoacme-roles-and-personas.md#project-managers) tracks and reports on risk status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
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
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify [Security Engineer](octoacme-roles-and-personas.md#security-engineer) and Security on-call
- For release issues, engage [Release Manager](octoacme-roles-and-personas.md#release-manager) immediately
