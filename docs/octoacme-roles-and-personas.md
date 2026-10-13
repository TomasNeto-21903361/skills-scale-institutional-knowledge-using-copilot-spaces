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

## Engineering Lead

### Role Summary
The Engineering Lead provides technical direction for a project or major initiative, balancing short-term delivery needs with long-term architecture and maintainability.

### Responsibilities
- Set and communicate technical strategy and architecture for the project
- Review and approve major design decisions and technical trade-offs
- Identify and mitigate technical risks and dependencies
- Mentor developers and help unblock technical issues
- Ensure code quality and enforce engineering standards

### Interactions
- Works with Product Managers to align technical feasibility with product goals
- Collaborates with Project Managers on delivery timelines and risk mitigation
- Escalates infrastructure or platform needs to Platform/SRE
- Participates in design and PR reviews with Developers

---

## UX Researcher / Designer

### Role Summary
The UX Researcher / Designer ensures the product is usable, accessible, and validated with real users. They translate user needs into actionable designs and acceptance criteria.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define UX acceptance criteria and accessibility checks
- Maintain design system components and guidelines
- Validate solutions against user needs before handoff

### Interactions
- Collaborates with Product Managers to inform requirements and success metrics
- Works with Developers to hand off designs and clarify interactions
- Participates in sprint demos and acceptance for UX-related criteria
- Shares findings with stakeholders to guide prioritization

---

## Platform / SRE

### Role Summary
The Platform / SRE team owns production reliability, environment provisioning, and operational tooling that enable safe, repeatable delivery.

### Responsibilities
- Manage and provision environments (staging, prod, etc.)
- Build and maintain CI/CD pipelines, runbooks, and observability tooling
- Support incident response and post-incident remediation
- Provide guidance on non-functional requirements (scalability, SLOs)
- Automate deployment, rollbacks, and routine operations

### Interactions
- Advises Engineering Leads and Developers on infrastructure constraints and best practices
- Works with Release Manager to validate deployment readiness and post-deploy checks
- Collaborates with Project Managers on timeline impact for platform tasks
- Partners with Support/Ops during incidents and major releases

---

## Security Owner

### Role Summary
The Security Owner coordinates threat modeling, security reviews, and vulnerability triage to ensure features meet security and compliance expectations.

### Responsibilities
- Perform threat modeling and security risk assessments
- Review architecture and PRs for security concerns
- Triage and track vulnerabilities; define mitigations
- Ensure compliance checks and necessary audits are completed
- Provide security acceptance criteria for releases

### Interactions
- Works with Engineering Lead and Developers during design and implementation
- Notifies Product and Project Managers of critical security risks and remediation timelines
- Coordinates with Platform/SRE for secure deployment and incident handling
- Escalates severe findings to Product Lead or Sponsor as needed

---

## Data Analyst / Data Engineer

### Role Summary
The Data Analyst / Data Engineer ensures projects have the right telemetry and validated data pipelines to measure success and inform decisions.

### Responsibilities
- Define metrics and events required for success measurement
- Design and validate data pipelines and dashboards
- Ensure data quality, lineage, and access controls
- Support experiment instrumentation and analysis
- Provide analytical insights post-release

### Interactions
- Collaborates with Product Managers to define measurable success metrics
- Works with Developers and Platform/SRE to instrument telemetry and validate pipelines
- Delivers dashboards to stakeholders and supports release verification of analytics
- Advises on data-related trade-offs during planning

---

## Release Manager

### Role Summary
The Release Manager coordinates release activities, ensuring deployments are planned, communicated, and executed with rollback and mitigation plans in place.

### Responsibilities
- Plan release windows and coordinate cross-team schedules
- Run deployment checklists and verify pre/post-deploy steps
- Draft release notes and communicate to stakeholders
- Ensure rollback plans and mitigation steps are ready
- Validate that release acceptance criteria are met

### Interactions
- Coordinates with Project Manager, Platform/SRE, and Support for release readiness
- Works with Product Manager and Engineering Lead to confirm acceptance criteria
- Notifies stakeholders and support teams of release timing and risks
- Owns the release communication and post-release verification

---

## Support / Ops Representative

### Role Summary
The Support / Ops Representative ensures customer-facing teams are prepared for new releases and that operational playbooks are up to date.

### Responsibilities
- Update playbooks and troubleshooting guides for new features
- Train support teams on expected behaviors and common failure modes
- Validate observability and customer-facing messaging
- Triage customer issues and feed insights back to the team

### Interactions
- Receives release notes and runbooks from the Release Manager
- Works with Platform/SRE on incident runbooks and escalation paths
- Provides feedback to Product and Project Managers on customer impact
- Escalates recurring issues into backlog items for Developers

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
