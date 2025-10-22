# OctoAcme Project Management Process Documentation

Welcome to OctoAcme's project management process documentation. This guide serves as the central entry point for understanding how we plan, execute, and deliver projects across our organization.

OctoAcme follows an iterative lifecycle approach built on clear ownership, measurable outcomes, and continuous improvement. Each project moves through distinct phases—initiation, planning, execution, release, and retrospective—with defined artifacts, decision gates, and communication touchpoints. Our Project Managers coordinate delivery and risk management, while Product Managers define success metrics and prioritize the backlog. Cross-functional teams collaborate using a project board, pull request workflows with automated CI, and structured release checklists to ensure quality and predictability.

Our process emphasizes customer value, psychological safety, and data-informed decisions. By maintaining a prioritized backlog, tracking risks in a shared register, and holding regular syncs and retrospectives, we create a culture of transparency and accountability. These documents provide the templates, checklists, and workflows that guide teams from initial problem statements through deployment and continuous improvement.

## Docs Index

The following documents detail each aspect of OctoAcme's project management approach:

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) — High-level principles, roles, lifecycle phases, and key artifacts
- [OctoAcme Project Initiation](octoacme-project-initiation.md) — Define the problem, align stakeholders, create a project one-pager, and authorize planning
- [OctoAcme Project Planning](octoacme-project-planning.md) — Build the prioritized backlog, estimate scope, define milestones, and prepare for execution
- [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day workflows, PR conventions, testing practices, and progress tracking
- [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md) — Identify and mitigate risks, maintain the risk register, and communicate with stakeholders
- [OctoAcme Release & Deployment](octoacme-release-and-deployment.md) — Release types, deployment checklist, rollback procedures, and release notes
- [OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, create action items, and iterate on processes
- [OctoAcme Roles & Personas](octoacme-roles-and-personas.md) — Detailed responsibilities for Project Managers, Product Managers, Developers, Release Manager, QA Lead, UX Designer, Support Lead, and Stakeholders, including handoffs and communication paths

## Getting Started

### For New Team Members

1. **Read the Project One-pager**: Every project starts with a one-pager that defines the problem, goal, success metrics, and stakeholders. Check your project repository for this foundational document.

2. **Review the Kickoff Checklist**: Found in the [Project Initiation guide](octoacme-project-initiation.md), this checklist ensures alignment before planning begins.

3. **Surface Docs to Copilot Spaces**: Add relevant process documents to your project's `.copilot/` directory so GitHub Copilot Spaces can use them as context when assisting with planning, execution, and delivery tasks.

4. **Join the Communication Cadence**: Connect with your Project Manager to understand the team's standups, weekly syncs, and demo schedule.

### Understanding the Workflow

Projects flow through five key phases:

1. **Initiation** — Validate the business need and create the project one-pager
2. **Planning** — Build the backlog, estimate effort, and define the release plan
3. **Execution** — Develop features using PR workflows, CI automation, and quality gates
4. **Release** — Deploy to production following the release checklist and smoke tests
5. **Retrospective** — Capture learnings and identify improvements for the next cycle

## How to Contribute

### Requesting Changes or Updates

If you identify a gap, improvement opportunity, or need clarification in any of these process documents, please use our standardized issue template:

- Navigate to the [Issues tab](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) in the repository
- Select "Add Content to Project Management Process Docs"
- Specify which document needs updating (or select "new document" if proposing entirely new content)
- Provide a summary of the change, rationale, and suggested content

Your issue will be reviewed by the process owners, and approved changes will be incorporated into the documentation.

### Review Process

All updates to process documentation should:
- Align with OctoAcme's principles of customer-first delivery, iterative improvement, and clear ownership
- Maintain consistency in style, terminology, and structure with existing documents
- Include practical examples, checklists, or templates where applicable
- Be reviewed with relevant stakeholders before merging

## Acceptance Criteria

This documentation meets the following acceptance criteria:

- [ ] Content aligns with existing process docs in style and terminology
- [ ] Update improves clarity and provides a clear entry point for navigating all process documents
- [ ] Proposed content has been reviewed with stakeholders (if needed)
