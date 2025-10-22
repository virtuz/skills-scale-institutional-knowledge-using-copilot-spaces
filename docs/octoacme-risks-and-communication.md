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
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
Clear communication paths ensure alignment across all roles (see [Roles & Personas](octoacme-roles-and-personas.md) for details):
- **Project Manager**: Coordinates overall status updates and stakeholder communication
- **Product Manager**: Communicates product vision, priorities, and trade-offs
- **Release Manager**: Announces release schedules and deployment windows
- **QA Lead**: Reports quality metrics and testing risks
- **UX Designer**: Shares design decisions and user research findings
- **Support Lead**: Communicates customer impact and support readiness
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
Clear escalation accountability by issue type:
- **General blockers**: Team-level -> PM -> Product Lead -> Sponsor
- **Quality concerns**: QA Lead -> PM -> Product Lead
- **Release risks**: Release Manager -> PM -> Product Lead
- **Customer-impacting incidents**: Support Lead -> PM + Engineering on-call (immediate)
- **Design conflicts**: UX Designer -> Product Manager -> Product Lead
- **Security incidents**: Follow security incident runbook and notify Security on-call immediately

For routine escalations, see [Execution & Tracking](octoacme-execution-and-tracking.md).
