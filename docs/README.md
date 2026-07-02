# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. These guides provide comprehensive, step-by-step guidance for managing projects from initiation through close-out. The docs emphasize customer-first thinking, iterative delivery, clear ownership, data-informed decisions, and psychological safety to help teams ship reliable, measurable value.

OctoAcme’s project management approach is grounded in a few clear principles — customer-first delivery, iterative increments, clear ownership, and data-informed decisions — and follows a simple lifecycle: initiation, planning, execution, release, and close/retrospective. New work starts with a lightweight validation step (a Project One-pager that captures problem, objective, success metrics, stakeholders, and a high-level timeline) and an initiation checklist to confirm sponsor alignment and readiness to plan. Planning breaks approved initiatives into shippable backlog items with acceptance criteria, estimates, a Definition of Done, and an explicit release plan and milestone map.

Work execution is organized around a small-change pull request workflow and an explicit project board. Teams use a Kanban-like board with Backlog → Ready → In Progress → In Review → QA → Done, keep PRs small (guidance suggests <= 400 lines), include issue links and acceptance criteria in PR descriptions, run CI/lint/security scans before requesting review, and require approvals per team policy. Planning and backlog practices emphasize prioritization, capacity-aware sprint selection, and tracking dependencies and risks in a Risk Register (ID, impact, likelihood, owner, mitigation, status).

Roles and responsibilities are well defined: Product Managers own outcomes, success metrics, and prioritization; Project Managers coordinate delivery, schedules, risks, and stakeholder communications; Developers implement features, write tests, and participate in design and reviews; QA owners validate acceptance criteria and manage test strategy. This role clarity supports accountability and reduces single-person dependency by naming owners for artifacts like the one-pager, release plan, risk register, and action items from retrospectives.

## Documents (in this folder)

### Foundation & Framework
- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts
- [Roles & Personas](octoacme-roles-and-personas.md) — Definitions of core roles (PM, Product Manager, Developer, QA) and their responsibilities

### Delivery Phases
- [Project Initiation](octoacme-project-initiation.md) — Steps to validate and authorize new work, align stakeholders, and create a project one-pager
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and prioritized backlog
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day execution, team rhythm, quality standards, and progress tracking
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardized approach to releasing features to production with reduced risk
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements

### Cross-cutting Concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies throughout the project lifecycle

## How to use
- Start with this README to understand the lifecycle and where to find role definitions, templates, and checklists.
- Follow the initiation -> planning -> execution -> release -> retrospective flow and reference the linked docs for templates and checklists.
- Use the included issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes to these process documents.

## Contact / Review
If you have updates or want to propose new content, open an issue using the "Add Content to Project Management Process Docs" template and follow the Acceptance Criteria listed there.

<!-- Copilot: branch update to create PR diff -->
