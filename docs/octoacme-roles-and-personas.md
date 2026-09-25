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

## Technical Leads / Architecture Owners

### Role Summary
Technical Leads or Architecture Owners provide technical direction and ensure that implementation choices support product outcomes, maintainability, reliability, and agreed constraints.

### Responsibilities
- Define and communicate technical direction and architecture decisions
- Facilitate design reviews and document important trade-offs
- Identify technical dependencies, risks, and required mitigations
- Support estimation by clarifying technical scope and complexity
- Promote maintainable designs, observability, and operational readiness

### Interaction with Existing Roles
- Partner with Product Managers to translate product goals into feasible technical approaches
- Work with Project Managers to surface dependencies, risks, and schedule impacts
- Guide Developers through design decisions while preserving team ownership of implementation
- Coordinate with QA Leads, Security Champions, and Release Managers on quality, security, and deployment readiness

---

## QA Leads / Quality Owners

### Role Summary
QA Leads or Quality Owners establish the testing approach and help the team verify that deliverables meet acceptance criteria and quality standards before release.

### Responsibilities
- Define test strategy and coverage expectations for the project
- Confirm that acceptance criteria are testable and sufficiently complete
- Coordinate integration, end-to-end, regression, and manual testing where appropriate
- Track quality risks, defects, and release-readiness gaps
- Provide a quality recommendation before milestone or production releases

### Interaction with Existing Roles
- Work with Product Managers to clarify acceptance criteria and expected user outcomes
- Collaborate with Developers on testability, automated tests, defect triage, and fixes
- Coordinate with Project Managers to report quality status and escalate risks or schedule impacts
- Partner with Security Champions and Release Managers to include security checks and smoke tests in release readiness

---

## Security Champions / Compliance Reviewers

### Role Summary
Security Champions or Compliance Reviewers make security, privacy, and compliance considerations part of normal planning, implementation, testing, and release activities.

### Responsibilities
- Identify security, privacy, and compliance requirements early in the lifecycle
- Review designs and changes for relevant threats, controls, and data-handling risks
- Coordinate security scanning, remediation tracking, and exception decisions
- Advise the team on secure development and incident escalation practices
- Confirm that security evidence and approvals are available when required for release

### Interaction with Existing Roles
- Work with Product Managers to understand regulatory, customer, and data-protection expectations
- Partner with Technical Leads and Developers on secure architecture and implementation choices
- Update Project Managers on security risks, mitigations, and dependencies for the risk register
- Coordinate with QA Leads and Release Managers to include security validation in test and deployment plans

---

## Release Managers / Deployment Coordinators

### Role Summary
Release Managers or Deployment Coordinators organize the transition from completed work to a controlled release, with clear readiness checks, communications, and rollback plans.

### Responsibilities
- Coordinate release scope, timelines, deployment windows, and stakeholder notifications
- Confirm that acceptance criteria, CI checks, security scans, release notes, and rollback plans are complete
- Track staging validation, smoke tests, production deployment, and post-deployment verification
- Maintain a clear release decision and escalation path
- Capture release outcomes, incidents, and follow-up actions

### Interaction with Existing Roles
- Work with Project Managers to align release milestones, risks, dependencies, and communications
- Confirm scope and business readiness with Product Managers
- Coordinate with Technical Leads, Developers, and QA Leads on technical readiness and verification
- Partner with Security Champions on required security approvals and with stakeholders on release announcements and support readiness

---

## Customer Success / Stakeholder Liaisons

### Role Summary
Customer Success or Stakeholder Liaisons represent customer and stakeholder perspectives throughout delivery and help ensure that changes are understood, adopted, and supported.

### Responsibilities
- Gather and communicate customer, operational, and stakeholder needs and feedback
- Maintain stakeholder alignment on milestones, changes, risks, and expected outcomes
- Support readiness, training, adoption, and post-release feedback activities
- Identify communication gaps, adoption risks, and emerging customer-impacting issues
- Connect project outcomes and success metrics to stakeholder expectations

### Interaction with Existing Roles
- Partner with Product Managers to translate feedback into product priorities and measurable outcomes
- Work with Project Managers on stakeholder mapping, status updates, decisions, and escalation needs
- Collaborate with QA Leads and Release Managers on acceptance, support readiness, and release communications
- Provide Developers and Technical Leads with user and operational context without replacing their technical decision ownership

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign a named owner for each active responsibility while recognizing that one person may fill multiple personas on a small team.
- Use the interaction guidance to make handoffs, decisions, risks, and approvals explicit during initiation, planning, execution, release, and retrospective activities.

