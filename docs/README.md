# OctoAcme Project Management Docs

OctoAcme uses a lightweight, iterative project management approach that prioritizes customer value, clear ownership, and measurable outcomes. Projects progress through a simple lifecycle—Initiation, Planning, Execution, Release, and Close—with decision gates (for example, a Project One-pager) to ensure objectives, stakeholders, and capacity are aligned before planning begins. The Project One-pager and core artifacts (backlog, risk register, release notes) are used to keep objectives visible and measurable throughout delivery.

Planning breaks approved initiatives into small, shippable increments with explicit acceptance criteria and a Definition of Done. Teams estimate using T-shirt sizing or story points, maintain a prioritized backlog, and create timeboxed iterations. Execution is driven by a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a Pull Request workflow that requires small, linked PRs, passing CI (including security scans), and required approvals before merge.

Roles and responsibilities are explicit: Project Managers coordinate delivery, Product Managers own outcomes and prioritization, Developers implement and test, and QA validates acceptance. Communication is cadenced and frequent—daily standups for blockers and progress, weekly delivery syncs, PM–PdM alignment meetings, sprint demos/reviews, and monthly stakeholder updates. Risks and dependencies are tracked in a Risk Register and escalated via a defined path (team → PM → Product Lead → Sponsor).

Quality is enforced through a mix of automated and manual practices: unit and integration tests, smoke/end-to-end tests for critical flows, CI-based checks (tests, linting, security scans), and manual QA where needed. Releases follow a checklist-driven process including staging verification and a rollback plan; incident and rollback playbooks are in place to minimize production impact. Retrospectives capture learnings as action items tracked in the backlog to ensure continuous improvement.

## Process docs in this folder

- [Project Management Overview](octoacme-project-management-overview.md)  
- [Project Initiation Guide](octoacme-project-initiation.md)  
- [Project Planning](octoacme-project-planning.md)  
- [Execution & Tracking](octoacme-execution-and-tracking.md)  
- [Risk Management & Communication](octoacme-risks-and-communication.md)  
- [Release & Deployment Guide](octoacme-release-and-deployment.md)  
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)  
- [Roles and Personas](octoacme-roles-and-personas.md)
