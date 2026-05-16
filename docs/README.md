# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management documentation repository. This is your central hub for understanding how OctoAcme runs projects, manages teams, and delivers value to customers.

## Overview of OctoAcme's Project Management Approach

OctoAcme follows a structured five-phase project lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**. The approach is grounded in five core principles: customer-first prioritization, iterative delivery of small testable increments, clear ownership (each project has a named Project Manager and Product Manager), data-informed decision-making, and psychological safety that encourages team feedback and learning. Projects begin with a lightweight initiation phase to validate business need, confirm stakeholders, and define success metrics through a Project One-pager. This gates the move into planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a prioritized backlog is created. The structured lifecycle ensures alignment early and reduces wasteful rework downstream.

OctoAcme operates with three primary delivery roles: **Developers** (who implement features, write tests, and participate in design reviews), **Product Managers** (who define what should be built, prioritize the roadmap, and measure outcomes), and **Project Managers** (who coordinate schedules, manage risks, and facilitate communication across stakeholders). Execution follows a structured workflow using GitHub Projects with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible) and include issue links, acceptance criteria, and automated CI checks before review. Communication is disciplined with daily 15-minute standups focused on progress and blockers, weekly delivery syncs, sprint/milestone reviews, and a three-tier escalation path (team triage → PM to Product Lead → sponsor-level) for blockers. Stakeholder updates flow monthly or at key milestones, ensuring transparency throughout the lifecycle.

Quality is built into every phase through multiple mechanisms: unit tests and integration tests for new logic, end-to-end smoke tests for critical flows before release, automated security scanning in CI, and manual QA for feature acceptance when needed. Definition of Done (DoD) is documented upfront and enforced during sprint planning to ensure work meets quality gates. Beyond individual releases, OctoAcme emphasizes organizational learning through regular retrospectives held after sprints, releases, or important milestones. Retrospectives follow a structured format (what went well, what could improve, action items) and are time-boxed to 45–75 minutes to maintain focus. Action items are tracked in the project backlog with clear owners and timelines, and outstanding actions are reviewed weekly in PM syncs. This commitment to continuous improvement, paired with risk and dependency tracking via a regularly updated Risk Register, ensures the organization incrementally refines its execution capabilities while maintaining psychological safety to encourage candid feedback.

---

## Documentation Map

The OctoAcme project management processes are documented across several guides. Use this map to find the guidance you need:

| Document | Purpose | Best For |
|----------|---------|----------|
| [Project Management Overview](octoacme-project-management-overview.md) | Framework, principles, and core roles for OctoAcme projects | New team members, stakeholders unfamiliar with OctoAcme |
| [Project Initiation](octoacme-project-initiation.md) | Steps to validate and authorize new work | Project leads starting a new initiative |
| [Project Planning](octoacme-project-planning.md) | Converting initiatives into actionable plans and backlogs | Product managers, project managers, delivery leads |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Managing day-to-day execution and tracking progress | Development teams, scrum masters, daily practitioners |
| [Risks & Communication](octoacme-risks-and-communication.md) | Identifying, managing, and communicating risks and dependencies | Project managers, product leads, stakeholders |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardizing releases to production and managing rollbacks | DevOps, release managers, deployment leads |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting them into improvements | Scrum masters, team leads, retrospective facilitators |
| [Roles & Personas](octoacme-roles-and-personas.md) | Defining typical roles and responsibilities in OctoAcme projects | Anyone needing clarity on team structure and expectations |

---

## Quick Start: Where to Begin

### For Developers
1. Start with [Project Management Overview](octoacme-project-management-overview.md) to understand the overall framework
2. Review [Execution & Tracking](octoacme-execution-and-tracking.md) for daily workflows and PR practices
3. Check [Roles & Personas](octoacme-roles-and-personas.md) to understand developer responsibilities

### For Product Managers
1. Review [Project Management Overview](octoacme-project-management-overview.md) for the high-level framework
2. Dive into [Project Initiation](octoacme-project-initiation.md) to learn how to kick off new work
3. Study [Project Planning](octoacme-project-planning.md) to prioritize and structure backlogs
4. Reference [Risks & Communication](octoacme-risks-and-communication.md) for stakeholder management

### For Project Managers
1. Start with [Project Management Overview](octoacme-project-management-overview.md)
2. Review [Project Initiation](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md)
3. Focus on [Execution & Tracking](octoacme-execution-and-tracking.md), [Risks & Communication](octoacme-risks-and-communication.md), and [Release & Deployment](octoacme-release-and-deployment.md)
4. Reference [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) for post-project learning

### For Stakeholders
1. Review [Project Management Overview](octoacme-project-management-overview.md) for context
2. Reference [Risks & Communication](octoacme-risks-and-communication.md) for status updates and escalation paths

---

## Key Artifacts

OctoAcme projects typically produce and maintain these key artifacts:

- **Project Charter / One-pager** — Problem statement, objectives, success metrics, stakeholders, timeline
- **Roadmap and Release Plan** — High-level sequencing and delivery milestones
- **Sprint/Iteration Backlog** — Prioritized work with acceptance criteria and estimates
- **Acceptance Criteria & Definition of Done** — Clear expectations for work completion
- **Risk Register** — Identified risks, impact, mitigation strategies, and status
- **Retrospective Notes & Action Items** — Learnings and follow-up improvements

---

## Communication Cadence

- **Daily Standups** — 15 minutes; focus on progress, blockers, dependencies
- **Weekly PM Sync** — Alignment between Project Manager and Product Manager
- **Twice-Weekly Team Standups** — Execution team (or as agreed per project)
- **Weekly Delivery Sync** — Show progress, highlight risks, update roadmap
- **Monthly Stakeholder Updates** — Status reports and milestone reviews
- **Sprint/Milestone Demos** — Review completed work with stakeholders and team
- **Ad-hoc Escalations** — As needed for blockers or critical decisions

---

## How to Use These Docs

- **Keep the Project Charter updated** in your project repository
- **Reference relevant guides** when starting a new project phase
- **Add process-specific docs** to `.copilot/` if you want Copilot Spaces to use them as context
- **Suggest improvements** by opening an issue with the "Add Content to Project Management Process Docs" template
- **Stay synchronized** — these docs evolve with team feedback and lessons learned

---

## Contributing to This Documentation

Have feedback, ideas, or lessons learned to share? Help us improve this documentation:

1. **Request an update** — Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
2. **Propose a change** — Open a pull request with your suggested edits
3. **Ask a question** — Open a discussion or issue if something is unclear

Your insights help us scale institutional knowledge across OctoAcme teams.

---

*Last updated: 2026-05-16*
