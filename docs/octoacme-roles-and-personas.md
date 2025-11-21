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

## QA Engineers

### Role Summary
QA Engineers validate features against acceptance criteria, design test strategies, and ensure quality standards are met before release. They work closely with developers and product teams to identify issues early and maintain high product reliability.

### Responsibilities
- Create test plans and test cases based on acceptance criteria
- Execute manual and automated tests (functional, regression, integration)
- Report and track defects with clear reproduction steps
- Validate fixes and verify acceptance criteria are met
- Participate in planning to ensure testability and define test data needs

### Goals
- Catch defects before they reach production
- Maintain high coverage of critical user flows
- Reduce time-to-resolve by providing clear defect reports

### Typical Communication
- Daily standups and sprint planning
- Bug reports and test summary reports
- Collaboration with developers on testability and edge cases

---

## UX Designer

### Role Summary
UX Designers research user needs, create wireframes and prototypes, and ensure the product is accessible and intuitive. They translate user problems into design solutions and work with Product Managers and Developers to deliver cohesive user experiences.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Run design sprints and collaborate on design critiques
- Ensure accessibility standards are met (WCAG compliance)
- Provide annotated designs and specifications for development handoff

### Goals
- Deliver intuitive, accessible user experiences
- Validate designs with real user feedback
- Reduce development rework through clear, actionable specs

### How they interact with existing roles
- **Product Manager**: Collaborate on user problems and success metrics; align on priority features
- **Developers**: Hand off annotated mockups with interaction specs, spacing, and accessibility notes
- **QA**: Define expected UI behavior and acceptance criteria for visual and interaction testing

### Examples of deliverables / artifacts
- Annotated wireframes and high-fidelity mockups
- Design system components and style guides
- Usability test reports and research insights
- Accessibility audit checklists

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical implementation. They gather and document requirements, map workflows, and ensure solutions align with business objectives and processes.

### Responsibilities
- Elicit and document detailed requirements from stakeholders
- Create workflow diagrams, process maps, and data models
- Support definition of acceptance criteria and user stories
- Analyze business impact and perform gap analysis
- Facilitate requirements workshops and validation sessions

### Goals
- Ensure solutions meet business needs and constraints
- Reduce ambiguity in requirements
- Improve traceability from business need to delivery

### How they interact with existing roles
- **Product Manager**: Translate high-level vision into detailed requirements
- **Project Manager**: Provide input on scope, dependencies, and timeline feasibility
- **Developers**: Clarify business logic, edge cases, and validation rules
- **QA**: Define expected business outcomes and test scenarios

### Examples of deliverables / artifacts
- Detailed user stories with acceptance criteria
- Business process maps and workflow diagrams
- Requirements traceability matrix
- Data dictionaries and business rules documentation

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain CI/CD pipelines, automate infrastructure, and ensure reliable deployments. They enable fast, safe releases and maintain observability and incident response capabilities.

### Responsibilities
- Design and maintain CI/CD pipelines for automated builds and deployments
- Automate infrastructure provisioning and configuration management
- Set up monitoring, alerting, and log aggregation
- Create and maintain runbooks for deployments and incidents
- Manage release processes and coordinate rollback procedures

### Goals
- Reduce time from code commit to production deployment
- Ensure high availability and quick recovery from incidents
- Automate repetitive tasks and improve system reliability

### How they interact with existing roles
- **Developers**: Collaborate on build and test automation; provide deployment tooling
- **QA**: Set up test environments and integrate automated testing into CI/CD
- **Project Manager**: Coordinate release schedules, communicate deployment windows, and track release readiness

### Examples of deliverables / artifacts
- CI/CD pipeline configurations (e.g., GitHub Actions workflows)
- Infrastructure as Code templates (Terraform, CloudFormation)
- Deployment runbooks and rollback procedures
- Monitoring dashboards and alert configurations

---

## Customer Support

### Role Summary
Customer Support triages incoming issues, gathers user feedback, maintains knowledge base articles, and escalates critical bugs to the engineering team. They are the voice of the customer and help improve product quality and documentation.

### Responsibilities
- Triage and respond to customer inquiries and issues
- Document and escalate bugs with reproduction steps
- Maintain and update knowledge base articles and FAQs
- Gather product feedback and report common pain points
- Follow escalation conventions and tag issues appropriately

### Goals
- Resolve customer issues quickly and effectively
- Reduce repeat issues through improved documentation
- Provide actionable feedback to product and engineering teams

### How they interact with existing roles
- **Product Manager**: Share user feedback, feature requests, and pain point trends
- **Project Manager**: Escalate critical customer-facing issues and coordinate urgent fixes
- **QA**: Provide real-world test scenarios and edge cases from customer reports

### Guidance on issue escalation and tagging conventions
- **Severity tags**: Critical (service down), High (major feature broken), Medium (workaround exists), Low (cosmetic or minor)
- **Escalation path**: Support → PM for prioritization → Engineering triage → Hotfix or backlog
- **Required info**: Steps to reproduce, affected users/accounts, business impact, screenshots/logs

### Examples of deliverables / artifacts
- Knowledge base articles and troubleshooting guides
- Escalated bug reports with reproduction steps
- Customer feedback summaries and trend reports

---

## External Stakeholder

### Role Summary
External Stakeholders provide approvals, governance oversight, and strategic feedback on project direction. They may include clients, partners, regulatory bodies, or executive sponsors who need visibility and input at key milestones.

### Responsibilities
- Review and approve project scope, budget, and major deliverables
- Provide feedback on strategic alignment and business value
- Ensure compliance with governance, legal, or contractual requirements
- Participate in milestone reviews and go/no-go decisions

### Goals
- Ensure project aligns with organizational strategy and compliance
- Mitigate business and regulatory risks
- Maintain transparency and trust through timely communication

### How they interact with existing roles
- **Project Manager**: Primary point of contact for status updates, approvals, and escalations
- **Product Manager**: Align on success metrics, business outcomes, and value delivery

### Interaction cadence for reviews
- **Milestone reviews**: At key gates (e.g., planning approval, release readiness)
- **Monthly updates**: High-level status, risks, and upcoming decisions
- **Ad-hoc escalations**: For scope changes, budget issues, or critical risks

### Examples of deliverables / artifacts
- Approval sign-offs on project charters and budgets
- Feedback on roadmaps and strategic priorities
- Governance and compliance review notes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

