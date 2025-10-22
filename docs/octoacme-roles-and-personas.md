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

## Release Manager

### Role Summary
Release Managers coordinate and oversee the release process from code-complete to production deployment. They ensure releases are well-planned, tested, and communicated, managing the release schedule and coordinating cross-team dependencies.

### Responsibilities
- Own the release calendar and coordinate release windows
- Manage release branches and version tagging
- Coordinate deployment activities with engineering and operations
- Ensure pre-release checklists and smoke tests are completed
- Communicate release status to stakeholders and support teams
- Manage rollback procedures when issues arise
- Track and report on release metrics (frequency, success rate, lead time)

### Goals
- Deliver reliable, predictable releases with minimal disruption
- Reduce deployment risk through standardized processes
- Maintain clear communication with all affected teams
- Continuously improve release velocity and quality

### Typical Communication
- Release planning meetings with PM, PdM, and engineering leads
- Pre-release readiness reviews
- Release announcements and change notifications to stakeholders
- Post-release reports and retrospectives
- Coordination with Support Lead for customer-facing changes

### Interactions with Other Roles
- **Project Manager**: Aligns release timelines with project milestones and communicates schedule risks
- **QA Lead**: Confirms all quality gates are passed before release approval
- **Developers**: Coordinates merge windows and ensures code freeze policies are followed
- **Support Lead**: Provides advance notice of changes and ensures support readiness
- **UX Designer**: Ensures UI/UX changes are documented for user communication

---

## QA Lead

### Role Summary
QA Leads define and execute the quality assurance strategy, ensuring that features meet acceptance criteria and quality standards before release. They coordinate testing efforts, manage test environments, and advocate for quality throughout the development lifecycle.

### Responsibilities
- Define test strategy and quality standards for projects
- Create and maintain test plans and test cases
- Coordinate manual and automated testing efforts
- Manage test environments and test data
- Identify and track defects through resolution
- Perform acceptance testing against defined criteria
- Advocate for testability and quality in design discussions
- Report on quality metrics and testing progress

### Goals
- Ensure releases meet quality standards and acceptance criteria
- Minimize production defects through comprehensive testing
- Improve test coverage and automation over time
- Build quality awareness across the team

### Typical Communication
- Test plan reviews with PM and engineering team
- Daily defect triage and status updates
- Quality gate checkpoints before releases
- Testing metrics in weekly project syncs
- Post-release quality retrospectives

### Interactions with Other Roles
- **Developers**: Collaborates on testability, reports defects, and validates fixes
- **Product Manager**: Validates acceptance criteria and prioritizes defect fixes
- **Project Manager**: Reports testing progress and risks to project schedule
- **Release Manager**: Provides go/no-go recommendations based on quality gates
- **UX Designer**: Tests usability and validates design implementation

---

## UX Designer

### Role Summary
UX Designers create user-centered designs that balance customer needs, business goals, and technical feasibility. They conduct user research, design interfaces and interactions, and validate designs through testing and feedback.

### Responsibilities
- Conduct user research and usability studies
- Create wireframes, mockups, and prototypes
- Define user flows and interaction patterns
- Ensure accessibility and inclusive design standards
- Collaborate with developers on design implementation
- Validate designs through user testing and feedback
- Maintain design systems and component libraries
- Document design decisions and guidelines

### Goals
- Deliver intuitive, accessible user experiences
- Validate designs with real user feedback
- Maintain design consistency across the product
- Balance user needs with technical and business constraints

### Typical Communication
- Design reviews with product and engineering teams
- User research presentations and findings
- Prototype walkthroughs and feedback sessions
- Design handoff documentation for developers
- Usability test reports and recommendations

### Interactions with Other Roles
- **Product Manager**: Translates product requirements into user-centered designs
- **Developers**: Collaborates on feasibility and implementation details
- **QA Lead**: Works together to validate design implementation and usability
- **Support Lead**: Gathers user feedback and identifies usability pain points
- **Project Manager**: Aligns design timelines with project milestones

---

## Support Lead

### Role Summary
Support Leads represent the customer voice in product development and ensure smooth transitions from development to customer use. They prepare support teams for releases, gather customer feedback, and escalate critical issues.

### Responsibilities
- Prepare support teams for upcoming releases and changes
- Create and maintain customer-facing documentation and knowledge base
- Monitor customer feedback and report trends to product teams
- Triage and escalate critical customer issues
- Participate in release planning to assess customer impact
- Conduct post-release reviews of customer-reported issues
- Define support readiness criteria for releases
- Train support team members on new features

### Goals
- Ensure support team readiness for all releases
- Minimize customer disruption during changes
- Provide actionable customer insights to product teams
- Maintain high-quality customer documentation

### Typical Communication
- Release readiness meetings with Release Manager and PM
- Customer impact assessments during planning
- Daily escalation reviews with engineering on-call
- Weekly customer feedback reports to product team
- Post-release support retrospectives

### Interactions with Other Roles
- **Release Manager**: Reviews release notes and ensures support readiness before deployment
- **Product Manager**: Provides customer feedback and feature requests from support trends
- **QA Lead**: Collaborates on reproducing and validating customer-reported defects
- **Developers**: Escalates critical issues and provides customer context for bugs
- **UX Designer**: Shares usability feedback and common customer pain points

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

