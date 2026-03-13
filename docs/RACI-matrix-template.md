# RACI Matrix Template

## Overview
Use this RACI matrix to clarify roles and responsibilities across key project activities. Assign each role one of the following designations for each activity:

| Code | Meaning |
|---|---|
| **R** | **Responsible** — Does the work |
| **A** | **Accountable** — Owns the outcome; approves completion |
| **C** | **Consulted** — Provides input before or during the activity |
| **I** | **Informed** — Kept up to date on progress or outcomes |

> Each activity should have exactly one **A** (Accountable). Multiple **R**, **C**, and **I** assignments are acceptable.

---

## Project Roles Reference
For full role descriptions, see [Roles and Personas](./octoacme-roles-and-personas.md).

| Abbreviation | Role |
|---|---|
| PM-Prod | Product Manager |
| PM-Proj | Project Manager |
| Dev | Developer |
| UX | UX Designer |
| QA | QA Analyst |
| SME | Subject Matter Expert |
| DocLead | Documentation Lead |
| DevOps | DevOps Engineer |

---

## Sample RACI Matrix

> Replace or extend the activities below to match your project's specific needs.

| Activity | PM-Prod | PM-Proj | Dev | UX | QA | SME | DocLead | DevOps |
|---|---|---|---|---|---|---|---|---|
| Define problem statement & success metrics | A | C | C | C | I | C | I | I |
| Prioritize and groom product backlog | A | C | C | C | C | C | I | I |
| Conduct user research & UX design | C | I | C | A/R | C | C | I | I |
| Estimate and plan sprint work | C | A | R | C | C | I | I | I |
| Clarify domain requirements | C | I | C | C | C | A/R | I | I |
| Implement features | C | I | A/R | C | C | I | I | I |
| Write and maintain unit/integration tests | I | I | A/R | I | C | I | I | I |
| Define and execute test plans | C | C | C | I | A/R | C | I | I |
| Set up and maintain CI/CD pipelines | I | I | C | I | C | I | I | A/R |
| Manage environments (staging, prod) | I | C | C | I | C | I | I | A/R |
| Create and update documentation | C | I | C | C | C | C | A/R | I |
| Conduct sprint reviews / demos | C | A | R | R | R | C | I | I |
| Review and sign off on acceptance criteria | A | C | C | C | R | C | I | I |
| Manage risks and dependencies | C | A/R | C | I | I | C | I | C |
| Execute deployment to production | I | A | C | I | C | I | I | R |
| Run post-deploy verification | I | C | C | I | R | I | I | A/R |
| Draft and publish release notes | C | C | C | I | C | I | A/R | I |
| Lead incident response | I | A | C | I | C | I | I | R |
| Facilitate retrospective | I | A/R | C | C | C | I | I | I |

---

## How to Use This Template

1. **Copy this file** into your project repository or documentation space.
2. **Customize the activity list** to reflect the specific phases and deliverables of your project.
3. **Assign RACI codes** for each role and activity combination.
4. **Review with your team** to ensure alignment and shared understanding.
5. **Update as needed** when project scope or team structure changes.

---

## Tips for Effective RACI Assignments

- Avoid assigning **R** to too many roles for a single activity — it can dilute ownership.
- If an activity has no **A**, assign one to ensure clear accountability.
- Use **C** sparingly — over-consulting slows decisions.
- Ensure that everyone listed as **I** has a clear communication channel for receiving updates.
- Revisit the RACI matrix at the start of each major phase or when new team members join.

---

*This template aligns with OctoAcme project management principles. See the full [Project Management Overview](./octoacme-project-management-overview.md) for context.*
