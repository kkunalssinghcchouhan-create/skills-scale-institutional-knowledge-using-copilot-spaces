# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Incident & Blocker Communication Protocol

### Purpose
Ensure timely, clear communication of execution blockers and maintain a searchable archive of incidents and resolutions.

### Communication Channels by Severity
- **Level 1 (Team Blocker)**: Mentioned in daily standup; logged in project board as blocked issue
- **Level 2 (Cross-team Impact)**: Async notification in team Slack channel + @mention in GitHub issue; escalation email to PM and dependent team leads
- **Level 3 (Business Impact)**: Real-time Slack/call with sponsor + documented in Risk Register; follow-up email summary within 24 hours

### Incident Documentation Template
When logging blockers or incidents, capture:
- **Blocker ID**: Link to related GitHub issue
- **Detection Timestamp**: When the blocker was first identified
- **Description & Business Impact**: What is blocked and why it matters
- **Affected Components/Teams**: Which systems and teams are impacted
- **Root Cause**: Initial assessment (update as investigation progresses)
- **Mitigation Steps & Timeline**: Actions being taken and expected resolution time
- **Resolution & Lessons Learned**: How it was resolved and what to do differently next time

### Tracking & Follow-up
- All Level 2+ incidents must have a GitHub issue linked in the Risk Register
- Weekly review of open blockers in delivery sync
- Post-resolution: Document root cause and prevention steps in relevant process doc or team wiki
- Incidents resolved in same sprint: Brief retrospective note added to sprint retrospective
- Maintain a searchable incident log for organizational learning

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Incident/blocker communication channels defined and shared with team
- [ ] Template for blocker documentation accessible in team wiki or GitHub repo
- [ ] Process for post-incident documentation and process updates documented
