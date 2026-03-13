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
- Unit tests for new logic (Developer)
- Integration tests where applicable (Developer + QA Analyst)
- End-to-end smoke tests for critical flows before release (QA Analyst)
- Security scanning in CI (DevOps Engineer)
- Manual QA for feature acceptance when needed (QA Analyst)
- QA Analyst signs off on acceptance criteria before items move to Done
- Defects are logged, triaged, and prioritized collaboratively by Developers, QA, and Project Managers

## Documentation Touchpoints
- Documentation Lead participates in sprint reviews to identify documentation needs
- Each backlog item's Definition of Done includes a documentation check
- Technical changes that affect user-facing behavior require Documentation Lead review before release
- Runbooks and process changes are updated by Documentation Lead in coordination with DevOps Engineers and Developers

## DevOps & Environment Management
- DevOps Engineers maintain CI/CD pipelines and ensure build/test environments are stable
- Environment readiness for QA is confirmed by DevOps Engineers before QA cycles begin
- Infrastructure changes follow the same PR and review workflow as code changes

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Test environments ready and validated by DevOps Engineer
- [ ] QA Analyst has reviewed and signed off on acceptance criteria for completed items
- [ ] Documentation Lead has reviewed changes affecting user-facing behavior
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
