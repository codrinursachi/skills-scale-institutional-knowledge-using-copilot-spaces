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
Release Managers oversee release planning, coordination, and deployment activities. They work closely with Product Owners, QA Leads, and Development Teams to ensure releases are smooth, timely, and meet all quality criteria.

### Responsibilities
- Coordinate release schedules and deployment windows
- Manage release branches and version control strategy
- Facilitate go/no-go decisions for releases
- Coordinate with QA Lead for final release validation
- Ensure release notes and documentation are complete
- Manage rollback procedures and incident response during releases
- Track release metrics and identify process improvements

### Goals
- Deliver releases on schedule with zero critical defects
- Minimize deployment risk and downtime
- Maintain clear communication about release status
- Continuously improve release processes

### Typical Communication
- Release planning meetings with Product Owner and QA Lead
- Daily standups during release sprints
- Release status updates to stakeholders
- Post-release retrospectives and incident reviews

### Interaction Examples
- **With Product Owner**: Aligns on release scope, priorities, and go/no-go criteria
- **With QA Lead**: Coordinates test completion, validation, and sign-off
- **With Development Team**: Manages code freeze, deployment readiness, and hotfix prioritization
- **With Project Manager**: Shares release timeline and coordinates cross-team dependencies

---

## QA Lead

### Role Summary
QA Leads are responsible for overall quality assurance strategies, test management, and quality standards. They collaborate with developers, Release Managers, and Product Managers to ensure comprehensive testing coverage and quality gates.

### Responsibilities
- Define and maintain testing strategy and quality standards
- Oversee test planning, execution, and reporting
- Manage test environments and test data
- Review and approve test coverage for releases
- Identify quality risks and drive mitigation actions
- Mentor team members on testing best practices
- Track quality metrics and defect trends

### Goals
- Maintain high product quality and minimize production defects
- Ensure comprehensive test coverage across all features
- Reduce time-to-detection for quality issues
- Foster a quality-first culture across the team

### Typical Communication
- Weekly quality review sessions with Product Manager
- Test planning discussions during sprint planning
- Daily test status updates during release cycles
- Quality metrics reporting to stakeholders

### Interaction Examples
- **With Developers**: Reviews test plans, participates in code reviews focusing on testability
- **With Release Manager**: Provides quality sign-off for releases and coordinates test execution
- **With Product Manager**: Aligns on acceptance criteria and quality standards
- **With Technical Writer**: Ensures test documentation is clear and maintainable

---

## Data Steward

### Role Summary
Data Stewards manage data integrity, governance, and quality across systems. They partner with technical and business teams to ensure consistent, secure, and high-quality data handling practices.

### Responsibilities
- Define and enforce data governance policies
- Manage data quality standards and validation rules
- Oversee data access controls and privacy compliance
- Coordinate data migration and integration activities
- Monitor data health metrics and resolve data issues
- Document data models, dictionaries, and lineage
- Facilitate data-related training and awareness

### Goals
- Ensure data accuracy, consistency, and completeness
- Maintain compliance with data privacy regulations
- Enable data-driven decision making with trusted data
- Minimize data-related incidents and technical debt

### Typical Communication
- Monthly data governance meetings with stakeholders
- Data quality reviews with engineering teams
- Compliance check-ins with legal/security teams
- Training sessions for data best practices

### Interaction Examples
- **With Developers**: Reviews data models, validates data handling code, and defines data contracts
- **With Product Manager**: Ensures feature requirements include proper data governance
- **With Project Manager**: Identifies data-related dependencies and risks
- **With Process Owner**: Contributes to data governance process improvements

---

## Community Facilitator

### Role Summary
Community Facilitators engage with and support the project community, gathering feedback, handling communications, and surfacing insights to the team. They serve as a bridge between external stakeholders and internal teams.

### Responsibilities
- Manage community communication channels and forums
- Gather and synthesize community feedback and feature requests
- Coordinate community events, demos, and engagement activities
- Monitor community sentiment and escalate issues
- Maintain community documentation and FAQs
- Recognize and support community contributors
- Report community insights to Product and Project teams

### Goals
- Build and maintain an engaged, supportive community
- Ensure community voices inform product decisions
- Increase community satisfaction and retention
- Foster a welcoming and inclusive environment

### Typical Communication
- Daily monitoring of community channels
- Weekly community health reports to Product Manager
- Monthly community newsletters and announcements
- Quarterly community surveys and feedback sessions

### Interaction Examples
- **With Product Manager**: Shares community feedback and helps prioritize user-requested features
- **With Technical Writer**: Collaborates on user-facing documentation and FAQs
- **With Developers**: Facilitates community bug reports and feature discussions
- **With QA Lead**: Helps coordinate community beta testing programs

---

## Technical Writer

### Role Summary
Technical Writers maintain and improve process documentation, working with all roles to gather information, ensure clarity, and make content accessible for broad audiences.

### Responsibilities
- Create and maintain technical and process documentation
- Review documentation for accuracy, clarity, and consistency
- Collaborate with subject matter experts to gather information
- Manage documentation workflows and version control
- Ensure documentation follows style guides and standards
- Identify and address documentation gaps
- Facilitate documentation reviews and updates

### Goals
- Provide clear, accurate, and up-to-date documentation
- Reduce time-to-productivity for new team members
- Minimize support burden through self-service documentation
- Maintain documentation that scales with the organization

### Typical Communication
- Regular check-ins with all roles for documentation needs
- Documentation review sessions with subject matter experts
- Style guide and template updates to stakeholders
- Documentation metrics and gap analysis reports

### Interaction Examples
- **With Developers**: Captures technical details, API documentation, and architecture decisions
- **With Product Manager**: Documents product requirements, user guides, and release notes
- **With Process Owner**: Maintains process documentation and templates
- **With Community Facilitator**: Creates user-facing documentation and community resources

---

## Process Owner

### Role Summary
Process Owners are accountable for the effectiveness and evolution of project management processes. They regularly review and update process documentation, facilitate process improvement initiatives, and collaborate with all roles to ensure processes serve the team's needs.

### Responsibilities
- Own and maintain the project management process framework
- Facilitate process review and improvement sessions
- Monitor process effectiveness metrics and KPIs
- Identify process gaps and bottlenecks
- Drive process standardization and best practice adoption
- Coordinate process training and onboarding
- Ensure processes align with organizational goals

### Goals
- Continuously improve process efficiency and effectiveness
- Reduce waste and eliminate unnecessary process overhead
- Increase process adoption and consistency
- Foster a culture of continuous improvement

### Typical Communication
- Monthly process review meetings with leadership
- Quarterly process health assessments and retrospectives
- Process improvement workshops with teams
- Regular updates to process documentation

### Interaction Examples
- **With Project Manager**: Collaborates on process execution and identifies improvement opportunities
- **With Technical Writer**: Ensures process documentation is clear and current
- **With Release Manager**: Reviews and optimizes release processes
- **With All Roles**: Gathers feedback and facilitates process improvement initiatives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

## Role Interaction Overview

The expanded set of personas work together to ensure comprehensive project success:

- **Core Delivery**: Product Managers, Project Managers, and Developers form the core delivery team, supported by Release Manager for deployments and QA Lead for quality assurance.
- **Quality & Risk**: QA Lead and Release Manager coordinate closely during release cycles, while Data Steward ensures data integrity across all activities.
- **Communication & Improvement**: Community Facilitator bridges external stakeholders with internal teams, Technical Writer ensures clear documentation, and Process Owner drives continuous improvement.
- **Cross-functional Collaboration**: All roles collaborate through regular cadences (standups, planning sessions, retrospectives) and maintain transparency through shared artifacts (project boards, documentation, metrics).

For specific collaboration patterns, see the [Cross-Team Collaboration Guide](./templates/cross-team-collaboration-guide.md) and [Role Onboarding Checklist](./templates/role-onboarding-checklist.md).

---

*This document was updated based on feedback from [Issue #4](https://github.com/codrinursachi/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to expand role definitions and clarify responsibilities for comprehensive project management coverage.*

