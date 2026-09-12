# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. The goal of this update is to make the personas more actionable: include common activities, success signals, collaboration touchpoints, and example Copilot persona prompts so the definitions can be used directly in exercises and Copilot Spaces.

---

## Developers (Engineers)

### Role summary
Developers design, build, test, and deliver software components. They collaborate with product, design, and project leads to implement features that meet acceptance criteria, performance, and quality standards.

### Typical activities
- Implement features and fixes to meet acceptance criteria
- Write and maintain unit, integration, and end-to-end tests
- Improve observability and address production issues
- Participate in design, architecture, and code reviews
- Help estimate, plan, and break down work
- Keep documentation and onboarding artifacts up to date

### Responsibilities
- Deliver working, well-tested code that meets acceptance criteria
- Maintain test suites and CI pipelines
- Create and update technical documentation and runbooks
- Proactively propose technical improvements and risk mitigations

### Success signals
- Pull requests are small, well-described, and reviewed promptly
- High test coverage and low flakiness in CI
- Low mean time to recovery (MTTR) for incidents in owned areas
- Clear, up-to-date documentation for components they own

### Collaboration touchpoints
- Daily standups and sprint planning
- Pairing sessions and design reviews
- PR descriptions and code review comments
- Technical design docs and architecture conversations

### Example Copilot persona prompt
"You are an OctoAcme Developer focused on backend services. Help me write tests and a concise PR description for: [short feature summary]. Include deployment considerations and rollback steps."

---

## Product Managers

### Role summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Typical activities
- Define problem statements, user journeys, and success metrics
- Create and prioritize the roadmap and backlog
- Run user research, experiments, and beta programs
- Communicate trade-offs and decisions to stakeholders

### Responsibilities
- Maintain a prioritized backlog aligned with the roadmap
- Clearly specify acceptance criteria and business context
- Validate solutions with real users and metrics
- Coordinate cross-functional work with engineering and design

### Success signals
- Improvements in key product metrics (engagement, retention, conversion)
- Clear prioritization and fewer urgent scope changes
- High-quality acceptance criteria that reduce rework
- Positive user feedback from experiments and releases

### Collaboration touchpoints
- Weekly alignment with engineering and design leads
- Roadmap updates, prioritization sessions, and stakeholder briefings
- Acceptance criteria, feature specs, and release reviews

### Example Copilot persona prompt
"You are an OctoAcme Product Manager. Given this user problem: [one-sentence problem], propose 3 prioritized experiments to validate solutions, with expected metrics and success thresholds."

---

## Project Managers (Delivery Leads)

### Role summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Typical activities
- Create and maintain project plans and timelines
- Track risks, dependencies, and resource constraints
- Facilitate ceremonies: kickoff, planning, standups, retrospectives
- Report status and escalations to stakeholders

### Responsibilities
- Keep cross-team dependencies visible and resolved
- Maintain project documentation (status reports, decision logs)
- Drive efficient meeting cadence and actionable outcomes

### Success signals
- Projects delivered on time and within scope
- Clear traceability of decisions and mitigations for risks
- Reduced meeting overload and clearer action ownership

### Collaboration touchpoints
- Regular syncs with PMs, product, and engineering leads
- Risk and dependency reviews with stakeholders
- Coordination via project boards and milestone checkpoints

### Example Copilot persona prompt
"You are an OctoAcme Project Manager. Summarize the current milestone status for [project name], list top 3 risks with owners, and propose mitigations for each."

---

## Suggested additions: RACI sketch
To make the roles actionable during exercises and real projects, use a lightweight RACI (Responsible, Accountable, Consulted, Informed) for common activities.

- Feature delivery: Developers (R), Product Manager (A), Project Manager (C), QA (C)
- Incident resolution: Developers (R), Project Manager (A), Product Manager (I), Support (C)
- Roadmap decisions: Product Manager (A), Developers (C), Project Manager (I)

Include a RACI table in project kickoff docs so expectations are explicit.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be loaded as a Copilot Spaces persona prompt to shape role-specific guidance. Example prompts are provided above to make adoption straightforward.

---

## Notes for maintainers
- Keep this doc lightweight and example-driven; add role-specific prompts or RACI examples per project when needed.
- Consider adding more personas (Design, QA/Testing, Support/Customer Success, Security/Compliance) as the project grows.
