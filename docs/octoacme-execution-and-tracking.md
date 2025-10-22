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
  - Tag UX Designer for review when UI/UX changes are included
  - QA Lead signs off on feature PRs before marking as Done

## Quality & Testing
Quality ownership is shared between Developers and the QA Lead (see [Roles & Personas](octoacme-roles-and-personas.md)):
- **Developers**: Write unit tests for new logic and integration tests where applicable
- **QA Lead**: Defines quality gates, maintains test strategy, and performs acceptance testing
- **All team members**: Run automated tests and security scanning in CI before merging
- End-to-end smoke tests for critical flows before release (coordinated by QA Lead)
- Manual QA for feature acceptance when needed (QA Lead assigns and validates)
- Usability validation by UX Designer when UI changes are involved

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
Clear escalation paths ensure accountability (see [Risk Management & Communication](octoacme-risks-and-communication.md)):
- **Level 1**: Team-level triage in daily standup (PM facilitates)
- **Level 2**: PM escalates to Product Lead and dependent teams; QA Lead escalates quality concerns; UX Designer escalates design conflicts
- **Level 3**: Sponsor-level escalation for business-impacting issues
- **Customer-impacting issues**: Support Lead escalates to PM and engineering on-call immediately

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled with stakeholders
- [ ] Risk register updated weekly (PM with input from all roles)
- [ ] QA Lead tracking quality metrics and testing progress
- [ ] Release Manager tracking release readiness if applicable
- [ ] UX Designer validating design implementation iteratively
- [ ] Support Lead monitoring for customer impact and preparing documentation
