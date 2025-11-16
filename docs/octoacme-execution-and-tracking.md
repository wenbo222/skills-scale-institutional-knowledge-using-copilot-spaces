# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
**Scrum Master** facilitates all ceremonies and ensures team adherence to Agile practices.

- **Daily standups** (15 min) — focus on progress, blockers, dependencies
  - **Scrum Master** facilitates
  - **Developers** report progress and blockers
  - **QA Engineer** shares testing status
  - **Technical Lead** provides technical guidance as needed
  
- **Weekly delivery sync** — show progress, updates, and flagged risks
  - **Project Manager** leads
  - **Scrum Master** shares sprint metrics
  - **QA Engineer** reports quality status
  - **Technical Lead** raises technical risks
  
- **Demo/Review** at the end of each sprint or milestone
  - **Scrum Master** facilitates
  - **Developers** demonstrate completed features
  - **Product Manager** validates against acceptance criteria
  - **UX Designer** reviews design compliance
  - **QA Engineer** confirms testing completion

**Cross-Reference**: See [Sprint Review Handoff](octoacme-roles-and-personas.md#updated-existing-personas) and [Scrum Master Daily Ceremony Checklist](octoacme-roles-and-personas.md#daily-ceremony-checklist) for detailed workflows.

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - **Developer** requests review from **Technical Lead** or peers
  - Require at least one approval before merging (or team-defined policy)
  - **Developer** merges after approval and passes to **QA Engineer** for verification
  
**QA Handoff Process**:
- **Developer** moves item to QA column and notifies **QA Engineer**
- **QA Engineer** verifies against acceptance criteria (see [QA Sign-Off Checklist](octoacme-roles-and-personas.md#qa-sign-off-checklist-per-feature))
- **QA Engineer** reports bugs back to **Developer** with repro steps
- **Developer** fixes issues and notifies **QA Engineer** for re-verification
- **QA Engineer** moves to Done column when fully verified and documents sign-off

**Cross-Reference**: See [Roles and Personas](octoacme-roles-and-personas.md) for Developer and QA Engineer interaction details.

## Quality & Testing
**Primary Owner**: QA Engineer  
**Supporting Roles**: Developers, Technical Lead

- Unit tests for new logic - **Developer** responsibility
- Integration tests where applicable - **Developer** with **QA Engineer** input
- End-to-end smoke tests for critical flows before release - **QA Engineer** owns and executes
- Security scanning in CI - **Technical Lead** ensures configuration
- Manual QA for feature acceptance when needed - **QA Engineer** executes
- **QA Engineer** provides formal sign-off before release (see [Pre-release Requirements](octoacme-release-and-deployment.md#pre-release-requirements))

**Test Strategy Collaboration**:
- **Technical Lead** and **QA Engineer** define test coverage standards
- **QA Engineer** maintains test plans and automation frameworks
- **Developers** ensure code testability and write unit tests
- **QA Engineer** tracks quality metrics and reports to **Project Manager**

**Cross-Reference**: See [QA Engineer role](octoacme-roles-and-personas.md#qa-engineer) for detailed testing responsibilities.

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
**Scrum Master** coordinates initial triage and escalation.

- **Level 1**: Team-level triage in daily standup
  - **Scrum Master** identifies and tracks blockers
  - **Technical Lead** provides technical guidance
  - Team self-organizes to resolve
  
- **Level 2**: **Scrum Master** or **Technical Lead** escalates to **Project Manager** for cross-team coordination
  - **Project Manager** coordinates with dependent teams
  - Updates risk register and stakeholder communication
  
- **Level 3**: **Project Manager** escalates to **Product Manager** and Sponsor for business-impacting issues
  - Scope, priority, or resource decisions required
  - Executive stakeholder involvement needed

**Cross-Reference**: See [Risk Escalation Paths](octoacme-risks-and-communication.md#escalation-paths) for detailed escalation procedures by type.

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
