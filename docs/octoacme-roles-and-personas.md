# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations
- Collaborate with QA Engineer on testability and bug fixes
- Follow coding standards and architectural guidelines set by Technical Lead

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed
- Bug reports and fix confirmations with QA Engineer

### Interactions with Other Roles
- **Technical Lead**: Receives code review feedback, seeks guidance on technical decisions, discusses architectural approaches
- **QA Engineer**: Collaborates on bug reproduction and fixes, ensures testability of implementations
- **Scrum Master**: Reports blockers and progress in standups, receives coaching on Agile practices
- **UX Designer**: Implements design specs, seeks clarification on UI/UX requirements
- **Product Managers**: Clarifies acceptance criteria and feature requirements

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Work with UX Designer on user experience and design direction
- Provide clear acceptance criteria for features

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Backlog refinement sessions with Scrum Master and team

### Interactions with Other Roles
- **UX Designer**: Collaborates on feature definition, user research, and design validation
- **Technical Lead**: Discusses technical feasibility and trade-offs, receives estimates and risk assessments
- **Scrum Master**: Participates in backlog refinement, clarifies priorities and acceptance criteria
- **QA Engineer**: Validates feature behavior, clarifies acceptance criteria, reviews quality metrics
- **Project Managers**: Aligns on roadmap timelines, communicates scope changes, shares stakeholder feedback

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Escalate blockers and risks through proper channels
- Coordinate with Release Manager on deployment schedules

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Release planning updates with Release Manager

### Interactions with Other Roles
- **Scrum Master**: Receives sprint progress reports, coordinates on cross-team dependencies and impediment escalation
- **Release Manager**: Aligns on deployment timelines, coordinates release communication with stakeholders
- **Technical Lead**: Gathers technical estimates and risk assessments, escalates technical constraints
- **QA Engineer**: Tracks testing progress and quality metrics, incorporates QA timelines into project plans
- **Product Managers**: Aligns on roadmap and scope, communicates project status and risks
- **Stakeholders**: Provides regular status updates, manages expectations, escalates critical decisions

---

## Scrum Master

### Role Summary
Scrum Masters facilitate Agile ceremonies, remove impediments, and drive continuous improvement. They support delivery teams in following Agile best practices and ensure smooth sprint execution.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove blockers and impediments for the team
- Coach team members on Agile practices and self-organization
- Track and communicate sprint metrics (velocity, burndown)
- Ensure adherence to Definition of Done and team agreements
- Shield the team from external disruptions
- Foster a culture of continuous improvement

### Goals
- Maximize team velocity and predictability
- Eliminate waste and process inefficiencies
- Build high-performing, self-organizing teams
- Maintain sustainable development pace

### Typical Communication
- Daily facilitation of standups and team coordination
- Sprint reports and metrics to Project Managers and stakeholders
- Impediment tracking and escalation to Project Managers
- Retrospective action items shared with team and management

### Interactions with Other Roles
- **Project Managers**: Shares sprint progress, escalates risks and dependencies that require cross-team coordination
- **Product Managers**: Coordinates on backlog refinement and acceptance criteria clarity
- **Developers**: Removes blockers, facilitates collaboration, coaches on Agile practices
- **QA Engineer**: Ensures testing is integrated into sprint workflow and Definition of Done
- **Stakeholders**: Provides sprint demos and progress visibility

### Daily Ceremony Checklist
- [ ] Review updated blockers from team members before standup
- [ ] Facilitate 15-minute standup focused on progress, plans, and impediments
- [ ] Update project board and sprint burndown chart
- [ ] Follow up on blockers and escalate if needed
- [ ] Prepare for upcoming sprint ceremonies (planning, review, retro)
- [ ] Track and communicate sprint health metrics

---

## UX Designer

### Role Summary
UX Designers define and maintain user experience standards, guide design decisions, and ensure features align with usability goals. They collaborate across teams to create intuitive, user-centered solutions.

### Responsibilities
- Define and document UX standards and design systems
- Create wireframes, prototypes, and user flows
- Conduct user research and usability testing
- Review features for consistency with design guidelines
- Collaborate on acceptance criteria from a usability perspective
- Provide design feedback during planning and code review

### Goals
- Deliver exceptional user experiences
- Maintain design consistency across products
- Validate design decisions with user research
- Reduce usability issues and support tickets

### Typical Communication
- Design reviews and prototype walkthroughs
- Usability findings and recommendations
- Design specs and asset handoffs to developers
- Feedback on feature implementations

### Interactions with Other Roles
- **Product Managers**: Collaborates on feature definition, user research, and acceptance criteria from UX perspective
- **Developers**: Provides design specs, reviews implementations, clarifies UI/UX requirements
- **QA Engineer**: Partners on usability testing and acceptance verification
- **Technical Lead**: Discusses design feasibility and technical constraints
- **Stakeholders**: Presents design concepts and user research findings

---

## Release Manager

### Role Summary
Release Managers coordinate deployment processes, ensure pre-release conditions are met, and communicate release status with stakeholders. They oversee the entire release lifecycle from planning to post-deployment verification.

### Responsibilities
- Plan and schedule release windows
- Maintain release checklists and ensure compliance
- Coordinate deployment activities across teams
- Verify pre-release requirements (tests, approvals, documentation)
- Monitor deployments and post-release health
- Communicate release status to stakeholders and support teams
- Manage rollback procedures when needed
- Maintain release notes and deployment documentation

### Goals
- Ensure smooth, reliable deployments
- Minimize deployment-related incidents
- Maintain clear communication during releases
- Improve release process efficiency over time

### Typical Communication
- Release plans and deployment schedules
- Go/no-go decisions with stakeholders
- Deployment status updates
- Post-release reports and metrics
- Incident notifications and rollback communications

### Interactions with Other Roles
- **Project Managers**: Coordinates release timelines, communicates deployment status, escalates release risks
- **QA Engineer**: Verifies all acceptance criteria met, ensures test coverage and sign-off before release
- **Developers**: Coordinates code freeze, deployment steps, and post-deployment verification
- **Technical Lead**: Reviews technical readiness, architecture impacts, and rollback plans
- **Stakeholders**: Communicates release schedules, feature availability, and known issues

### Release Manager Onboarding Checklist
- [ ] Review deployment pipeline and automation tools
- [ ] Understand rollback procedures and incident response plan
- [ ] Access release planning tools and deployment systems
- [ ] Review historical release notes and post-mortems
- [ ] Meet with QA Engineer to understand testing and sign-off process
- [ ] Shadow at least two releases before leading independently
- [ ] Document stakeholder communication preferences and schedules
- [ ] Establish relationships with support and operations teams

---

## Technical Lead

### Role Summary
Technical Leads guide technical direction, architecture decisions, and code quality standards. They mentor developers, make key technical decisions, and serve as a liaison between engineering and project management.

### Responsibilities
- Define and maintain system architecture and technical standards
- Review code for quality, security, and adherence to standards
- Make key technical decisions and document trade-offs
- Mentor developers and provide technical guidance
- Identify and address technical debt
- Evaluate new technologies and tools
- Collaborate with Project Managers on technical feasibility and estimates
- Escalate technical risks and constraints

### Goals
- Maintain high code quality and system reliability
- Build scalable, maintainable architectures
- Develop strong engineering capabilities within the team
- Balance technical excellence with delivery timelines

### Typical Communication
- Technical design documents and architecture decisions
- Code review feedback and mentoring guidance
- Technical risk assessments and recommendations
- Engineering updates in planning meetings

### Interactions with Other Roles
- **Project Managers**: Provides technical estimates, identifies risks, and clarifies technical constraints and dependencies
- **Product Managers**: Advises on technical feasibility, proposes technical solutions, discusses trade-offs
- **Developers**: Mentors on best practices, reviews code, provides technical guidance and unblocks technical challenges
- **QA Engineer**: Collaborates on test strategy, reviews test coverage, addresses quality issues
- **Release Manager**: Reviews technical readiness for releases, advises on deployment strategies and rollback plans

---

## QA Engineer

### Role Summary
QA Engineers own testing plans, build quality verification processes, and confirm that features meet the Definition of Done. They work across functions to ensure product quality and reliability.

### Responsibilities
- Develop comprehensive test plans and test cases
- Execute manual and automated tests
- Track and triage bugs and quality issues
- Verify acceptance criteria and Definition of Done
- Collaborate on test strategy and coverage
- Maintain test automation frameworks
- Perform regression testing before releases
- Sign off on feature readiness and release quality

### Goals
- Ensure high product quality and reliability
- Catch defects early in the development cycle
- Improve test coverage and automation
- Reduce production incidents and customer-reported bugs

### Typical Communication
- Test plans and coverage reports
- Bug reports and quality metrics
- Release readiness assessments
- QA sign-off confirmations

### Interactions with Other Roles
- **Developers**: Reports bugs, collaborates on reproducibility, validates fixes, reviews testability of implementations
- **Release Manager**: Provides release sign-off, confirms all acceptance criteria met, communicates testing status
- **Product Managers**: Clarifies acceptance criteria, validates feature behavior against requirements
- **Technical Lead**: Discusses test strategy, reviews test architecture, addresses testing challenges
- **Scrum Master**: Integrates testing into sprint workflow, ensures QA capacity in sprint planning

### QA Sign-Off Checklist (Per Feature)
- [ ] All acceptance criteria verified and passing
- [ ] Automated tests added or updated for new functionality
- [ ] Regression tests executed and passing
- [ ] Edge cases and error scenarios tested
- [ ] Cross-browser/platform compatibility verified (if applicable)
- [ ] Performance impact assessed
- [ ] Security considerations reviewed
- [ ] Documentation updated (if applicable)
- [ ] No critical or high-priority bugs remaining
- [ ] Sign-off communicated to Release Manager and Project Manager

---

## Updated Existing Personas

### Handoff and Responsibility Clarifications

The existing personas (Developers, Product Managers, Project Managers) work closely with the new roles defined above. Key handoffs and cross-functional workflows include:

**Risk Escalation Path:**
1. **Developers/QA Engineer** identify technical or quality risks → **Technical Lead** assesses impact
2. **Technical Lead** or **Scrum Master** escalates to → **Project Manager** for coordination
3. **Project Manager** updates risk register and escalates to → **Product Manager** or stakeholders as needed
4. For deployment risks: **Release Manager** coordinates with all parties and makes go/no-go decisions

**Release Planning Workflow:**
1. **Product Manager** defines release scope and priorities
2. **Project Manager** coordinates timeline and dependencies
3. **Technical Lead** reviews technical readiness
4. **QA Engineer** confirms testing coverage and provides sign-off
5. **Release Manager** executes deployment and communicates status
6. **Scrum Master** ensures sprint goals align with release milestones

**Sprint Review Handoff:**
1. **Scrum Master** facilitates demo of completed work
2. **Developers** present implemented features
3. **Product Manager** validates against acceptance criteria
4. **UX Designer** reviews user experience and design compliance
5. **QA Engineer** confirms testing and quality verification
6. **Project Manager** updates project status and stakeholder communications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction maps and checklists to model realistic handoffs and collaboration patterns.
- Cross-reference with process docs (see [Risk Management](octoacme-risks-and-communication.md), [Release Guide](octoacme-release-and-deployment.md), [Execution & Tracking](octoacme-execution-and-tracking.md)) for detailed workflows.

