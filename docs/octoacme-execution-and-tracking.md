# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (written by [Developers](octoacme-roles-and-personas.md#developers))
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Automated test coverage maintained by [QA/Test Automation Engineer](octoacme-roles-and-personas.md#qatest-automation-engineer)
- Security scanning in CI (monitored by [Security Engineer](octoacme-roles-and-personas.md#security-engineer))
- Manual QA for feature acceptance when needed
- Usability testing with [UX/UI Designer](octoacme-roles-and-personas.md#uxui-designer) for user-facing changes
- Documentation updated by [Technical Writer](octoacme-roles-and-personas.md#technical-writer) alongside feature work

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] [QA/Test Automation Engineer](octoacme-roles-and-personas.md#qatest-automation-engineer) integrated into sprint workflow
- [ ] [Security Engineer](octoacme-roles-and-personas.md#security-engineer) reviews high-risk changes
- [ ] [Technical Writer](octoacme-roles-and-personas.md#technical-writer) tracks documentation updates
- [ ] [UX/UI Designer](octoacme-roles-and-personas.md#uxui-designer) validates UI implementations (if applicable)
