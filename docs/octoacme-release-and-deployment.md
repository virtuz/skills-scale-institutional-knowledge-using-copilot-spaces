# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability. The Release Manager coordinates this process (see [Roles & Personas](octoacme-roles-and-personas.md)).

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
Release Manager validates readiness with input from key roles:
- All acceptance criteria met and PRs merged (validated by QA Lead)
- Passing CI and security scans
- Release notes drafted (Release Manager with input from PM and PdM)
- Rollback / mitigation plan documented (Release Manager)
- Smoke tests prepared and executed (QA Lead)
- Support documentation updated (Support Lead)
- Design changes documented for users if applicable (UX Designer)

## Deployment Checklist
Release Manager coordinates the following steps:
- [ ] Deployment window scheduled and communicated (if needed)
- [ ] Support Lead notified and support team briefed
- [ ] Backup or snapshot completed (if applicable)
- [ ] Deploy to staging and run smoke tests (QA Lead validates)
- [ ] Go/no-go decision made by Release Manager with QA Lead sign-off
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications (QA Lead)
- [ ] Monitor key metrics and error rates
- [ ] Release announcement sent to stakeholders (Release Manager) and support teams (Support Lead)

## Rollback & Incident Playbook
If a deployment fails or causes a critical issue, clear handoffs ensure quick response:
- **Release Manager**: Initiates rollback decision and coordinates response
- **QA Lead**: Validates rollback success and monitors for regressions
- **Support Lead**: Communicates status to affected customers and escalates severity
- **PM**: Coordinates incident retrospective and tracks action items
- Steps:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Validate rollback with smoke tests
  - Triage root cause and capture action items
  - Schedule blameless retrospective (see [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md))

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
