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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define quality standards, manage test planning, and ensure acceptance criteria are validated before release. They collaborate with developers, product managers, and release engineers to deliver high-quality software.

### Responsibilities
- Define quality standards and test strategy aligned with project objectives
- Create and maintain test plans aligned with acceptance criteria
- Coordinate manual and automated testing efforts
- Report quality metrics and blockers to PM/Project Manager
- Validate acceptance criteria before handoff to production
- Identify and communicate quality risks and recommendations

### Goals
- Catch defects early and reduce production incidents
- Ensure customer-facing features meet usability and reliability standards
- Enable confident releases through comprehensive testing

### Typical Communication
- Sprint planning and backlog refinement (quality criteria input)
- Daily standups (status, blockers, test progress)
- Weekly quality reports and metrics
- Pre-release quality gates and sign-offs
- Cross-functional collaboration with developers and technical leads on test design

### Interaction with Other Roles
- Works with **Developers** to clarify test requirements and validate code quality
- Reports quality status and risks to **Project Managers** and **Product Managers**
- Collaborates with **Technical Leads** on test automation strategies
- Partners with **DevOps Engineers** on test environment provisioning and deployment validation

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide technical direction, mentor developers, and ensure designs support project goals and operational requirements. They act as a bridge between strategic product decisions and implementation details.

### Responsibilities
- Guide technical approach and architecture decisions aligned with project goals
- Review designs and pull requests for scalability, maintainability, and security
- Identify technical risks and propose mitigations
- Mentor developers and help unblock technical challenges
- Collaborate with DevOps and QA on deployment and testing strategies
- Document technical decisions and rationale

### Goals
- Deliver scalable, maintainable solutions
- Reduce technical debt and operational risk
- Accelerate developer productivity through clear technical leadership

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and mentoring sessions
- Risk register updates for technical risks
- Collaboration with Product Managers on feasibility and trade-offs
- Regular sync with DevOps on operational readiness

### Interaction with Other Roles
- Guides **Developers** through technical decision-making and code quality
- Advises **Product Managers** on technical feasibility and trade-offs
- Works with **QA/Testing Leads** to define testability and test coverage strategies
- Partners with **DevOps Engineers** to ensure designs support deployment and observability
- Escalates technical risks to **Project Managers** and **Sponsors**

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps Engineers own deployment pipelines, infrastructure as code, monitoring, and operational readiness. They enable fast, safe deployments and maintain system reliability throughout the project lifecycle.

### Responsibilities
- Design and maintain CI/CD pipelines for automated testing and deployment
- Manage infrastructure and deployment automation
- Define observability and monitoring strategies for production systems
- Support release planning and provide rollback procedures and contingency planning
- Collaborate on security scanning and compliance checks
- Provision and manage test environments for QA and development teams

### Goals
- Enable fast, safe deployments to production
- Maintain system reliability and observability
- Reduce deployment risk and incident recovery time

### Typical Communication
- Release planning and deployment checkpoints
- Post-incident retrospectives and root cause analysis
- Weekly infrastructure/reliability updates
- Collaboration with developers on deployment-related questions
- Coordination with QA on test environment needs

### Interaction with Other Roles
- Supports **Developers** with deployment questions and environment provisioning
- Implements deployment and monitoring recommendations from **Technical Leads**
- Partners with **QA/Testing Leads** on test environment setup and post-deploy validation
- Reports infrastructure risks and readiness to **Project Managers**
- Coordinates with **Sponsors** on deployment windows and production readiness

---

## Sponsor / Stakeholder

### Role Summary
Sponsors provide business context, approve resource allocation, and escalate business-critical risks. They are ultimate decision-makers for project direction and serve as the voice of organizational strategy.

### Responsibilities
- Define business objectives and success metrics for the project
- Approve project charter and major scope changes
- Allocate budget and resources in collaboration with leadership
- Escalate business-impacting risks and decisions
- Provide feedback on deliverables and alignment with organizational goals
- Champion the project and communicate value across the organization

### Goals
- Ensure project delivers measurable business value
- Maintain alignment between project and organizational strategy
- Support team success through timely decision-making and resource availability

### Typical Communication
- Project kickoff and milestone reviews
- Monthly stakeholder updates and status reports
- Escalation paths for critical decisions
- Feedback sessions on deliverables and outcomes
- Budget and resource allocation discussions

### Interaction with Other Roles
- Works with **Project Managers** on planning, risk escalation, and status reporting
- Collaborates with **Product Managers** on objectives and success metrics
- Receives recommendations from **Technical Leads** on feasibility and trade-offs
- Reviews quality and readiness status from **QA/Testing Leads**
- Approves deployment and release decisions with input from **DevOps Engineers**

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional interactions show how roles collaborate throughout the project lifecycle.
