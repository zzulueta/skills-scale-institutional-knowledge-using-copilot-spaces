# OctoAcme Project Management Docs

This folder contains OctoAcme's project management processes, templates, and reference guides. The goal is to centralize how we plan, execute, release, and learn from cross-functional projects so team members can quickly find consistent guidance and templates. These docs are intentionally lightweight and focused on iterative delivery, clear ownership, and measurable outcomes.

OctoAcme follows a simple lifecycle: validate and authorize work with a Project One-pager, turn approved initiatives into a prioritized and estimated backlog, execute using a project board and CI-backed small pull requests, and release with smoke tests and rollback plans. Quality is enforced through automated tests, security scanning, mandatory PR reviews, and manual QA where required. Retrospectives and tracked action items close the loop for continuous improvement.

Roles and responsibilities are explicit: Product Managers (PdMs) define outcomes and success metrics, Project Managers (PMs) coordinate delivery and risk, Developers implement and test, and QA validates acceptance. Communication is cadence-driven with daily standups, weekly delivery syncs, milestone demos, and monthly stakeholder updates. Risks and incidents are logged in a Risk Register and escalated through defined paths.

Use this README as the single entry point for the process docs below. Keep project-specific artifacts (Project One-pager, Roadmap, Risk Register, Release Notes) in the project repository and link them from the relevant project README. To propose updates to these process docs, file an issue using the "Add Content to Project Management Process Docs" template in .github/ISSUE_TEMPLATE/.

## Key Process Documents
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

## How to use these docs
- New team members: read the Overview then the Initiation and Planning guides to understand how projects start and are set up.
- Delivery teams: follow Execution & Tracking during sprints and reference the Release & Deployment guide before any production rollout.
- PMs/PdMs: maintain the Project One-pager, Risk Register, and release notes; schedule retrospectives and track action items.
