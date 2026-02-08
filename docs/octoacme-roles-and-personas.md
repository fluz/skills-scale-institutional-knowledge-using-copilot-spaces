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

## UX/UI Designer

### Role Summary
Responsible for user research, interface design, user flows, and ensuring usability of features. UX/UI Designers focus on creating intuitive and effective user experiences.

### Responsibilities
- Conduct user research and usability studies
- Develop wireframes, mockups, and prototypes
- Collaborate with Product Manager on feature requirements
- Work with Developers to hand off designs and clarify intent
- Create and maintain design systems and style guides
- Validate designs through user testing and iteration

### Goals
- Deliver intuitive, accessible, and visually appealing interfaces
- Ensure consistency across product experience
- Reduce user friction and improve satisfaction metrics

### Typical Communication
- Design reviews with Product Manager and Developers
- Handoff sessions with Development team
- User research findings and design rationale documentation
- Participation in sprint planning and backlog refinement

### Interactions with Other Roles
- **Product Manager**: Partners in ideation, feature definition, and validation
- **Developers**: Provides design assets and clarifies implementation details
- **QA/Test Automation Engineer**: Collaborates on usability testing scenarios
- **Technical Writer**: Ensures UI terminology aligns with documentation

---

## Technical Writer

### Role Summary
Ensures documentation is clear, accurate, and up-to-date for both internal and external audiences. Technical Writers make complex information accessible and usable.

### Responsibilities
- Create and maintain user guides, API docs, and in-product help
- Document onboarding steps, release notes, and FAQs
- Work with all teams to capture changes in features or processes
- Ensure documentation follows style guides and standards
- Manage documentation versioning alongside product releases
- Gather feedback on documentation quality and usability

### Goals
- Provide comprehensive, accurate documentation for all features
- Reduce support burden through effective self-service resources
- Maintain documentation that evolves with the product

### Typical Communication
- Documentation reviews with Subject Matter Experts
- Release notes collaboration with Release Manager
- Content planning meetings with Product Manager
- Technical accuracy reviews with Developers

### Interactions with Other Roles
- **Developers**: Sources technical details and implementation information
- **Product Manager**: Understands feature purpose and user needs
- **QA/Test Automation Engineer**: Validates documentation accuracy through testing
- **Release Manager**: Coordinates on release notes and deployment documentation
- **UX/UI Designer**: Ensures consistency between UI and documentation terminology

---

## QA/Test Automation Engineer

### Role Summary
Designs and automates test scenarios to maintain and ensure product quality. QA/Test Automation Engineers are responsible for identifying defects and preventing regression.

### Responsibilities
- Develop automated tests for new and existing features
- Maintain test suites and CI/CD integration
- Report bugs found during testing with clear reproduction steps
- Support manual QA for complex or exploratory testing
- Define test strategies and coverage goals
- Participate in acceptance criteria definition
- Monitor test results and maintain test infrastructure

### Goals
- Achieve high test coverage for critical functionality
- Catch defects early in the development cycle
- Reduce manual testing effort through automation

### Typical Communication
- Bug reports and test results
- Test plan reviews with Project Manager and Developers
- Participation in sprint planning for testability discussion
- QA signoff communications during release process

### Interactions with Other Roles
- **Developers**: Collaborates on bug triage, resolution, and test strategy
- **Project Manager**: Reports testing status and quality metrics
- **Release Manager**: Provides QA signoff before deployments
- **UX/UI Designer**: Validates usability aspects during testing
- **Product Manager**: Ensures test coverage aligns with acceptance criteria
- **Security Engineer**: Coordinates on security testing requirements

---

## Release Manager

### Role Summary
Oversees the release process, coordinates deployments, and ensures proper communication. Release Managers are responsible for smooth, predictable releases.

### Responsibilities
- Maintain release schedules and deployment checklists
- Coordinate with Development, QA, and Infrastructure teams
- Communicate release status, blockers, and release notes
- Manage release branches and version control strategy
- Ensure release readiness criteria are met
- Coordinate rollback procedures when needed
- Track post-release metrics and incidents

### Goals
- Execute reliable, low-risk deployments
- Minimize deployment-related incidents and downtime
- Maintain clear release communication with all stakeholders

### Typical Communication
- Release readiness meetings
- Deployment notifications and status updates
- Release retrospectives
- Stakeholder briefings on release schedules

### Interactions with Other Roles
- **Project Manager**: Aligns on release timing and readiness
- **Developers**: Coordinates code freeze and deployment activities
- **QA/Test Automation Engineer**: Verifies testing completion before release
- **Technical Writer**: Ensures release documentation is prepared
- **Security Engineer**: Obtains security signoff for releases
- **Support teams**: Communicates release timing and expected changes

---

## Business Analyst

### Role Summary
Bridges technical and business teams to elicit requirements and clarify objectives. Business Analysts ensure that technical solutions align with business needs.

### Responsibilities
- Gather and document business requirements
- Map workflows and validate with stakeholders
- Support Product Manager in defining success criteria
- Analyze business processes and identify improvement opportunities
- Create functional specifications and user stories
- Facilitate requirements workshops and stakeholder interviews
- Track requirements traceability throughout the project

### Goals
- Ensure clear understanding of business needs across all teams
- Bridge communication between business stakeholders and technical teams
- Define measurable success criteria for features

### Typical Communication
- Requirements documentation and user stories
- Stakeholder interview summaries
- Business process maps and workflows
- Traceability matrices

### Interactions with Other Roles
- **Product Manager**: Collaborates on requirements and prioritization
- **Developers**: Translates business needs into technical requirements
- **QA/Test Automation Engineer**: Helps define test scenarios based on business rules
- **Project Manager**: Supports in scope management and requirements tracking
- **UX/UI Designer**: Provides user workflow insights
- **Stakeholders**: Primary liaison for business needs and validation

---

## Security Engineer

### Role Summary
Ensures best practices in security are followed throughout the project lifecycle. Security Engineers protect the system and data from vulnerabilities and threats.

### Responsibilities
- Identify potential security risks in features and architecture
- Conduct code reviews with a security lens
- Guide incident response and remediation
- Implement and maintain security controls
- Perform security testing and vulnerability assessments
- Ensure compliance with security policies and standards
- Provide security training and guidance to team members

### Goals
- Minimize security vulnerabilities in production
- Ensure regulatory compliance and data protection
- Build security awareness across the team

### Typical Communication
- Security review findings and recommendations
- Threat models and risk assessments
- Security incident reports
- Security signoff documentation

### Interactions with Other Roles
- **Developers**: Conducts security code reviews and provides secure coding guidance
- **Project Manager**: Tracks security risks and mitigation efforts
- **Release Manager**: Provides security signoff during release planning
- **QA/Test Automation Engineer**: Collaborates on security testing approaches
- **Product Manager**: Advises on security implications of feature decisions
- **Business Analyst**: Ensures security requirements are captured in specifications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

