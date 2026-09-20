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

## Engineering Managers

### Role Summary
Engineering Managers support technical delivery by coordinating engineering capacity, execution, team health, and cross-team technical dependencies. They help translate project goals into an achievable delivery approach without replacing the ownership of Developers for implementation details.

### Responsibilities
- Plan engineering capacity and identify staffing constraints
- Coordinate technical execution and cross-team dependencies
- Support Developers with prioritization, design decisions, and delivery risks
- Ensure engineering practices support quality, maintainability, and observability
- Surface technical trade-offs and schedule risks to the Project Manager and Product Manager

### Interaction with Existing Roles
- Partner with the Project Manager on delivery plans, milestones, dependencies, and resource risks
- Partner with the Product Manager on scope, feasibility, sequencing, and trade-offs
- Support Developers during implementation while preserving their ownership of code and technical contributions
- Coordinate with QA/Testing and Release Managers to ensure work is ready for validation and deployment

---

## Security and Compliance Leads

### Role Summary
Security and Compliance Leads ensure that project decisions, designs, and releases address applicable security, privacy, regulatory, and compliance requirements. They help teams identify and mitigate risks early rather than treating security as a final release gate.

### Responsibilities
- Identify security, privacy, and compliance requirements during initiation and planning
- Review designs and implementation plans for threats, controls, and sensitive data handling
- Coordinate security testing, compliance evidence, and remediation activities
- Track security risks and escalate unresolved high-impact issues
- Advise on incident readiness and required release controls

### Interaction with Existing Roles
- Work with Product Managers to incorporate security and compliance requirements into outcomes and acceptance criteria
- Work with Developers and Engineering Managers on secure design, implementation choices, and remediation plans
- Work with Project Managers to record risks, dependencies, decisions, and escalation paths
- Coordinate with QA/Testing and Release Managers before deployment to confirm required checks are complete

---

## QA / Testing Leads

### Role Summary
QA / Testing Leads define and coordinate validation activities so the team can confidently verify that features meet acceptance criteria, quality standards, and release readiness expectations.

### Responsibilities
- Define test strategy, scope, and validation approach for each milestone or release
- Create and maintain quality gates, smoke tests, regression coverage, and acceptance validation plans
- Coordinate with Developers and Product Managers to ensure edge cases and risk areas are covered
- Identify quality risks, defects, and release blockers early in the lifecycle
- Validate readiness for staging and production deployment alongside Release Managers

### Interaction with Existing Roles
- Partner with Developers on test planning, defect triage, and release confidence
- Work with Product Managers to confirm that acceptance criteria are testable and measurable
- Support Project Managers by surfacing quality risks, schedule impacts, and release blockers
- Coordinate with Security and Compliance Leads on security and compliance validation requirements
- Collaborate with UX Researchers and Design Partners to include usability and accessibility checks in validation activities

---

## UX Researchers and Design Partners

### Role Summary
UX Researchers and Design Partners ensure that project decisions reflect user needs, accessibility considerations, and usable experiences. They provide evidence and design guidance that help the team validate assumptions before implementation and release.

### Responsibilities
- Conduct user research and synthesize customer needs and usability findings
- Create or review user flows, prototypes, and interaction designs
- Identify accessibility and usability risks
- Validate solutions with users and communicate findings to the delivery team
- Contribute user-centered acceptance criteria and release feedback

### Interaction with Existing Roles
- Work with Product Managers to refine problem statements, priorities, and success metrics
- Collaborate with Developers and Engineering Managers to ensure designs are feasible and implemented as intended
- Provide input to Project Managers on research dependencies, milestones, and risks
- Partner with QA/Testing to include usability and accessibility checks in validation activities
- Incorporate feedback from Customer Success and Support Liaisons into research and design decisions

---

## Release Managers and Deployment Leads

### Role Summary
Release Managers and Deployment Leads coordinate the operational readiness and execution of releases. They ensure that approved changes have a controlled rollout plan, appropriate verification, communications, and rollback or mitigation options.

### Responsibilities
- Maintain release schedules, readiness criteria, and deployment plans
- Coordinate staging validation, smoke tests, production deployment, and post-deploy verification
- Confirm release notes, stakeholder communications, and support readiness
- Ensure rollback, mitigation, and incident-response plans are documented
- Track release blockers and escalate launch risks

### Interaction with Existing Roles
- Work with Project Managers and Product Managers to align releases with milestones, scope, and stakeholder expectations
- Coordinate with Developers and Engineering Managers on deployment dependencies and technical readiness
- Partner with QA/Testing on test completion and release verification
- Work with Security and Compliance Leads to confirm required controls and approvals
- Coordinate with Customer Success and Support Liaisons so customer-facing teams are prepared for changes and known issues

---

## Customer Success and Support Liaisons

### Role Summary
Customer Success and Support Liaisons connect delivery teams with customer feedback, support trends, adoption needs, and operational pain points. They help ensure that project decisions account for the experience of existing and prospective users.

### Responsibilities
- Consolidate customer feedback, support cases, and recurring pain points
- Identify adoption, training, documentation, and enablement needs
- Provide customer impact context for prioritization and release decisions
- Coordinate customer-facing communications and feedback after releases
- Surface emerging incidents or usability concerns to the delivery team

### Interaction with Existing Roles
- Work with Product Managers to translate customer insights into backlog priorities and success measures
- Partner with Project Managers on stakeholder updates, customer dependencies, and communication plans
- Collaborate with UX Researchers and Design Partners to validate user problems and proposed solutions
- Coordinate with Release Managers on announcements, known issues, rollout timing, and support readiness
- Share reproducible issues and customer context with Developers, Engineering Managers, and QA/Testing

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign a clear owner for each responsibility while using the interaction guidance to make handoffs, decisions, and escalation paths explicit.

