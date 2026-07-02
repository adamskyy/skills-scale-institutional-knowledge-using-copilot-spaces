# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. These guides provide step-by-step guidance for managing projects from initiation through close-out and serve as the canonical source for our delivery practices.

## Overview

OctoAcme follows a structured, lifecycle-driven approach that emphasizes customer-first thinking, iterative delivery, clear ownership, data-informed decisions, and psychological safety. Projects begin with a lightweight initiation (a Project One-pager, stakeholder list, and initial risk register) to validate the business need, define measurable outcomes, and confirm sponsor alignment before moving into planning and execution.

## Project lifecycle

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation** — Validate business need, align stakeholders, and decide go/no-go.
2. **Planning** — Break work into shippable increments, create a prioritized backlog, and define acceptance criteria and Definition of Done.
3. **Execution** — Build, test, and iterate using a disciplined PR and CI workflow and a project board that tracks work from Backlog → Ready → In Progress → In Review → QA → Done.
4. **Release** — Deploy using a standardized checklist (staging verification, rollback plan, smoke tests, post-deploy validation).
5. **Close & Retrospective** — Capture learnings, convert them into prioritized action items, and feed improvements back into the backlog.

## Key workflows and quality practices

- Planning and backlog grooming produce acceptance criteria and estimates so the team can plan realistic, testable increments.
- Execution uses small, reviewable PRs linked to issues, automated CI (tests, linting, security scans), and required approvals before merge.
- QA includes unit and integration tests, end-to-end smoke tests for critical flows, and manual acceptance testing where needed.
- Risk is tracked in a simple Risk Register and escalated along defined paths (team → PM → Product Lead → Sponsor) when necessary.
- Retrospectives are timeboxed, produce 2–3 prioritized action items, and track implementation and impact.

## How to use these docs

This README is the entry point for the project management processes. Each document below goes into detail for a specific stage of the lifecycle or cross-cutting concern. Keep the Project Charter and one-pagers in the project repo and add process-specific docs into `.copilot/` if you want Copilot Spaces to consume them as context.

## Process documents

### Foundation & Framework
- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts.
- [Roles & Personas](octoacme-roles-and-personas.md) — Definitions of core roles (PM, Product Manager, Developer, QA) and responsibilities.

### Delivery phases
- [Project Initiation](octoacme-project-initiation.md) — Steps to validate and authorize new work, align stakeholders, and create a project one-pager.
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and prioritized backlog.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day execution, team rhythm, quality standards, and progress tracking.
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardized approach to releasing features to production with reduced risk.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements.

### Cross-cutting concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies across the project lifecycle.

## Feedback and contributions

If you want to add or update content, use the issue template “Add Content to Project Management Process Docs” in .github/ISSUE_TEMPLATE and open a PR. For editorial or substantive changes, please review with the PM and Product Lead as appropriate.
