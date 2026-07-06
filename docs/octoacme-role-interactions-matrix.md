# OctoAcme Role Interactions Matrix

This document provides a RACI (Responsible, Accountable, Consulted, Informed) matrix and interaction guide for OctoAcme personas in project scenarios.

---

## RACI Matrix

| Activity | Developers | Product Manager | Project Manager | QA Lead | Change Owner | Comms Manager | Resource Scheduler |
|----------|-----------|-----------------|-----------------|---------|--------------|---------------|--------------------|
| Define acceptance criteria | C | A | C | C | I | I | I |
| Plan sprint/iteration | R | C | A | C | I | I | C |
| Implement features | A | I | C | C | I | I | I |
| Conduct code reviews | A | I | I | C | I | I | I |
| Execute QA testing | C | I | I | A | I | I | I |
| Document test results | C | I | I | R | I | I | I |
| Assess change impact | C | C | C | R | A | C | C |
| Communicate changes | I | C | C | I | R | A | I |
| Plan resources | C | C | R | I | C | I | A |
| Resolve resource conflicts | C | I | C | I | I | I | A |
| Escalate issues | R | R | A | R | R | R | R |
| Provide stakeholder updates | I | C | C | I | I | A | I |
| Track project metrics | I | C | R | C | I | I | I |
| Plan releases | C | A | R | C | C | I | I |
| Manage risks | I | C | A | C | R | I | I |

**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (final authority/approval)
- **C** = Consulted (provides input)
- **I** = Informed (kept in the loop)

---

## Key Interaction Patterns

### Planning Phase
1. **Product Manager** defines what needs to be built
2. **Project Manager** creates the project plan
3. **QA Lead** defines acceptance criteria and test approach
4. **Resource Scheduler** allocates team members
5. **Stakeholder Communication Manager** briefs stakeholders on plan

### Execution Phase
1. **Developers** implement features
2. **QA Lead** conducts testing in parallel
3. **Change Management Owner** tracks and assesses change requests
4. **Project Manager** monitors progress and manages risks
5. **Stakeholder Communication Manager** provides status updates
6. **Resource Scheduler** tracks utilization and resolves conflicts

### Quality Gate (Before Release)
1. **QA Lead** confirms all tests passed and criteria met
2. **Change Management Owner** validates all changes approved
3. **Project Manager** confirms scope and timeline alignment
4. **Stakeholder Communication Manager** prepares release communication
5. **Resource Scheduler** confirms team availability for release support

### Issue Escalation
- **Any role** can escalate to **Project Manager**
- **Project Manager** involves **Stakeholder Communication Manager** for external communication
- **Change Management Owner** escalates scope impacts
- **QA Lead** escalates quality blockers
- **Resource Scheduler** escalates critical resource gaps

---

## Scenario Examples

### Scenario 1: Mid-Project Scope Change
1. **Stakeholder** requests additional feature
2. **Change Management Owner** assesses impact on timeline and resources
3. **QA Lead** evaluates testing scope implications
4. **Resource Scheduler** checks capacity for additional work
5. **Project Manager** decides on approval/rejection
6. **Stakeholder Communication Manager** communicates decision and implications

### Scenario 2: Quality Issue Discovery
1. **QA Lead** discovers critical defect in accepted component
2. **Developers** assess fix complexity and timeline
3. **Change Management Owner** determines if change approval needed
4. **Project Manager** evaluates impact on release date
5. **Stakeholder Communication Manager** prepares escalation communication
6. **Resource Scheduler** adjusts allocation for fix priority

### Scenario 3: Resource Conflict
1. **Resource Scheduler** identifies team member needed for multiple projects
2. **Project Managers** (from both projects) consult on priorities
3. **Resource Scheduler** recommends allocation based on business priority
4. **Project Managers** agree on resolution
5. **Stakeholder Communication Manager** informs affected stakeholders
6. **Developers** adjust schedules based on resource allocation

---

## Communication Guidelines

### Daily Communication
- **Developers** & **QA Lead**: Test status, defect findings, blockers
- **Project Manager** & **Resource Scheduler**: Progress tracking
- **Project Manager** & **Developers**: Sprint execution status

### Weekly Communication
- **All Roles** participate in sprint review and retrospective
- **Project Manager** shares status with **Stakeholder Communication Manager**
- **Resource Scheduler** reviews utilization metrics
- **Change Management Owner** reviews change requests

### As-Needed Communication
- **Change Management Owner** initiates change impact assessments
- **QA Lead** escalates quality blockers
- **Stakeholder Communication Manager** manages crisis communications
- **Resource Scheduler** addresses resource conflicts
