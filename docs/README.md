# OctoAcme Project Management Docs

## Overview

OctoAcme uses a lightweight, stage-gated approach to run projects from initiation through planning, execution, release, and continuous improvement. Each initiative begins with a concise Project One-pager that defines the problem, objective, success metrics, stakeholders, timeline, and initial risks. Once approved at the decision gate, work is turned into a prioritized backlog, estimated and sized for iterative delivery.

Work is executed using an iterative delivery model with a visible project board and clear workflows (Backlog → Ready → In Progress → In Review → QA → Done). Backlog items use a standard template (title, description, acceptance criteria, priority, estimate, owner) to ensure readiness for implementation and review. Pull requests should be small when possible, link to the originating issue and acceptance criteria, run CI checks (tests, linting, security scans), and require review and approval before merging.

Roles and ownership are explicit: the Project Manager (PM) coordinates delivery, scheduling, risks and communications; the Product Manager (PdM) defines outcomes and prioritization; Developers implement and test; and QA validates acceptance criteria and quality gates. Communication cadences include daily standups for the delivery team, weekly PM+PdM syncs, sprint demos/reviews, and regular stakeholder updates. These cadences help keep dependencies, risks, and decisions visible.

Quality is enforced through automated and manual checks. Developers are expected to include unit and integration tests for new logic, and teams run end-to-end smoke tests for critical flows before release. Security scanning is performed in CI. Releases follow a checklist (staging verification, automated deployment pipelines where possible, post-deploy checks and rollback plans) and use release notes to document notable changes. Retrospectives and a risk register drive continuous improvement and mitigation.

## Docs
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risks & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## How to use this README
Use this file as the central index for OctoAcme process documentation and as the first stop for new contributors. Each linked doc provides guidance for a specific part of the lifecycle (initiation, planning, execution, release, risk management, and retrospectives).

## How to contribute
To add or update process docs, open an issue using the "Add Content to Project Management Process Docs" template located at `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`. Fill in the fields (process doc, summary, rationale, suggested content, acceptance criteria) and assign / discuss with stakeholders as needed. Small edits can be proposed via pull requests that reference the issue.

## Acceptance criteria
- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)

---

*This README was added to satisfy issue #2: [README — project management processes summary and links to docs](https://github.com/manoj13194/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2).



PR review: initial README addition
