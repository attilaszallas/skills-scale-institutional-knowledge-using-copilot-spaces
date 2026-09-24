# OctoAcme Personas and Roles

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. The personas below help teams make ownership, collaboration, and handoffs explicit throughout the delivery lifecycle.

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

## UX Designers

### Role Summary
UX Designers understand user needs and turn them into accessible, usable workflows and interfaces. They ensure that proposed solutions are clear and effective before and during implementation.

### Responsibilities
- Conduct user research and synthesize user needs
- Create journeys, wireframes, prototypes, and interaction specifications
- Validate designs with users and incorporate feedback
- Define usability and accessibility considerations
- Partner with Product Managers to connect user outcomes to product goals

### Goals
- Make experiences intuitive, inclusive, and fit for purpose
- Reduce rework by validating workflows early
- Provide developers with clear, implementable design guidance

### Interaction with Existing Roles
- Work with Product Managers to refine problem statements, personas, and acceptance criteria
- Collaborate with Developers during refinement and implementation to resolve design questions
- Coordinate with Project Managers on research, design, and usability milestones
- Share usability findings and decisions in design documentation and reviews

---

## Quality Engineers

### Role Summary
Quality Engineers protect product quality by designing validation strategies, automating appropriate checks, and helping the team prevent defects throughout delivery.

### Responsibilities
- Define test strategies and coverage for features and releases
- Create and maintain automated and exploratory tests
- Verify acceptance criteria, accessibility, and regression risk
- Report, prioritize, and help reproduce defects
- Contribute quality insights to release readiness decisions

### Goals
- Detect important issues early and reduce escaped defects
- Make quality practices repeatable and visible
- Balance delivery speed with appropriate confidence and risk control

### Interaction with Existing Roles
- Partner with Product Managers to clarify acceptance criteria and edge cases
- Work with Developers to build testable designs, investigate failures, and improve automation
- Provide Project Managers with quality status, risks, and release-readiness information
- Collaborate with UX Designers on usability and accessibility validation

---

## Security and Compliance Specialists

### Role Summary
Security and Compliance Specialists identify security, privacy, regulatory, and governance requirements and help the team address them throughout the product lifecycle.

### Responsibilities
- Translate applicable policies and regulations into actionable requirements
- Facilitate threat modeling, security reviews, and privacy impact assessments
- Advise on secure design, data handling, access control, and auditability
- Track security findings and verify remediation or approved exceptions
- Support incident preparedness and compliance evidence collection

### Goals
- Reduce security and compliance risk without creating avoidable delivery friction
- Make controls and decisions traceable
- Protect customers, users, and company data

### Interaction with Existing Roles
- Work with Product Managers to include security and compliance outcomes in the roadmap and acceptance criteria
- Advise Developers and UX Designers on secure, private, and accessible solution designs
- Coordinate with Quality Engineers to include security and compliance checks in test plans
- Partner with Project Managers to track findings, dependencies, approvals, and evidence in project reporting

---

## Site Reliability Engineers

### Role Summary
Site Reliability Engineers make services operable, resilient, and observable from development through production. They help teams manage operational risk and learn from real-world service behavior.

### Responsibilities
- Define reliability, availability, performance, and observability requirements
- Build and maintain deployment, monitoring, alerting, and recovery practices
- Review operational readiness and capacity before releases
- Participate in incident response, post-incident learning, and remediation planning
- Help teams automate repetitive operational work

### Goals
- Keep services reliable and recoverable
- Reduce operational toil and time to detect and resolve incidents
- Make production health and release risk visible

### Interaction with Existing Roles
- Work with Developers on service design, automation, instrumentation, and operational fixes
- Help Product Managers and Project Managers set realistic reliability goals and release plans
- Collaborate with Quality Engineers on performance, resilience, and recovery testing
- Provide incident and operational feedback that informs roadmap prioritization and risk management

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign complementary personas to planning, delivery, release, and incident scenarios so that decisions reflect both customer value and delivery risk.
- Treat the role boundaries as collaboration guidance: one person may hold multiple roles on a small team, but the responsibilities and handoffs should remain explicit.
