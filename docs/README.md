# OctoAcme Project Management Docs

## Overview

The OctoAcme project management framework provides a structured yet flexible approach to managing cross-functional projects. Our docs guide teams through each phase of the project lifecycle, emphasizing customer value, iterative delivery, clear ownership, and data-informed decisions.

OctoAcme's framework is built on the principle that effective project management requires balancing strategic alignment with operational agility. By centralizing institutional knowledge through these process documents and Copilot Spaces, we enable consistent, repeatable project execution while maintaining psychological safety and continuous improvement.

## Project Lifecycle Overview

| Phase | Purpose | Key Artifact |
|-------|---------|------------------|
| **Initiation** | Validate business need and authorize work | Project One-pager |
| **Planning** | Break work into actionable increments | Release Plan & Backlog |
| **Execution** | Deliver increments, track progress, manage risks | Sprint Board & Risk Register |
| **Release** | Deploy to production safely | Release Notes & Runbook |
| **Retrospective** | Capture learnings and improve | Action Items & Metrics |

## Core Processes at a Glance

**OctoAcme Project Lifecycle and Workflows:**

OctoAcme follows a structured five-phase project lifecycle that begins with **Initiation**—validating business need and aligning stakeholders around a lightweight Project One-pager containing the problem statement, success metrics, and resource requirements. This moves into **Planning**, where approved initiatives are broken down into prioritized, estimated backlog items with clear acceptance criteria and a defined Definition of Done. During the **Execution** phase, teams work in sprints or iterations, utilizing a GitHub Projects board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and following a pull request workflow with small PRs (≤400 lines), automated CI/CD testing, and mandatory code review approvals. The **Release** phase emphasizes pre-release validation including passing security scans, smoke tests, and documented rollback plans, followed by **Retrospectives** to capture learnings and drive continuous improvement.

**Roles and Responsibilities:**

OctoAcme operates with clearly defined roles that balance product thinking with delivery coordination. Product Managers own the product vision, prioritize the backlog, and measure outcomes through success metrics. Project Managers coordinate delivery activities, manage risks and dependencies, facilitate planning and retrospective meetings, and maintain transparent communication across stakeholders. Developers design and build features to acceptance criteria while writing tests, participating in code reviews, and identifying technical risks. This clear ownership model—where each project has a named PM and Product Lead—ensures accountability and reduces silos across the team.

**Communication and Risk Management:**

Communication at OctoAcme follows a disciplined cadence including daily standups (15 minutes focusing on progress and blockers), weekly delivery syncs to review progress and flag risks, and monthly stakeholder updates. The organization maintains a Risk Register that captures risk ID, description, impact/likelihood, owner, and mitigation plan, which is reviewed and updated weekly. Escalation follows a four-level path: team-level triage → PM escalation → Product Lead involvement → Sponsor-level escalation for business-impacting issues.

**Quality Assurance and Execution Standards:**

Quality is embedded throughout OctoAcme's execution approach, with requirements for unit tests on new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. Automated testing and linting run in CI before review, and security scanning is part of the standard pipeline. Demos occur at the end of each sprint or milestone, and manual QA for feature acceptance is performed when needed. An Execution Checklist ensures branching/PR conventions are documented, CI is properly configured, regular demos are scheduled, and the risk register is updated weekly—creating a culture of iterative delivery, measurable outcomes, and continuous learning.

## Process Documentation

### Core Framework
- **[Project Management Overview](./octoacme-project-management-overview.md)** — Start here for principles, roles, key artifacts, and communication cadence
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Understand responsibilities of PMs, Product Managers, Developers, and QA teams

### Phase-Specific Guides
- **[Project Initiation](./octoacme-project-initiation.md)** — Problem validation, stakeholder alignment, and go/no-go decision gate
- **[Project Planning](./octoacme-project-planning.md)** — Backlog creation, estimation, release planning, and dependency management
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Daily execution, team rhythm, quality standards, and blocker escalation
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Pre-release checklist, deployment procedures, and rollback strategies
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Learning capture, action item tracking, and iterative improvement culture

### Cross-Cutting Concerns
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk register, stakeholder communication templates, and escalation paths

## Quick Start Guide

**I'm starting a new project**  
→ Read [Project Initiation](./octoacme-project-initiation.md)  
→ Create a Project One-pager with problem statement, success metrics, and stakeholders  
→ Schedule initiation meeting with delivery team

**I need to estimate and plan work**  
→ Read [Project Planning](./octoacme-project-planning.md)  
→ Create prioritized backlog with acceptance criteria  
→ Define Definition of Done and identify dependencies

**I need to manage risks or communicate status**  
→ Read [Risk Management & Communication](./octoacme-risks-and-communication.md)  
→ Maintain Risk Register with impact, likelihood, and mitigation plans  
→ Use weekly status template for stakeholder updates

**I'm preparing a release**  
→ Read [Release & Deployment](./octoacme-release-and-deployment.md)  
→ Verify all acceptance criteria met and PRs merged  
→ Run smoke tests and prepare release notes

**We just finished a sprint/release**  
→ Read [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)  
→ Conduct retrospective (45–75 minutes)  
→ Identify 2–3 action items with owners and due dates

## Using These Docs with Copilot Spaces

These process documents are designed to be used alongside **Copilot Spaces**, which can ingest these files as context to provide role-specific guidance and project-tailored recommendations. When setting up a Copilot Space for your project:

1. Add relevant process docs from this folder to ground Copilot's knowledge in OctoAcme practices
2. Reference specific personas (Developer, Product Manager, Project Manager) for role-specific prompts
3. Use this README as the entry point to help Copilot understand the full project lifecycle
4. Keep process docs updated in your project repository to maintain alignment

For more information on Copilot Spaces, see the [Copilot Spaces documentation](https://docs.github.com/en/copilot/managing-copilot/managing-copilot-in-your-organization).

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning
- **Transparency**: Maintain a single source of truth for project status and decisions

## Getting Help

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
- **Need a specific template?** Check the relevant phase guide (Initiation, Planning, Execution, Release, Retrospective)
- **Have a question about roles?** See [Roles & Personas](./octoacme-roles-and-personas.md)
- **Facing a blocker or risk?** Consult [Risk Management & Communication](./octoacme-risks-and-communication.md)
