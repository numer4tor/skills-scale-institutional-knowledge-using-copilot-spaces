# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation. This README centralizes OctoAcme's project management processes, making them discoverable and easy to navigate for contributors, stakeholders, and new team members.

## Quick Links to Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — High-level summary of OctoAcme's approach to project management and how the other documents fit together.
- [Project Initiation](octoacme-project-initiation.md) — Guidance on project intake, objectives, stakeholders, and approval criteria.
- [Project Planning](octoacme-project-planning.md) — Planning artifacts, timelines, milestone definitions, and scope control.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — How work is executed, status reporting, and progress tracking practices.
- [Risks and Communication](octoacme-risks-and-communication.md) — Risk identification, escalation paths, and stakeholder communication protocols.
- [Release and Deployment](octoacme-release-and-deployment.md) — Release checklists, deployment responsibilities, and rollback guidance.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Post-release reviews, improvement backlog, and action tracking.
- [Roles and Personas](octoacme-roles-and-personas.md) — Responsibilities and expectations for roles involved in project delivery.

## OctoAcme Project Management Overview

OctoAcme employs a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership across cross-functional teams. The framework consists of five primary phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business need, identify stakeholders, and define success metrics through a lightweight Project One-pager. This decision gate ensures alignment before moving into detailed Planning, where work is broken into shippable increments with clear acceptance criteria, estimated scope, and documented dependencies. The approach prioritizes small, testable releases and maintains a risk register throughout the project lifecycle to proactively identify and mitigate potential blockers.

Execution and delivery are coordinated through a disciplined team rhythm that includes daily standups (15 minutes), weekly delivery syncs, and demo/review sessions at sprint or milestone endpoints. Work flows through a project board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), and pull requests follow strict quality gates: small PRs (≤400 lines), automated CI/CD testing and linting, and at least one approval before merge. Quality assurance is embedded throughout—unit tests, integration tests, end-to-end smoke tests, and security scanning are all required before release. Communication is transparent and multi-layered, with weekly PM/PdM syncs, stakeholder updates, and a clear three-level escalation path for blockers (team → PM → Product Lead → Sponsor).

OctoAcme defines clear roles with distinct accountabilities: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes and prioritize the backlog; **Developers** implement features and collaborate on design; and **QA/Testing** validates acceptance criteria. This separation of concerns enables distributed ownership while maintaining alignment through shared artifacts—project charters, roadmaps, risk registers, and retrospective notes—that serve as the single source of truth. Release management follows a standardized process with pre-release checks, deployment checklists, smoke testing in staging, and documented rollback plans, ensuring production deployments are predictable and observable. Finally, the cycle closes with structured retrospectives that capture learnings and convert action items into future backlog work, embedding continuous improvement as a core cultural practice.

## How to Use These Docs

1. **Start here** — Begin with the [Project Management Overview](octoacme-project-management-overview.md) to understand the high-level approach and lifecycle.
2. **Find your phase** — Browse the list above and click the document relevant to your current project phase or question.
3. **Report gaps or suggest updates** — If a process is missing, unclear, or needs improvement, [open an issue](https://github.com/numer4tor/skills-scale-institutional-knowledge-using-copilot-spaces/issues) referencing this README and the specific document.
4. **Contribute** — To propose updates to process documentation, submit a PR with changes to the target document and reference the relevant issue.

## Key Principles

- **Customer-first**: Prioritize customer value and usability.
- **Iterative delivery**: Deliver small, testable increments.
- **Clear ownership**: Each project has a named Project Manager and Product Lead.
- **Data-informed decisions**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback and learning.

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications.
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success.
- **Developers**: Implement features, collaborate on design and testability.
- **QA/Testing**: Validate quality and acceptance criteria.
- **Stakeholders**: Provide inputs, approvals, and strategic direction.

For more details on roles and personas, see [Roles and Personas](octoacme-roles-and-personas.md).

## Communication Cadence

- **Daily standups** (15 minutes) — Team-level progress, blockers, and dependencies.
- **Weekly PM/PdM sync** — Delivery and product alignment.
- **Twice-weekly standups** (or as agreed) — For delivery teams.
- **Monthly stakeholder updates** — High-level progress and upcoming milestones.
- **Ad-hoc escalations** — For urgent risks or blockers.

---

**Last updated**: July 2026  
**Repository**: [numer4tor/skills-scale-institutional-knowledge-using-copilot-spaces](https://github.com/numer4tor/skills-scale-institutional-knowledge-using-copilot-spaces)
