# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
**Owner**: Release Manager (coordinates), QA Engineer (verifies quality), Technical Lead (technical readiness)

- [ ] All acceptance criteria met and PRs merged
- [ ] Passing CI and security scans
- [ ] **QA Engineer** formal sign-off obtained (see [QA Sign-Off Checklist](octoacme-roles-and-personas.md#qa-sign-off-checklist-per-feature))
- [ ] **Technical Lead** confirms technical readiness and architecture review
- [ ] Release notes drafted by **Release Manager**
- [ ] Rollback / mitigation plan documented
- [ ] Smoke tests prepared by **QA Engineer**
- [ ] Stakeholder communication plan ready (coordinated with **Project Manager**)

**Cross-Reference**: See [Roles and Personas](octoacme-roles-and-personas.md) for Release Manager, QA Engineer, and Technical Lead responsibilities.

## Deployment Checklist
**Primary Owner**: Release Manager  
**Supporting Roles**: Technical Lead, QA Engineer, Project Manager

- [ ] Deployment window scheduled (if needed) - **Release Manager** with **Project Manager**
- [ ] Backup or snapshot (if applicable) - **Technical Lead** ensures procedures
- [ ] Deploy to staging and run smoke tests - **QA Engineer** executes tests
- [ ] **Technical Lead** reviews deployment logs and health checks
- [ ] Deploy to production (automated pipeline preferred) - **Release Manager** initiates
- [ ] Run post-deploy verifications - **QA Engineer** and **Technical Lead**
- [ ] **Release Manager** announces release to stakeholders and support (template in [Risk & Communication](octoacme-risks-and-communication.md))
- [ ] **Project Manager** updates project status and documentation

**Cross-Reference**: See [Release Manager Onboarding Checklist](octoacme-roles-and-personas.md#release-manager-onboarding-checklist) for detailed role preparation.

## Rollback & Incident Playbook
**Incident Commander**: Release Manager  
**Technical Response**: Technical Lead  
**Communication**: Project Manager

- If a deployment fails or causes a critical issue:
  - **Release Manager** triggers incident response and notifies on-call
  - **Technical Lead** assesses technical impact and coordinates technical response
  - **Release Manager** executes rollback to last known-good release if necessary
  - **Project Manager** manages stakeholder communication using incident template (see [Risk & Communication](octoacme-risks-and-communication.md))
  - **Technical Lead** and team triage root cause and capture action items
  - **Scrum Master** schedules post-incident retrospective

**Cross-Reference**: See [Escalation Paths](octoacme-risks-and-communication.md#escalation-paths) for detailed incident escalation procedures.

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
