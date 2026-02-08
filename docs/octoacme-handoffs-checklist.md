# OctoAcme — Team Handoffs Checklist

## Purpose
Standardize handoffs between roles to ensure clarity, reduce gaps, and maintain quality throughout the project lifecycle. Each handoff should include clear deliverables, acceptance criteria, and communication protocols.

---

## Business Analyst → Product Manager
**When**: After requirements gathering is complete
**Deliverables**:
- [ ] Business requirements document with stakeholder sign-off
- [ ] User workflows and process maps
- [ ] Success criteria and KPIs defined
- [ ] Stakeholder contact list and communication preferences

**Acceptance Criteria**:
- Requirements are clear, measurable, and prioritized
- Business value and impact are quantified
- All stakeholder concerns are documented

**Key Communication**: Requirements review meeting

See [Business Analyst](octoacme-roles-and-personas.md#business-analyst) and [Product Manager](octoacme-roles-and-personas.md#product-managers) roles.

---

## Product Manager → UX/UI Designer
**When**: After feature prioritization and before design work begins
**Deliverables**:
- [ ] Feature requirements and user stories
- [ ] Target user personas and use cases
- [ ] Success metrics for user experience
- [ ] Constraints (technical, timeline, scope)

**Acceptance Criteria**:
- Designer understands user needs and business goals
- Design scope and timeline are agreed upon
- Accessibility and responsive design requirements are clear

**Key Communication**: Design kickoff meeting

See [Product Manager](octoacme-roles-and-personas.md#product-managers) and [UX/UI Designer](octoacme-roles-and-personas.md#uxui-designer) roles.

---

## UX/UI Designer → Developers
**When**: After design approval and before implementation begins
**Deliverables**:
- [ ] Final mockups and prototypes
- [ ] Design specifications (spacing, colors, fonts, interactions)
- [ ] Design assets (icons, images, style guides)
- [ ] Interaction flows and edge case scenarios
- [ ] Accessibility requirements (WCAG compliance, keyboard navigation)

**Acceptance Criteria**:
- Developers understand design intent and implementation approach
- Technical feasibility has been validated
- All edge cases and error states are designed
- Design assets are in developer-friendly formats

**Key Communication**: Design handoff session with Q&A

See [UX/UI Designer](octoacme-roles-and-personas.md#uxui-designer) and [Developers](octoacme-roles-and-personas.md#developers) roles.

---

## Developers → QA/Test Automation Engineer
**When**: When feature is ready for testing (before marking as "Done")
**Deliverables**:
- [ ] Completed code with PR merged to test branch
- [ ] Unit tests written and passing
- [ ] Acceptance criteria reference
- [ ] Test environment setup instructions
- [ ] Known issues or limitations documented
- [ ] Demo or walkthrough of implemented feature

**Acceptance Criteria**:
- Feature meets all acceptance criteria
- Code is deployed to test environment
- QA has access to necessary test data
- Test automation hooks or test IDs are in place

**Key Communication**: Feature handoff and demo session

See [Developers](octoacme-roles-and-personas.md#developers) and [QA/Test Automation Engineer](octoacme-roles-and-personas.md#qatest-automation-engineer) roles.

---

## QA/Test Automation Engineer → Release Manager
**When**: After testing is complete and before release preparation
**Deliverables**:
- [ ] Test execution results and coverage report
- [ ] List of bugs found and their status (fixed, deferred, won't fix)
- [ ] Automated test suite updated for new features
- [ ] Regression test results
- [ ] QA signoff document
- [ ] Known issues for release notes

**Acceptance Criteria**:
- All critical and high-priority bugs are resolved
- Test coverage meets agreed thresholds
- No blocking issues remain
- Automated tests are integrated into CI/CD

**Key Communication**: QA signoff meeting

See [QA/Test Automation Engineer](octoacme-roles-and-personas.md#qatest-automation-engineer) and [Release Manager](octoacme-roles-and-personas.md#release-manager) roles.

---

## Security Engineer → Release Manager
**When**: After security review is complete and before release
**Deliverables**:
- [ ] Security review results
- [ ] Vulnerability scan reports
- [ ] Threat model (for significant features)
- [ ] Security test results
- [ ] Compliance checklist (if applicable)
- [ ] Security signoff document

**Acceptance Criteria**:
- All critical security vulnerabilities are addressed
- Security best practices are followed
- Compliance requirements are met
- Incident response plan is reviewed (if needed)

**Key Communication**: Security signoff meeting

See [Security Engineer](octoacme-roles-and-personas.md#security-engineer) and [Release Manager](octoacme-roles-and-personas.md#release-manager) roles.

---

## Developers → Technical Writer
**When**: Throughout development, with final handoff before release
**Deliverables**:
- [ ] Feature description and purpose
- [ ] API changes or new endpoints (with examples)
- [ ] Configuration options and defaults
- [ ] UI changes and new workflows
- [ ] Known limitations or breaking changes
- [ ] Migration guides (if applicable)

**Acceptance Criteria**:
- Documentation covers all user-facing changes
- Technical Writer has access to test environment
- Code comments and inline help are clear
- Examples and screenshots are accurate

**Key Communication**: Documentation review sessions throughout sprint

See [Developers](octoacme-roles-and-personas.md#developers) and [Technical Writer](octoacme-roles-and-personas.md#technical-writer) roles.

---

## Release Manager → Support/Operations
**When**: Before and after deployment
**Deliverables**:
- [ ] Release notes and changelog
- [ ] Deployment schedule and maintenance windows
- [ ] Rollback procedures
- [ ] Monitoring and alerting setup
- [ ] Known issues and workarounds
- [ ] Support runbook updates
- [ ] Post-deployment verification checklist

**Acceptance Criteria**:
- Support team understands what changed and why
- Monitoring is in place for new features
- Support documentation is updated
- Escalation paths are clear

**Key Communication**: Release briefing for support team

See [Release Manager](octoacme-roles-and-personas.md#release-manager) role.

---

## Technical Writer → All Stakeholders
**When**: When documentation is published
**Deliverables**:
- [ ] User-facing documentation published
- [ ] Release notes published
- [ ] Internal documentation updated
- [ ] Migration guides (if applicable)
- [ ] Documentation version aligned with product version

**Acceptance Criteria**:
- Documentation is accurate and accessible
- All stakeholders know where to find documentation
- Documentation follows style guide
- Feedback mechanism is in place

**Key Communication**: Documentation release announcement

See [Technical Writer](octoacme-roles-and-personas.md#technical-writer) role.

---

## General Handoff Best Practices

1. **Schedule handoffs in advance**: Don't treat handoffs as ad-hoc. Plan them as part of sprint planning.

2. **Use consistent templates**: Standardize handoff documents to reduce miscommunication.

3. **Allow time for questions**: Budget time for the receiving team to ask clarifying questions.

4. **Document decisions**: Record key decisions made during handoff in a shared location.

5. **Confirm understanding**: Receiving team should summarize their understanding before handoff is complete.

6. **Track handoff status**: Use project board or tracking system to show handoff completion.

7. **Measure handoff quality**: Track defects or rework caused by incomplete handoffs and improve process.

8. **Provide context, not just artifacts**: Explain the "why" behind decisions, not just the "what".

---

## Cross-Functional Ceremonies

Some handoffs happen naturally during team ceremonies:

- **Sprint Planning**: [Product Manager](octoacme-roles-and-personas.md#product-managers) → team (requirements, priorities)
- **Sprint Review/Demo**: [Developers](octoacme-roles-and-personas.md#developers) → stakeholders (completed work)
- **Release Planning**: [Release Manager](octoacme-roles-and-personas.md#release-manager) coordinates with all roles
- **Architecture Reviews**: [Developers](octoacme-roles-and-personas.md#developers) ↔ [Security Engineer](octoacme-roles-and-personas.md#security-engineer) ↔ [Business Analyst](octoacme-roles-and-personas.md#business-analyst)

See [Execution & Tracking](octoacme-execution-and-tracking.md) for more on team ceremonies.
