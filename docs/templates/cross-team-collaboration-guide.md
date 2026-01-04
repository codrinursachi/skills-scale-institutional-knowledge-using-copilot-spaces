# Cross-Team Collaboration Guide

## Purpose
Define effective patterns for collaboration between roles and teams in OctoAcme projects to ensure clear communication, reduce friction, and maintain alignment on shared goals.

---

## Core Collaboration Principles

1. **Clear Ownership**: Every task, decision, and artifact has a clear owner
2. **Transparent Communication**: Share context proactively through documented channels
3. **Respect Boundaries**: Understand each role's scope and involve them at the right time
4. **Iterative Feedback**: Seek input early and often, incorporate feedback constructively
5. **Shared Accountability**: Success is a team outcome; support each other's goals

---

## Key Collaboration Patterns

### Product Development Cycle

#### Planning Phase
**Who**: Product Manager, Project Manager, Developers, QA Lead
- **Product Manager** defines problem statement, success metrics, and prioritized features
- **Project Manager** estimates timeline, identifies dependencies, and creates project plan
- **Developers** provide technical feasibility input and effort estimates
- **QA Lead** defines testing strategy and acceptance criteria

**Artifacts**: Project Charter, Backlog, Release Plan, Test Strategy

#### Execution Phase
**Who**: Developers, QA Lead, Project Manager, Technical Writer
- **Developers** implement features in small increments with tests
- **QA Lead** validates acceptance criteria and coordinates test execution
- **Project Manager** tracks progress, manages risks, and facilitates standups
- **Technical Writer** documents features and updates relevant guides

**Artifacts**: Pull Requests, Test Reports, Status Updates, Feature Documentation

#### Release Phase
**Who**: Release Manager, QA Lead, Product Manager, Developers
- **Release Manager** coordinates deployment schedule and go/no-go decision
- **QA Lead** provides quality sign-off and final validation
- **Product Manager** approves release scope and reviews release notes
- **Developers** support deployment and monitor post-release metrics

**Artifacts**: Release Checklist, Deployment Plan, Release Notes, Rollback Procedures

---

### Cross-Functional Collaboration Scenarios

#### Scenario 1: New Feature Request from Community
**Flow**: Community Facilitator → Product Manager → Project Manager → Development Team

1. **Community Facilitator** gathers and synthesizes feedback from community channels
2. **Product Manager** evaluates against roadmap, prioritizes if accepted
3. **Project Manager** adds to backlog and coordinates planning discussion
4. **Development Team** estimates effort and begins implementation when prioritized

**Communication**: Community feedback report → Product backlog item → Sprint planning discussion

---

#### Scenario 2: Release Planning and Execution
**Flow**: Product Manager → Release Manager → QA Lead → Developers → Community Facilitator

1. **Product Manager** defines release scope and success criteria
2. **Release Manager** creates release plan with deployment schedule
3. **QA Lead** defines test plan and quality gates for release
4. **Developers** complete features, fix bugs, prepare release branch
5. **QA Lead** executes tests and provides sign-off
6. **Release Manager** coordinates deployment and monitors rollout
7. **Community Facilitator** announces release and gathers feedback

**Communication**: Release kickoff meeting → Daily release standups → Release retrospective

---

#### Scenario 3: Data Governance Implementation
**Flow**: Data Steward → Product Manager → Developers → QA Lead

1. **Data Steward** defines data governance requirements and policies
2. **Product Manager** incorporates data requirements into feature specs
3. **Developers** implement data handling with proper validation and controls
4. **Data Steward** reviews data models and code for compliance
5. **QA Lead** includes data quality tests in test plan
6. **Data Steward** audits implementation post-deployment

**Communication**: Data governance review → Feature planning → Code review → Post-deployment audit

---

#### Scenario 4: Process Improvement Initiative
**Flow**: Process Owner → All Roles → Technical Writer → Process Owner

1. **Process Owner** identifies process gap or improvement opportunity
2. **All Roles** participate in retrospective or improvement workshop
3. **Process Owner** synthesizes feedback and proposes changes
4. **Technical Writer** updates process documentation
5. **Process Owner** communicates changes and monitors adoption
6. **All Roles** provide feedback on improved process

**Communication**: Process review meeting → Improvement proposal → Documentation update → Adoption metrics

---

#### Scenario 5: Critical Production Issue
**Flow**: Any Role → Release Manager → Developers → QA Lead → Community Facilitator

1. **Any Role** detects and escalates critical issue
2. **Release Manager** triggers incident response and coordinates
3. **Developers** investigate root cause and implement fix
4. **QA Lead** validates fix in staging environment
5. **Release Manager** coordinates hotfix deployment
6. **Community Facilitator** communicates status to affected users
7. **Project Manager** documents incident and action items

**Communication**: Incident alert → War room / sync → Status updates → Post-incident review

---

## Communication Channels and Cadences

### Synchronous Channels
- **Daily Standups** (15 min): Development Team, Project Manager, QA Lead
- **Weekly Planning** (1 hour): Product Manager, Project Manager, Development Team leads
- **Release Planning** (2 hours): Release Manager, Product Manager, QA Lead, key Developers
- **Monthly Stakeholder Updates** (30 min): Project Manager, Product Manager, stakeholders
- **Quarterly Process Reviews** (2 hours): Process Owner, representatives from all roles

### Asynchronous Channels
- **Pull Requests & Code Reviews**: Developers, QA Lead, Technical Writer
- **Project Board Updates**: All team members update their tasks daily
- **Risk Register**: Project Manager updates weekly; all roles contribute as needed
- **Documentation Updates**: Technical Writer coordinates; all roles contribute
- **Community Feedback Reports**: Community Facilitator shares weekly summaries

---

## Decision-Making Framework

### Decision Types and Owners

| Decision Type | Primary Owner | Consulted Roles | Informed Roles |
|--------------|---------------|-----------------|----------------|
| Product roadmap prioritization | Product Manager | Project Manager, Developers | All roles |
| Release go/no-go | Release Manager | Product Manager, QA Lead | All roles |
| Technical architecture | Developers (Lead) | QA Lead, Data Steward | Product Manager, Project Manager |
| Quality standards | QA Lead | Developers, Process Owner | All roles |
| Data governance policies | Data Steward | Product Manager, Developers | All roles |
| Process changes | Process Owner | All affected roles | All roles |
| Community engagement strategy | Community Facilitator | Product Manager, Technical Writer | Project Manager |

### Escalation Path
1. **Team Level**: Discuss in standups or working sessions
2. **Project Level**: Escalate to Project Manager or Product Manager
3. **Leadership Level**: Escalate through manager chain for strategic decisions
4. **Emergency**: Direct escalation to Release Manager for production issues

---

## Collaboration Best Practices

### For All Roles
- **Document decisions**: Use decision logs, PR descriptions, meeting notes
- **Share context proactively**: Don't assume others know what you know
- **Ask clarifying questions**: Better to ask than assume
- **Respect response times**: Set clear expectations for urgency
- **Follow up on action items**: Close the loop on commitments

### Cross-Role Collaboration Tips
- **Developers ↔ QA Lead**: Involve QA early in design; share test results transparently
- **Product Manager ↔ Developers**: Explain the "why" behind features; be open about constraints
- **Project Manager ↔ All Roles**: Aggregate concerns; don't become a bottleneck
- **Release Manager ↔ QA Lead**: Coordinate testing windows; align on release criteria
- **Data Steward ↔ Developers**: Review data models early; provide clear governance requirements
- **Community Facilitator ↔ Product Manager**: Quantify feedback trends; prioritize high-impact requests
- **Technical Writer ↔ Subject Matter Experts**: Schedule regular doc reviews; make updates easy
- **Process Owner ↔ All Roles**: Gather continuous feedback; balance standardization with flexibility

---

## Collaboration Tools and Artifacts

### Essential Artifacts for Cross-Team Work
- **Project Charter**: Single source of truth for goals, scope, timeline
- **RACI Matrix**: Clarifies who is Responsible, Accountable, Consulted, Informed
- **Decision Log**: Records key decisions, context, and owners
- **Risk Register**: Shared view of risks, mitigations, and status
- **Definition of Done**: Shared quality standards for completed work
- **Communication Plan**: Who needs what information, when, and how

### Tool Recommendations
- **Project Boards**: Visualize work, dependencies, and status
- **Documentation Wiki**: Central repository for processes, guides, templates
- **Chat/Messaging**: Quick questions, coordination, informal discussion
- **Video Conferencing**: Complex discussions, planning sessions, retrospectives
- **Email/Announcements**: Formal communications, broad updates, approvals

---

## Measuring Collaboration Effectiveness

### Health Indicators
- **Cycle Time**: Time from idea to production (should decrease with good collaboration)
- **Rework Rate**: Percentage of work requiring changes (should decrease)
- **Meeting Efficiency**: Participation and outcomes (should improve)
- **Documentation Quality**: Clarity and usage metrics (should improve)
- **Team Satisfaction**: Regular surveys and retrospective feedback (should remain high)

### Red Flags
- Decisions being remade or challenged after implementation
- Same questions being asked repeatedly
- Important stakeholders surprised by changes
- Long lead times for simple coordination
- Silos forming between roles or teams

---

## Templates and Examples

### RACI Matrix Template
| Task/Decision | Product Manager | Project Manager | Developer | QA Lead | Release Manager | Data Steward | Community Facilitator | Technical Writer | Process Owner |
|--------------|----------------|-----------------|-----------|---------|-----------------|--------------|----------------------|-----------------|---------------|
| Feature prioritization | A/R | C | C | I | I | I | C | I | I |
| Release planning | C | C | C | C | A/R | I | I | I | I |
| Code review | I | I | A/R | C | I | I | I | I | I |
| Quality sign-off | I | I | C | A/R | C | I | I | I | I |

**Legend**: R = Responsible, A = Accountable, C = Consulted, I = Informed

### Communication Plan Template
| Stakeholder | Information Need | Frequency | Channel | Owner |
|-------------|-----------------|-----------|---------|-------|
| Leadership | Strategic progress | Monthly | Email report | Project Manager |
| Development Team | Daily progress | Daily | Standup | Project Manager |
| Community | Feature updates | Per release | Community channels | Community Facilitator |

---

## Continuous Improvement

This guide should evolve based on team feedback and changing needs:
- Gather feedback in retrospectives about collaboration pain points
- Update templates and patterns as processes mature
- Share success stories and lessons learned
- Involve Process Owner in significant changes
- Keep documentation current with Technical Writer support

---

## Resources
- [Roles & Personas](../octoacme-roles-and-personas.md)
- [Project Management Overview](../octoacme-project-management-overview.md)
- [Role Onboarding Checklist](./role-onboarding-checklist.md)
- [Risk Management & Communication](../octoacme-risks-and-communication.md)

---

*This guide was created as part of improvements identified in [Issue #4](https://github.com/codrinursachi/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to strengthen cross-team collaboration and clarity.*
