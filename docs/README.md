# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents. The README provides a short summary of our approach and direct links to each process document to help contributors and new team members quickly find relevant guidance.

OctoAcme runs cross-functional projects with a lightweight, iterative process that begins with a clear initiation step and continues through planning, execution, release, and retrospective phases. Initiation requires a one‑pager that defines the problem, objective, success metrics, stakeholders, and an initial timeline; work moves into planning only when metrics, stakeholder alignment, and team availability are confirmed. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release milestone map.

Execution is tracked on a project board using standard columns (Backlog, Ready, In Progress, In Review, QA, Done) and follows a disciplined PR workflow that favors small PRs, links issues and acceptance criteria, and gates merges on CI (tests, linting, and security scans) plus required reviews. Communication is structured: daily standups for delivery-level progress and blockers, weekly delivery syncs and PM/PdM alignment, monthly stakeholder updates, and documented escalation paths (team → PM → Product Lead → Sponsor). Incident and status templates help keep messages clear and consistent.

Quality assurance is built into every stage: unit and integration tests for new code, end-to-end smoke tests for critical flows, CI gating, and manual QA for acceptance when appropriate. Releases require passing CI and security checks, drafted release notes, a rollback plan, and staging verification before production deploys. Retrospectives capture learnings and convert them into actionable improvements tracked in the backlog.

Docs in this folder:
- octoacme-project-management-overview.md — High-level overview of roles, principles, lifecycle, and how to use these docs
- octoacme-project-initiation.md — Guidance and templates for project initiation and one-pagers
- octoacme-project-planning.md — Planning activities, backlog templates, and risk management
- octoacme-execution-and-tracking.md — Team rhythm, workflows, QA, and execution checklist
- octoacme-risks-and-communication.md — Risk register, communication templates, and escalation paths
- octoacme-release-and-deployment.md — Release types, deployment checklist, and rollback playbook
- octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and tracking improvements
- octoacme-roles-and-personas.md — Role summaries and responsibilities
