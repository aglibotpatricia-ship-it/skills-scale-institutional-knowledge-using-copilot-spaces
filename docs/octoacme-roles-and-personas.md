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

## Product Lead

### Role Summary
The Product Lead steers product strategy, resolves trade-offs, and ensures the work stays aligned with business outcomes and customer needs. They provide senior product direction while supporting the delivery team.

### Responsibilities
- Review and approve project one-pagers and overarching scope
- Validate that goals and success metrics align with customer and business priorities
- Prioritize competing product demands and resolve cross-functional trade-offs
- Partner with stakeholders to confirm roadmap direction and critical milestones
- Help determine go/no-go decisions at key project gates

### Goals
- Keep product direction clear, consistent, and measurable
- Guide teams toward the highest-value outcomes
- Reduce ambiguity in scope and decision-making

### Typical Communication
- Product strategy reviews and roadmap checkpoints
- Executive and stakeholder alignment meetings
- Prioritization and trade-off discussions with Product Managers and Project Managers

### Interaction with Existing Roles
- Works with Product Managers to confirm priorities, outcomes, and success metrics
- Collaborates with Project Managers to review milestones, dependencies, and risks
- Provides strategic input to Developers and QA when requirements or release scope need clarification
- Escalates unresolved business or priority conflicts to the Sponsor / Executive Stakeholder

---

## QA / Testing Lead

### Role Summary
The QA / Testing Lead defines the quality strategy for the project and ensures work meets acceptance criteria, release standards, and user expectations before delivery.

### Responsibilities
- Develop and maintain test plans, quality gates, and validation strategy
- Validate acceptance criteria and release readiness across features and milestones
- Coordinate manual and automated testing efforts with engineering teams
- Identify product and regression risks before release
- Partner with release and operational teams on pre-deployment verification

### Goals
- Reduce defects and quality risk before release
- Improve confidence in product readiness and user experience
- Ensure the project meets agreed acceptance criteria consistently

### Typical Communication
- Test planning and validation reviews
- Quality risk updates during standups and sprint reviews
- Release readiness and sign-off checkpoints

### Interaction with Existing Roles
- Works with Developers to define test coverage, defect triage, and bug-fix validation
- Aligns with Product Managers on acceptance criteria and user-facing quality expectations
- Coordinates with the Release / DevOps Engineer on deployment smoke tests and rollout checks
- Escalates unresolved quality or release risk to the Project Manager or Product Lead

---

## Sponsor / Executive Stakeholder

### Role Summary
The Sponsor / Executive Stakeholder provides strategic sponsorship, funding, and authority for the project. They ensure the effort remains aligned with business goals and support difficult prioritization decisions.

### Responsibilities
- Approve the project charter, business case, and major scope decisions
- Allocate budget, staffing, and priority across competing initiatives
- Resolve high-level conflicts, trade-offs, and strategic dependency issues
- Review major milestones and progress against business goals
- Support escalation for risk, timeline, or resource challenges that require executive action

### Goals
- Protect business value and strategic alignment
- Enable successful delivery through sponsorship and prioritization
- Maintain accountability for project outcomes at the executive level

### Typical Communication
- Executive status updates and steering committee meetings
- Decision points on business priority, funding, or major scope changes
- Escalation updates for cross-functional or organizational blockers

### Interaction with Existing Roles
- Receives updates from Project Managers and Product Leads on health, milestones, and risks
- Reviews key decisions with Product Leads and Product Managers before approving major changes
- Provides final authority when cross-team conflict or business priority needs resolution
- May sponsor issue escalation for security, revenue, or customer-impacting decisions

---

## Security Officer

### Role Summary
The Security Officer ensures security requirements are built into project work from planning through release. They help identify, mitigate, and communicate security risks and compliance concerns.

### Responsibilities
- Define security requirements, risk controls, and review expectations
- Evaluate project designs, dependencies, and code paths for security impact
- Coordinate security scanning, review findings, and track remediation
- Support incident triage and security escalation for critical issues
- Partner with teams to improve secure development practices and readiness

### Goals
- Reduce exposure to security vulnerabilities and compliance issues
- Enable safe delivery without slowing team velocity unnecessarily
- Ensure incidents are managed consistently and transparently

### Typical Communication
- Security review checkpoints and risk assessments
- Incident communication and review updates
- Security readiness checks during release planning and deployment

### Interaction with Existing Roles
- Works with Developers to review secure coding practices and remediation plans
- Aligns with Product Managers and Project Leads on risk acceptance and release decisions
- Supports release and deployment teams with security checks before production rollout
- Coordinates with the Project Manager for escalation tracking and incident follow-up

---

## Release / DevOps Engineer

### Role Summary
The Release / DevOps Engineer manages deployment automation, environment readiness, and production release execution so projects can ship safely and predictably.

### Responsibilities
- Maintain CI/CD pipelines, integration workflows, and automation standards
- Prepare staging and production environments for deployment
- Execute or coordinate release trains, deployments, and rollback actions
- Monitor post-deployment health and support incident mitigation
- Ensure operational readiness and documentation for deployment processes

### Goals
- Reduce deployment risk and recovery time
- Improve release consistency and automation quality
- Support product delivery without operational surprises

### Typical Communication
- Deployment readiness reviews and release checklists
- Release status updates and rollback decision points
- Operational health and incident coordination during rollout windows

### Interaction with Existing Roles
- Partners with Developers to ensure builds, pipelines, and deployment requirements are in place
- Collaborates with QA / Testing Lead on smoke tests and pre-release verification
- Works with Project Managers to confirm release windows, communication, and rollback plans
- Escalates production-impacting issues to the Security Officer or Sponsor as needed

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master / Agile Coach creates a healthy delivery rhythm, removes process impediments, and helps the team improve how it works together over time.

### Responsibilities
- Facilitate planning, standups, retrospectives, and team ceremonies
- Help the team maintain clear backlog flow, scope focus, and delivery discipline
- Identify blockers, cross-team dependencies, and process friction
- Coach teams on agile practices, continuous improvement, and collaboration habits
- Support healthy project board management and meeting facilitation

### Goals
- Improve team effectiveness, transparency, and flow
- Reduce friction caused by unclear process or unresolved blockers
- Help teams learn and adapt continuously

### Typical Communication
- Team facilitation and sprint planning meetings
- Retrospective follow-up and process improvement discussions
- Dependency and blocker tracking with Project Managers and team leads

### Interaction with Existing Roles
- Supports Project Managers with facilitation, planning, and issue tracking
- Works with Product Managers and Product Leads to clarify priorities and delivery constraints
- Helps Developers and QA maintain focus on team flow, quality, and actionable feedback
- Reinforces the project’s continuous improvement practices through retrospectives and action tracking

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles work together to create clearer accountability, stronger communication, and more predictable project execution.
