# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This folder contains comprehensive guides for running projects efficiently and consistently across our organization.

## Quick Navigation

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle
- **[Project Initiation](./octoacme-project-initiation.md)** — How to validate ideas, align stakeholders, and authorize new work
- **[Project Planning](./octoacme-project-planning.md)** — Breaking work into actionable plans, defining backlog items, and managing dependencies
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, quality standards, and blocker escalation
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identifying and managing risks, stakeholder communication, and escalation paths
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardized release process, deployment checklist, and rollback procedures
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and converting them into actionable improvements
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of key project roles (PMs, Product Managers, Developers) and their responsibilities

## Project Lifecycle at a Glance

1. **Initiation** — Define the problem, stakeholders, and high-level timeline
2. **Planning** — Create detailed backlog, estimate scope, and identify dependencies
3. **Execution** — Build, test, review, and iterate on deliverables
4. **Release** — Deploy to production with proper verification and communication
5. **Close & Retrospective** — Capture learnings and plan improvements

## Core Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Ship small, testable increments
- **Clear ownership:** Each project has named PM and Product Lead
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## OctoAcme Project Management Processes Overview

OctoAcme operates on a structured, customer-first project lifecycle that emphasizes iterative delivery and clear ownership. The organization follows five core phases: Initiation, Planning, Execution, Release, and Retrospective & Continuous Improvement. Each project is guided by two key leadership roles—a Project Manager who coordinates delivery schedules and manages risks, and a Product Manager who defines outcomes and measures success. This dual-leadership approach, combined with developers, QA/testing specialists, and stakeholders, ensures that projects balance business objectives with technical excellence. The framework prioritizes measurable outcomes through project one-pagers that establish success metrics early, allowing teams to validate ideas before committing significant resources.

During the planning and execution phases, OctoAcme emphasizes clear workflows and structured collaboration. Projects begin with a lightweight initiation gate where stakeholders align on problem statements, timelines, and resource needs. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs, defined acceptance criteria, and comprehensive risk registers. Execution follows a disciplined rhythm of daily standups (15 minutes), weekly delivery syncs, and sprint-based planning. The organization uses GitHub Projects for workflow visualization with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and enforces small, reviewable pull requests (≤400 lines) with automated CI testing and at least one approval before merging.

Quality assurance and risk management are embedded throughout the project lifecycle. Teams implement unit tests, integration tests, and end-to-end smoke tests for critical flows, with security scanning in CI pipelines. The approach includes a formal risk register with impact/probability assessments, and a three-level blocker escalation path (team triage → PM escalation → sponsor-level). Communication is intentional and multi-directional: weekly syncs between PM and Product Manager, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations as needed. Risk updates and status reports follow standard templates to ensure consistency.

Finally, OctoAcme closes the loop through structured releases and continuous improvement. All releases require pre-release verification (acceptance criteria met, passing CI/security scans, smoke tests, and rollback plans), followed by post-deployment verification and stakeholder announcements. After each sprint, release, or milestone, teams conduct 45–75 minute retrospectives to capture learnings and identify 2–3 prioritized action items. These improvements are tracked in the project backlog with clear owners and success criteria, creating a culture of psychological safety and iterative enhancement. This end-to-end approach—from validated initiation through continuous learning—enables OctoAcme to deliver reliable, customer-focused outcomes while reducing single-person dependency and maintaining institutional knowledge.

## Getting Started

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation](./octoacme-project-initiation.md) guide
- **Need to manage risk?** See [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Preparing for release?** Review [Release & Deployment](./octoacme-release-and-deployment.md)
- **Running a retrospective?** Check [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Reference the appropriate guide based on your current project phase
- Use persona definitions from [Roles & Personas](./octoacme-roles-and-personas.md) to understand team responsibilities
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context for additional guidance
