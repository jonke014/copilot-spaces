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

## Delivery Lead

### Role Summary
The Delivery Lead keeps the team focused on execution and removes blockers that slow delivery. They help maintain sprint rhythm, coordinate planning, and support the team in turning work into completed increments.

### Responsibilities
- Facilitate sprint planning, standups, and retrospectives
- Track delivery progress, priorities, and blockers
- Help resolve cross-team dependencies and impediments
- Ensure action items and follow-ups are closed
- Work with the Project Manager to identify risk and schedule impact

### Typical Handoffs
- With Project Managers: align on milestone health, scope pressure, and communication needs
- With Developers: remove blockers and clarify execution priorities
- With Product Managers: escalate trade-offs and sequencing questions

### When to Engage
- During sprint planning and weekly execution reviews
- When delivery risk or team capacity is at issue
- When work is stalled by dependencies or unclear ownership

---

## Release Manager

### Role Summary
The Release Manager owns coordination of release readiness, deployment timing, and stakeholder communication. They ensure release activities are planned, tracked, and communicated consistently.

### Responsibilities
- Coordinate release windows and deployment plans
- Validate release checklists and pre-release readiness
- Own rollback and mitigation planning for launch risk
- Communicate release status to stakeholders and support teams
- Partner with SRE/Platform and engineering leads for go/no-go decisions

### Typical Handoffs
- With Project Managers: align on stakeholder communication and release timing
- With Developers: confirm completed work, regression risks, and change scope
- With SRE/Platform: validate production readiness, observability, and rollback capability

### When to Engage
- Before each release candidate or production deployment
- During incident response and rollback planning
- When release communications are needed for internal or customer stakeholders

---

## SRE / Platform Engineer

### Role Summary
SRE / Platform Engineers ensure the platform is reliable, observable, and scalable. They support production health and help teams design systems that operate safely in real environments.

### Responsibilities
- Maintain platform reliability, monitoring, and incident response readiness
- Define observability requirements, dashboards, alerts, and runbooks
- Support deployments, environment readiness, and release safety checks
- Help diagnose production issues and coordinate mitigation efforts
- Partner with Developers to improve service reliability and resilience

### Typical Handoffs
- With Developers: design for reliability, observability, and deployability
- With QA Lead: align on smoke testing and production-like validation
- With Release Manager: confirm deployment safety and rollback readiness

### When to Engage
- Before major releases or risky changes
- During incident triage and post-incident follow-up
- When service health, performance, or platform capacity is a concern

---

## QA Lead / Test Architect

### Role Summary
The QA Lead defines quality strategy and validation standards to reduce product risk and ensure work meets the definition of done. They support both automated and manual quality assurance across the lifecycle.

### Responsibilities
- Define test strategy across unit, integration, and end-to-end coverage
- Set quality gates for feature readiness and release approval
- Coordinate manual QA, regression planning, and acceptance validation
- Help identify gaps in testing, monitoring, or validation coverage
- Work with Developers and Product Managers to define acceptance criteria

### Typical Handoffs
- With Developers: review testability, automation opportunities, and defect triage
- With Product Managers: validate user-facing acceptance criteria and expected outcomes
- With Release Manager: confirm sign-off criteria for deployment readiness

### When to Engage
- During planning and backlog refinement
- Before release windows and acceptance gates
- When product quality or regression risk is elevated

---

## Security Liaison

### Role Summary
The Security Liaison helps ensure security and compliance considerations are addressed early and tracked consistently. They act as the bridge between delivery teams and security stakeholders.

### Responsibilities
- Review product and technical changes for security impact
- Ensure security scans, reviews, and compliance checks are executed
- Track remediation plans for vulnerabilities and policy gaps
- Coordinate escalation for high-risk or high-impact issues
- Support secure-by-default design decisions

### Typical Handoffs
- With Developers: identify vulnerabilities, risk areas, and remediation priorities
- With Project Managers: communicate roadblocks, timelines, and escalation needs
- With Product Managers: assess business risk and release implications

### When to Engage
- During design reviews and implementation planning
- Before major releases or externally exposed changes
- When security findings or policy exceptions are identified

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers help ensure the product is usable, understandable, and valuable for the intended users. They translate customer needs into design direction and measurable experience quality.

### Responsibilities
- Gather user needs, research insights, and usability feedback
- Create or refine user flows, wireframes, and design direction
- Provide input on acceptance criteria for usability and interaction quality
- Run usability checks and validate design assumptions with users
- Partner with Product Managers and Developers to balance user value with technical constraints

### Typical Handoffs
- With Product Managers: shape problem framing, feature priorities, and user outcomes
- With Developers: clarify interaction requirements and edge cases
- With QA Lead: validate usability acceptance and regression scenarios

### When to Engage
- During discovery, prioritization, and feature definition
- When user experience or accessibility issues are under review
- Before launch for user validation and sign-off

---

## Data Analyst / Measurement Lead

### Role Summary
The Data Analyst defines how success is measured and ensures teams use trustworthy data to inform product decisions. They help connect delivery activity to outcomes and business value.

### Responsibilities
- Define key metrics, dashboards, and reporting views
- Validate data quality and measurement methods for experiments and releases
- Support analysis of product performance and customer impact
- Partner with Product Managers on success criteria and trend monitoring
- Help document the business impact of system changes

### Typical Handoffs
- With Product Managers: define success metrics and reporting cadence
- With Developers: confirm instrumentation needs and data quality checks
- With Release Manager: provide post-release monitoring and trend review

### When to Engage
- During planning and success metric definition
- Before and after releases for impact evaluation
- When experiments, feature adoption, or conversion metrics are involved

---

## Support / Customer Success Liaison

### Role Summary
The Support / Customer Success Liaison brings customer-facing insights into planning and delivery. They help ensure user pain points are understood and resolved quickly.

### Responsibilities
- Capture recurring customer issues and support trends
- Prioritize bug fixes and service-impacting concerns
- Share customer feedback with Product and Engineering teams
- Coordinate communications for known issues or service interruptions
- Support release readiness with customer impact awareness

### Typical Handoffs
- With Product Managers: communicate customer pain points and priority shifts
- With Project Managers: flag operational impact and escalation needs
- With Release Manager: coordinate customer-facing communication during launches or incidents

### When to Engage
- When customer-reported issues impact adoption or trust
- Before major releases to validate customer readiness
- During incidents, known issue communication, and post-release reviews

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles complement the core project team by clarifying operational ownership across delivery, quality, security, release, and customer impact.
