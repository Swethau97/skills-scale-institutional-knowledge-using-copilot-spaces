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

## QA/Quality Assurance Engineer

### Role Summary
Quality Assurance Engineers define and execute testing strategies to ensure software meets quality standards, acceptance criteria, and regulatory requirements before release. They collaborate with developers and product teams to prevent defects and maintain reliability.

### Responsibilities
- Develop and maintain comprehensive test plans aligned with acceptance criteria
- Execute manual and automated testing across all environments (development, staging, production)
- Identify, document, and track defects and quality issues using structured reporting
- Collaborate with developers to resolve quality concerns and validate fixes
- Perform regression testing and validate fixes after code changes
- Document test results, coverage metrics, and quality dashboards
- Recommend and implement test automation strategies
- Participate in design reviews to identify testability concerns

### Goals
- Prevent production defects through proactive and comprehensive testing
- Ensure software reliability, usability, and user satisfaction
- Maintain traceability between requirements and test coverage
- Reduce defect escape rate and post-release issues

### Typical Communication
- Test plans and test case documentation
- Bug reports and defect tracking systems
- Quality dashboards and metrics reports
- Sprint planning and retrospectives participation
- Test automation documentation and scripts

### Interactions with Other Personas
- Works closely with **Developers** during testing phases, code reviews, and defect resolution
- Validates acceptance criteria defined by **Product Managers**
- Reports quality risks and blockers to **Project Managers** for escalation and timeline impact
- Partners with **Technical Leads** on test automation architecture and performance testing strategies
- Supports **DevOps Engineers** with test environment requirements and monitoring setup
- Coordinates with **Release Managers** on release validation and go/no-go decisions

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance, make critical technical decisions, and ensure the engineering team maintains code quality, system design excellence, and long-term scalability. They serve as technical mentors and decision-makers for complex engineering challenges.

### Responsibilities
- Design system architecture and define technical standards for the team
- Review and approve major technical decisions and design proposals
- Mentor developers and conduct comprehensive code reviews
- Identify technical debt, propose refactoring initiatives, and prioritize them
- Assess technical feasibility of proposed features and propose alternatives
- Lead technical discussions, design reviews, and spike investigations
- Evaluate and recommend technology choices and frameworks
- Ensure code maintainability, performance, and security standards

### Goals
- Maintain system scalability, reliability, and maintainability as projects grow
- Foster engineering excellence, knowledge sharing, and best practices
- Reduce technical risk, complexity, and long-term technical debt
- Enable teams to make informed technical decisions

### Typical Communication
- Design reviews and architecture documentation (RFCs, ADRs)
- Technical spike investigations and recommendations
- Code review feedback, mentoring, and architectural guidance
- Technical leadership in decision logs
- Guidance on technology adoption and deprecation

### Interactions with Other Personas
- Partners with **Product Managers** to assess feature feasibility, estimate effort, and identify technical trade-offs
- Guides **Developers** through architectural decisions, design patterns, and code quality standards
- Advises **Project Managers** on technical risks, dependencies, timeline impacts, and resource requirements
- Supports **QA Engineers** on test automation architecture and performance testing strategies
- Collaborates with **DevOps Engineers** on infrastructure requirements and deployment architecture
- Works with **Release Managers** on release planning and technical deployment considerations
- Provides strategic technical input to **Stakeholders/Sponsors** on long-term technical direction

---

## Release Manager

### Role Summary
Release Managers oversee release planning, coordination, and deployment processes to ensure smooth, reliable transitions from development to production with minimal disruption. They serve as the central orchestrator for all release activities and stakeholder communication.

### Responsibilities
- Create and maintain release schedules, roadmaps, and timelines
- Coordinate release activities and dependencies across all teams
- Manage version control, tagging, branching strategies, and deployment approvals
- Prepare comprehensive release notes, deployment documentation, and runbooks
- Communicate release status and timelines to stakeholders
- Manage rollback procedures, contingency plans, and post-release monitoring
- Maintain release checklists and ensure quality gates are met
- Coordinate code freezes and communication of release windows

### Goals
- Ensure timely and reliable releases to production
- Minimize deployment risks, failures, and unplanned downtime
- Maintain clear, transparent communication with all stakeholders
- Establish predictable, repeatable release processes

### Typical Communication
- Release plans and deployment schedules
- Release notes and deployment checklists
- Post-release status reports and incident updates
- Stakeholder release briefings and go/no-go decision meetings
- Deployment logs and rollback documentation

### Interactions with Other Personas
- Collaborates with **Project Managers** on release scheduling, timeline planning, and stakeholder communication
- Coordinates with **Developers** on code freezes, version tagging, and deployment readiness
- Partners with **QA Engineers** on release validation testing, defect triage, and go/no-go recommendations
- Works with **Product Managers** on feature release communication and customer-facing release messaging
- Depends on **DevOps Engineers** for deployment infrastructure, automation, and post-release monitoring
- Consults **Technical Leads** on technical deployment considerations and rollback strategies
- Reports to **Stakeholders/Sponsors** on release status and business impact

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps and Infrastructure Engineers design, build, and maintain the infrastructure, tools, and processes that enable rapid, reliable development, testing, and production environments. They enable teams through automation and operational excellence.

### Responsibilities
- Design and maintain CI/CD pipelines, automation, and deployment processes
- Manage cloud infrastructure, servers, networking, and storage resources
- Implement comprehensive monitoring, logging, and observability solutions
- Ensure system security, compliance, disaster recovery, and business continuity
- Optimize infrastructure performance, reliability, and cost efficiency
- Support troubleshooting, incident response, and post-incident analysis
- Maintain infrastructure documentation, runbooks, and operational procedures
- Provide self-service tools and enable developer productivity

### Goals
- Enable rapid, reliable deployments with automated quality gates
- Ensure high system availability, performance, and security
- Reduce operational overhead through automation and self-service
- Support incident-free operations with proactive monitoring

### Typical Communication
- Infrastructure documentation, runbooks, and operational guides
- Incident reports, post-mortems, and remediation plans
- Performance metrics, dashboards, and capacity planning reports
- CI/CD pipeline documentation and deployment logs
- Infrastructure as Code reviews and deployment guidance

### Interactions with Other Personas
- Enables **Developers** with development environments, CI/CD tools, and deployment automation
- Provides **QA Engineers** with proper test environments, monitoring setup, and performance testing infrastructure
- Shares operational insights and system health with **Project Managers**
- Supports **Technical Leads** with infrastructure recommendations and architectural considerations
- Works closely with **Release Managers** on deployment infrastructure, automation, and post-release monitoring
- Escalates operational issues and constraints to **Project Managers** and **Stakeholders/Sponsors**

---

## Stakeholder/Executive Sponsor

### Role Summary
Stakeholders and Executive Sponsors provide business context, strategic alignment, and resource approval for projects. They ensure project outcomes align with organizational strategy and goals, and remove organizational blockers.

### Responsibilities
- Define business objectives, success metrics, and expected ROI for projects
- Approve project scope, budget, and resource allocation
- Remove organizational blockers and escalate issues requiring executive intervention
- Provide strategic feedback and business context to guide project direction
- Communicate project importance and status to the broader organization
- Review project progress against business objectives and approve major scope changes
- Make resource trade-off decisions and prioritize competing initiatives
- Ensure alignment with organizational strategy and goals

### Goals
- Ensure projects deliver measurable business value aligned with strategy
- Maintain executive visibility, transparency, and alignment across leadership
- Enable project teams to succeed with necessary resources and organizational support
- Maximize ROI and business impact of engineering investments

### Typical Communication
- Executive status updates and steering committee meetings
- Business requirement specifications and success criteria
- Budget approvals and resource allocation decisions
- Strategic alignment reviews and leadership briefings
- Escalation resolutions and executive decisions

### Interactions with Other Personas
- Provides business context, priorities, and strategic direction to **Product Managers**
- Reviews project status, approves changes, and provides executive sponsorship to **Project Managers**
- May escalate technical constraints and resource needs raised by **Technical Leads**
- Depends on **Developers** and engineering teams to deliver business value
- Supports **Release Managers** with stakeholder communication and go/no-go approval
- Receives operational insights and escalations from **DevOps Engineers** and other team members
- Relies on **QA Engineers** to ensure quality standards and product reliability

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interactions between personas to understand dependencies and collaboration points in project workflows.
- Use role responsibilities and goals to determine appropriate decision-makers and stakeholders for different project activities.
