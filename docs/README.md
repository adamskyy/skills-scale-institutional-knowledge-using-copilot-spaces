# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. These guides provide step-by-step guidance for managing projects from initiation through close-out and serve as the central entry point for team members and stakeholders.

## Brief overview of OctoAcme processes

OctoAcme runs projects through a clear, staged lifecycle: initiation (one‑pager & stakeholder alignment), planning (backlog creation, estimates, Definition of Done), execution (small iterative deliveries tracked on a project board), and release/close (deployment checklist, release notes, and retrospective). Core artifacts — Project One‑pager, prioritized backlog, release plan, risk register, and sprint/iteration backlog — are created early and maintained as the single sources of truth. Work is tracked on a project board with columns like Backlog → Ready → In Progress → In Review → QA → Done, and decisions to move between stages depend on acceptance criteria and the Definition of Done.

Responsibility is explicit: Product Managers define outcomes and success metrics, Project Managers coordinate schedules, risks, and stakeholder communication, Developers implement and test, and QA validates acceptance. The docs emphasize small, reviewable pull requests (target ≤ 400 lines), PR descriptions that include issue links and acceptance criteria, automated CI & security scans before review, and at least one approval before merging. Risk ownership and mitigation live in a lightweight Risk Register and cross-team dependencies are surfaced in planning and weekly syncs.

Communication and quality practices center on a regular rhythm and measurable controls: daily standups for immediate blockers, weekly delivery syncs for progress and risk review, scheduled demos, and stakeholder updates. QA uses unit/integration tests, smoke tests for critical flows, manual QA when needed, and security scanning in CI; pre‑release checklists require passing CI, drafted release notes, rollback plans, and post‑deploy verifications. Continuous improvement is enforced via retrospectives with prioritized action items tracked into the backlog, and an escalation path (Team → PM → Product Lead → Sponsor) for unresolved or business‑critical blockers.

## Project lifecycle (high level)

1. Initiation — Validate the business need, align stakeholders, produce a one-pager, decide go/no-go.  
2. Planning — Create the prioritized backlog, estimate work, define DoD, identify risks and dependencies.  
3. Execution — Implement in small increments, use PR and CI practices, perform QA and smoke tests.  
4. Release — Follow release checklist, deploy via pipeline, run post-deploy verifications, document release notes.  
5. Close & Retrospective — Capture learnings, convert into action items and backlog issues.

## Process documents

### Foundation & framework
- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts  
- [Roles & Personas](octoacme-roles-and-personas.md) — Definitions of core roles (PM, Product Manager, Developer, QA) and their responsibilities

### Delivery phases
- [Project Initiation](octoacme-project-initiation.md) — Steps to validate and authorize new work, align stakeholders, and create a project one-pager  
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and prioritized backlog  
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day execution, team rhythm, quality standards, and progress tracking  
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardized approach to releasing features to production with reduced risk  
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements

### Cross-cutting concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies throughout the project lifecycle

## How to use these docs

- Start at this README to understand the lifecycle and roles.  
- Use the Project One-pager and the Project Management Overview to onboard new projects and stakeholders.  
- Add action items and improvement tasks to the backlog and follow the Execution & Tracking guidance for day-to-day delivery.  
- Keep the Risk Register and release notes up to date as the single sources of truth for status and decisions.

## Acceptance criteria for this README
- Content aligns with existing process docs.  
- Improves discoverability and provides a central entry point.  
- Helps new users understand how documents relate across the lifecycle.
