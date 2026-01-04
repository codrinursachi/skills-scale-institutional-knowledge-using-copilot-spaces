# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Manager Role
The Release Manager coordinates all release activities and ensures smooth deployments. See [Roles & Personas - Release Manager](octoacme-roles-and-personas.md#release-manager) for detailed responsibilities and interactions.

For comprehensive release coordination, refer to the [Release Management Checklist](templates/release-management-checklist.md).

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

---

## Additional Resources
- [Release Management Checklist](templates/release-management-checklist.md) - Comprehensive checklist for all release phases
- [Roles & Personas - Release Manager](octoacme-roles-and-personas.md#release-manager) - Role responsibilities and interactions
- [Cross-Team Collaboration Guide](templates/cross-team-collaboration-guide.md) - Coordination patterns for releases

---

*Updated based on [Issue #4](https://github.com/codrinursachi/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to incorporate Release Manager role and comprehensive release management templates.*
