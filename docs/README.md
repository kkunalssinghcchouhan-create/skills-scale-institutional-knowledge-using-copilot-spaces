# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation. This folder contains comprehensive guides for running projects effectively using standardized processes, clear roles, and proven practices.

## Process Summary

OctoAcme follows a structured project lifecycle designed to deliver customer value through iterative, well-managed execution. Our approach emphasizes:

- **Customer-first mindset**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Ship small, testable increments rather than massive releases
- **Clear ownership**: Every project has named Project Manager (PM) and Product Manager (PdM) roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

The OctoAcme lifecycle consists of five core phases:

1. **Initiation** — Validate business need, align stakeholders, define success criteria
2. **Planning** — Break work into shippable increments, identify risks and dependencies
3. **Execution** — Build, test, review, and iterate with daily standups and regular demos
4. **Release** — Deploy to production with proper testing, verification, and communication
5. **Close & Retrospective** — Capture learnings and convert them into actionable improvements

## Documentation Index

All process documentation is organized by project phase and functional area. Use the links below to navigate to specific topics:

### Project Lifecycle Phases

| Phase | Document | Purpose |
|-------|----------|---------|
| **Initiation** | [Project Initiation Guide](./octoacme-project-initiation.md) | Define initial steps to validate work, align stakeholders, and create a lightweight plan |
| **Planning** | [Project Planning](./octoacme-project-planning.md) | Turn approved initiatives into actionable plans and prioritized backlogs |
| **Execution** | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Manage day-to-day execution and track progress toward milestones |
| **Release** | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize how OctoAcme releases features to production safely |
| **Close** | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |

### Cross-Functional Topics

| Topic | Document | Purpose |
|-------|----------|---------|
| **Foundation** | [Project Management Overview](./octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, roles, and key artifacts |
| **Roles** | [Roles & Personas](./octoacme-roles-and-personas.md) | Define typical roles, responsibilities, goals, and communication patterns |
| **Risk Management** | [Risk Management & Communication](./octoacme-risks-and-communication.md) | Identify, manage, monitor, and communicate risks and dependencies |

## Project Lifecycle Overview

```
┌─────────────────────────────────────────────────────────────────┐
│                    OctoAcme Project Lifecycle                   │
└─────────────────────────────────────────────────────────────────┘

    INITIATION              PLANNING              EXECUTION
    ──────────              ────────              ─────────
    • Problem              • Kickoff             • Daily standups
    • Stakeholders         • Backlog             • Sprint work
    • Timeline             • Estimates           • Code review
    • One-pager            • DoD                 • Testing
    ─────────────────────────────────────────────────────────────→
         ↓                      ↓                      ↓
    Go/No-Go            Ready to Build         Demo & Iterate
    Decision             Approval               Regular Updates


    ──────────────────────────────────────────────────────────────→
         ↓                      ↓                      ↓
    
    RELEASE                CLOSE & RETROSPECTIVE
    ──────────             ──────────────────────
    • Pre-release          • What went well
    • Deploy               • Improvements
    • Verify               • Action items
    • Announce             • Next steps
         ↓                      ↓
    Live in                Learnings
    Production             Captured
```

## Key Roles at a Glance

**Project Manager (PM)**
- Coordinates delivery, schedules, risks, and communications
- Maintains timelines and removes blockers
- See: [Roles & Personas](./octoacme-roles-and-personas.md#project-managers)

**Product Manager (PdM)**
- Defines outcomes, prioritizes backlog, measures success
- Owns product vision and customer value
- See: [Roles & Personas](./octoacme-roles-and-personas.md#product-managers)

**Developers**
- Implement features, collaborate on design and testing
- Write and maintain quality code and documentation
- See: [Roles & Personas](./octoacme-roles-and-personas.md#developers)

**QA/Testing**
- Validate quality and acceptance criteria
- Execute test plans and ensure product readiness
- See: [Project Management Overview](./octoacme-project-management-overview.md#core-roles)

## Communication Cadence

To keep projects aligned and risks visible:

- **Weekly PM + PdM sync** — Strategic alignment and dependency resolution
- **Twice-weekly delivery team standups** — Progress, blockers, quick wins
- **Monthly stakeholder updates** — High-level status and milestones
- **Ad-hoc escalations** — Critical issues requiring immediate attention

See [Risk Management & Communication](./octoacme-risks-and-communication.md#stakeholder-communication) for templates and best practices.

## Key Artifacts in Every Project

- **Project Charter / One-pager** — Problem, goal, success metrics, timeline
- **Roadmap & Release Plan** — Milestones and deliverable timeline
- **Sprint/Iteration Backlog** — Prioritized work with acceptance criteria
- **Definition of Done** — Quality and readiness standards
- **Risk Register** — Identified risks, impact, mitigation, and status
- **Retrospective Notes** — Learnings and action items for improvement

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction.

2. **Starting a project?** Follow the sequence: [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Execution](./octoacme-execution-and-tracking.md) → [Release](./octoacme-release-and-deployment.md) → [Retrospective](./octoacme-retrospective-and-continuous-improvement.md).

3. **Looking for role clarity?** Consult [Roles & Personas](./octoacme-roles-and-personas.md).

4. **Managing risks or dependencies?** Reference [Risk Management & Communication](./octoacme-risks-and-communication.md).

5. **Using Copilot Spaces?** Add these docs to `.copilot/` as context for role-specific guidance and process-informed assistance.

## Principles in Action

| Principle | How We Practice It |
|-----------|-------------------|
| **Customer-first** | Success metrics tied to customer outcomes; regular stakeholder feedback |
| **Iterative delivery** | Small PRs, frequent releases, continuous deployment when possible |
| **Clear ownership** | Named PM and PdM per project; defined RACI matrix |
| **Data-informed** | Dashboards for velocity, success metrics, error tracking |
| **Psychological safety** | Blameless retrospectives, encouraged feedback, learning from failures |

## Next Steps

- **For a specific project phase**, navigate to the corresponding guide above
- **For process questions**, check the [FAQ](./octoacme-project-management-overview.md#how-to-use-these-docs)
- **To contribute improvements**, follow the process documented in your project's contribution guidelines

---

**Last Updated:** 2026-09-12  
**Version:** 1.0  
**Maintained by:** OctoAcme Project Management Team
