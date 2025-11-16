# OctoAcme Project Management Documentation Hub

## Purpose

Welcome to the OctoAcme project management documentation hub. This collection of guides helps new teammates understand how we run projects, defines roles and responsibilities, and serves as a single source of truth for our delivery processes. Whether you're joining as a developer, product manager, project manager, or stakeholder, these docs will help you get up to speed quickly.

## Project Management Overview

OctoAcme organizes work around a clear project lifecycle: **Initiation** (one-pager, stakeholder alignment, go/no-go), **Planning** (kickoff, prioritized backlog, estimates, Definition of Done, release plan), **Execution** (iterative sprints or milestones with a project board and PR workflow), **Release** (pre-release checks, smoke tests, rollback plan), and **Close & Retrospective** (capture learnings and action items). Key artifacts — the Project One-pager/Charter, Roadmap, Backlog, Acceptance Criteria, Risk Register, and Retrospective notes — are maintained in the project repository and used as the single source of truth for decision-making and tracking.

Roles are explicitly defined to reduce ambiguity: Product Managers own outcomes and prioritization, Project Managers coordinate schedules, risks, and communications, developers implement and test, QA validates acceptance, and stakeholders provide input and approvals. Operational workflows emphasize small, reviewable changes (guidance for small PRs, PR descriptions that include issue links and acceptance criteria), CI gating (tests, linting, security scans), and at-least-one-approval merge policies to maintain quality and traceability.

Communication and quality practices are woven into the rhythm: daily standups and weekly delivery syncs for tactical coordination, weekly PM+PdM alignment and monthly stakeholder updates for strategic visibility, and escalation paths from team triage up to sponsor-level involvement for critical issues. Quality assurance uses a layered approach — unit and integration tests, end-to-end smoke tests for critical flows, manual QA where needed, and security scanning in CI — with deployment checklists and post-deploy verification to reduce risk and enable predictable releases.

## Documentation

Explore the following guides to learn about specific aspects of our project management approach:

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme Project Initiation](octoacme-project-initiation.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme Execution and Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme Risks and Communication](octoacme-risks-and-communication.md)
- [OctoAcme Release and Deployment](octoacme-release-and-deployment.md)
- [OctoAcme Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)

## How to Use This Hub

To keep this documentation effective:

- **Maintain the Project Charter**: Keep the Project Charter or One-pager updated in the project repository to ensure everyone has access to the latest project scope, objectives, and decisions.
- **Copilot Spaces Integration**: Add process-specific documentation into the `.copilot/` directory if you want GitHub Copilot Spaces to use them as additional context when assisting with project-related tasks.
- **Keep docs current**: Review and update these guides as processes evolve, and capture any changes during retrospectives.
