# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This README provides a concise overview of OctoAcme's project management processes and links to every document in this folder.

## Overview

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle with clear artifacts and ownership to keep delivery predictable and transparent. Work progresses through **Initiation → Planning → Execution → Release → Close/Retrospective**. During initiation, teams align on the business need and define measurable outcomes using a **Project One-pager** (problem, goal, success metrics), confirm stakeholders and resourcing, outline milestones, and capture initial risks. A project moves forward once success metrics are clear, stakeholders agree on priority, and team availability is confirmed.

Roles are explicitly defined to reduce ambiguity and speed decision-making. A named **Project Manager (PM)** coordinates delivery — planning, schedules, risks, and communications — while the **Product Manager (PdM)** owns outcomes and prioritization. **Developers** design and implement shippable increments with testing and documentation, and **QA/Testing** validates quality against acceptance criteria. **Stakeholders** contribute inputs and approvals. The team relies on shared artifacts — backlog items with acceptance criteria, Definition of Done, risk register, release notes, and retrospective actions — to ensure everyone is working from the same source of truth.

Day-to-day execution is managed via a project board (columns: **Backlog → Ready → In Progress → In Review → QA → Done**) and a delivery rhythm designed to surface blockers early. OctoAcme uses short **daily standups** for progress and dependency management, a **weekly delivery sync** to review progress and risks, and **demo/reviews** at sprint or milestone boundaries. Risk and dependency handling is formalized through a simple **risk register** (impact / likelihood / owner / mitigation / status) and a clear escalation path that starts with team triage and can escalate through the PM to product leadership and sponsors. Stakeholder updates use a consistent weekly status format covering progress, next steps, risks/blockers, and asks/decisions.

Quality assurance and release discipline are built into the workflow rather than treated as a final step. OctoAcme favors **small pull requests** (around 400 lines when feasible), expects PRs to include issue links and acceptance criteria, and requires CI checks (tests/linting) plus at least one approval before merge. Testing expectations include **unit tests for new logic**, integration testing where relevant, and **end-to-end smoke tests for critical flows** prior to release, plus security scanning in CI. Releases follow a standardized checklist (staging deploy + smoke tests, production deploy, post-deploy verification, stakeholder announcements) and require **release notes** and a **rollback/mitigation plan**, with a defined incident/rollback playbook and a **blameless retrospective** that turns learnings into owned, trackable improvement actions.

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's project management framework and principles |
| [Project Initiation](octoacme-project-initiation.md) | Processes and artifacts for starting a new project (one-pager, stakeholder alignment, kick-off) |
| [Project Planning](octoacme-project-planning.md) | Planning practices including backlog setup, milestone definition, and risk identification |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution workflows, project board usage, standups, and blocker management |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register format, escalation paths, and stakeholder communication cadence |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release checklist, CI/CD expectations, testing requirements, and rollback planning |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective process, blameless post-mortems, and tracking improvement actions |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions and responsibilities for each role: PM, PdM, Developers, QA/Testing, Stakeholders |
