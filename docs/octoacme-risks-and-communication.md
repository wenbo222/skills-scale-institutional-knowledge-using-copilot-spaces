# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates

### Weekly Status Template
**Owner**: Project Manager  
**Recipients**: Stakeholders, Product Manager, team leads

- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

### Sprint Review Summary
**Owner**: Scrum Master  
**Recipients**: Product Manager, stakeholders, Project Manager

- Sprint goals and completion status:
- Demos of completed features:
- Feedback and action items:
- Next sprint preview:

### Release Communication
**Owner**: Release Manager  
**Recipients**: Stakeholders, support teams, operations

- Release name/version:
- Scheduled deployment time:
- Key features and changes:
- Migration steps (if any):
- Known issues and workarounds:
- Rollback plan:

### QA Sign-Off Notice
**Owner**: QA Engineer  
**Recipients**: Release Manager, Project Manager, Product Manager

- Feature/release name:
- Testing coverage summary:
- Critical issues (if any):
- Sign-off status (Approved/Conditional/Blocked):
- Conditions or remaining items (if applicable):

### Technical Risk Assessment
**Owner**: Technical Lead  
**Recipients**: Project Manager, Product Manager, team

- Risk description:
- Technical impact assessment:
- Proposed mitigation or alternatives:
- Timeline and effort estimate:
- Recommendation:

### Incident Communication
**Owner**: Project Manager (coordinates), Technical Lead (technical details)  
**Recipients**: Stakeholders, affected teams

- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

**Cross-Reference**: See [Roles and Personas](octoacme-roles-and-personas.md) for detailed role responsibilities in communication workflows.

## Escalation Paths

### Standard Risk Escalation
- **Level 1**: Team identifies issue → **Scrum Master** or **Technical Lead** triages
- **Level 2**: **Scrum Master/Technical Lead** escalates to → **Project Manager** for cross-team coordination
- **Level 3**: **Project Manager** escalates to → **Product Manager** or Product Lead for scope/priority decisions
- **Level 4**: **Product Manager** escalates to → Sponsor for business-impacting issues

### Technical Risk Escalation
- **Developer** identifies technical risk → **Technical Lead** assesses impact and feasibility
- **Technical Lead** documents in risk register and notifies → **Project Manager**
- **Project Manager** coordinates mitigation with stakeholders

### Release Risk Escalation
- **QA Engineer** or **Developer** identifies release blocker → **Release Manager** assesses
- **Release Manager** coordinates with **Technical Lead** and **Project Manager** for go/no-go decision
- Critical issues trigger incident response (see below)

### Quality and Testing Escalation
- **QA Engineer** identifies critical quality issue → **Technical Lead** and **Scrum Master** notified
- If blocking release: **QA Engineer** → **Release Manager** → **Project Manager** → stakeholders
- **QA Engineer** provides formal sign-off or escalates concerns before any release

### Security Incidents
- Follow the security incident runbook and notify Security on-call immediately
- **Technical Lead** coordinates technical response
- **Project Manager** manages stakeholder communication
- **Release Manager** coordinates rollback if needed

**Note**: All escalations should be documented in the risk register with clear owners, timelines, and status updates. See [Roles and Personas](octoacme-roles-and-personas.md) for detailed role interactions.
