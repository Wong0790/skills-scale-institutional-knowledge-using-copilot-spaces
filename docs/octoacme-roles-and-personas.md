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

### Interaction with Other Roles
- Partner with QA/Testing Lead on test coverage and acceptance criteria validation
- Collaborate with Security role on code reviews and security design considerations
- Report blockers and risks to Project Manager during standups
- Engage with Product Manager on feature clarifications and acceptance criteria

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

### Interaction with Other Roles
- Report to Product Lead on roadmap alignment and strategic priorities
- Partner with Project Manager on backlog prioritization and scope management
- Communicate acceptance criteria and success metrics to Developers and QA
- Escalate risks and major decisions to Product Lead and Sponsor as needed

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

### Interaction with Other Roles
- Partner with Product Manager on backlog and milestone management
- Facilitate communication between Developers, QA, and Stakeholders
- Escalate blockers and risks to Product Lead and Sponsor
- Coordinate with Security role on security review timelines and risk assessments

---

## Product Lead

### Role Summary
Product Lead owns product strategy and roadmap alignment across the organization. They serve as the primary strategic advisor for product initiatives and approval authority for major project decisions and trade-offs.

### Responsibilities
- Define and communicate product strategy and vision
- Review and approve project one-pagers and success metrics during initiation
- Partner with Product Manager on prioritization and roadmap alignment
- Resolve cross-functional dependencies and prioritization conflicts
- Approve major scope changes and timeline adjustments
- Serve as primary escalation point for high-impact decisions

### Goals
- Ensure projects align with organizational strategy
- Make clear, strategic prioritization decisions across competing initiatives
- Enable cross-functional collaboration and minimize scope creep
- Drive measurable business and customer value

### Typical Communication
- Weekly strategic sync with Product Manager
- Project initiation gate approvals and reviews
- Escalation resolution and decision logs
- Stakeholder and executive briefings on strategic initiatives

### Interaction with Other Roles
- Review and approve projects initiated by Product Managers
- Collaborate with Sponsor on strategic trade-offs and resource allocation
- Provide strategic context to Project Manager for risk assessment
- Support Product Manager in cross-team dependency resolution

---

## QA/Testing Lead

### Role Summary
QA/Testing Lead defines and owns quality standards, test strategies, and acceptance criteria validation. They ensure products meet quality gates before release and collaborate with Developers on test coverage.

### Responsibilities
- Define test strategy, test plans, and quality acceptance criteria
- Validate acceptance criteria are met before features move to done
- Coordinate test coverage across unit, integration, and end-to-end testing
- Track and report quality metrics and test coverage
- Identify and prioritize quality risks
- Approve readiness for deployment and release

### Goals
- Ensure quality standards are consistently met across releases
- Reduce post-release defects and incidents
- Enable fast, confident deployments
- Maintain high test coverage and observability

### Typical Communication
- Daily collaboration with Developers on test cases and coverage
- Weekly QA status updates during delivery syncs
- Release readiness assessments and test reports
- Quality metrics and trend analysis

### Interaction with Other Roles
- Partner with Developers on test design and implementation
- Collaborate with Product Manager to validate acceptance criteria clarity
- Report quality metrics and readiness to Project Manager
- Coordinate with Security role on security testing and validation

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsor/Executive Stakeholder provides business context, funding decisions, and approval authority for major project decisions. They are the executive champion and decision-maker for project governance.

### Responsibilities
- Provide business rationale and success metrics for project initiation
- Approve funding and resource allocation for projects
- Review and approve major scope changes, timeline adjustments, or trade-offs
- Receive escalated risks and blockers impacting business outcomes
- Participate in project initiation gates and major milestones
- Remove organizational impediments to project success

### Goals
- Ensure projects deliver measurable business value
- Make clear, timely decisions on prioritization and resources
- Reduce organizational risk and unplanned rework
- Enable predictable, successful delivery

### Typical Communication
- Project initiation and gating decisions
- Escalation and decision logs for major issues
- Monthly or milestone-based executive status updates
- Business impact and risk reporting

### Interaction with Other Roles
- Partner with Product Lead on strategic prioritization and resource allocation
- Receive risk escalations from Project Manager
- Approve project one-pagers and success metrics from Product Manager
- Make final decisions on major scope or timeline changes

---

## Security/Compliance Role

### Role Summary
Security/Compliance Role reviews designs and code for security risks, manages security incident response, and ensures compliance with organizational and regulatory requirements. They are embedded in the development lifecycle to prevent security issues before they reach production.

### Responsibilities
- Review project designs and code for security vulnerabilities and risks
- Approve security scanning tools and processes in CI/CD pipelines
- Assess and prioritize security-related risks in the risk register
- Own security incident escalation and response procedures
- Partner with Product Manager on security-related success metrics
- Ensure compliance with organizational security policies and standards

### Goals
- Prevent security vulnerabilities from reaching production
- Minimize security incidents and their impact
- Build security awareness across the product and delivery teams
- Maintain compliance with regulatory and organizational requirements

### Typical Communication
- Code review participation and security feedback
- Security risk assessments and mitigation planning
- Security incident escalation and response coordination
- Security policy updates and team training

### Interaction with Other Roles
- Review code with Developers and provide security guidance
- Collaborate with Product Manager on security requirements and acceptance criteria
- Escalate high-severity security risks to Project Manager and Sponsor
- Partner with QA/Testing Lead on security testing and validation

---

## Stakeholders (Functional Groups)

### Role Summary
Stakeholders represent functional teams or business areas that depend on or consume project output. They provide critical input on requirements, priorities, and success metrics from their functional perspective.

### Responsibilities
- Provide functional requirements and acceptance criteria from their area
- Contribute to success metrics and definition of done
- Participate in project reviews and demos
- Communicate project status and outcomes to their teams
- Raise concerns and dependencies that affect their area
- Escalate blockers or trade-offs that impact their business operations

### Goals
- Ensure project outcomes meet functional area needs
- Reduce surprises and integrate seamlessly with dependent systems
- Enable adoption and value realization in their functional area
- Maintain clear communication and alignment across teams

### Typical Communication
- Project kickoff and planning sessions
- Weekly or milestone-based status updates
- Demo and review sessions
- Dependency and risk escalation communications

### Interaction with Other Roles
- Partner with Product Manager on requirements definition and prioritization
- Provide feedback to Developers on acceptance criteria clarity
- Receive project status from Project Manager
- Collaborate with other Stakeholders on cross-functional dependencies

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to interaction patterns to understand how roles collaborate on projects and resolve conflicts.
- Cross-reference with process documents (Project Initiation, Planning, Execution, Release, Risk Management) to see how personas engage at each lifecycle stage.
