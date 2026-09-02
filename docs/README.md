# OctoAcme Project Management Documentation

OctoAcme’s project management processes center on lightweight, repeatable workflows that take an initiative from a validated one‑pager through planning, execution, release, and continuous improvement. Projects begin with a Project One‑pager to capture the problem, measurable success metrics, stakeholders, and a high‑level timeline; a decision gate moves work into planning only once success metrics, priority, and team availability are confirmed. Planning focuses on a kickoff, a prioritized backlog with acceptance criteria, scoped estimates, a Definition of Done, and a release plan with identified dependencies.

Execution uses an explicit project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a pull request process that emphasizes small, reviewable changes, clear acceptance criteria, and automated CI checks (tests, linting, security scanning) before requesting reviews. Roles are clearly defined: Product Managers set outcomes and prioritize, Project Managers coordinate delivery, Developers implement and test, QA validates acceptance criteria, and stakeholders provide approvals and input. Risk is tracked in a simple Risk Register and escalations run from team-level triage up to sponsor-level involvement for business-impacting issues.

Communication is structured and frequent: daily standups for progress and blockers, weekly delivery syncs to surface risks and demo progress, PM/PdM weekly alignment, and monthly stakeholder updates. Incident and release communications are templated and a clear escalation path exists for security incidents and critical failures. Retrospectives occur after sprints, releases, or incidents, produce prioritized action items, and track improvements back into the backlog.

Quality assurance and release controls are integral: unit and integration tests, end‑to‑end smoke tests for critical flows, manual QA for acceptance when needed, and CI security scans. The Release & Deployment guide prescribes pre‑release checklists (passing CI, release notes, rollback plan), staged deployments with smoke tests, and a rollback/incident playbook for critical failures. These practices support iterative delivery with clear ownership, risk management, and continuous improvement.

## Quick Start
1. Read the [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction.  
2. Review the [Roles and Personas](octoacme-roles-and-personas.md) to understand key team members.  
3. Follow the guide that matches your project phase (see Process Guides below).

## Process Guides (by phase)
- Initiation: [Project Initiation Guide](octoacme-project-initiation.md)  
- Planning: [Project Planning](octoacme-project-planning.md)  
- Execution & Tracking: [Execution & Tracking](octoacme-execution-and-tracking.md)  
- Risk & Communication: [Risk Management & Communication](octoacme-risks-and-communication.md)  
- Release & Deployment: [Release & Deployment Guide](octoacme-release-and-deployment.md)  
- Retrospective & Continuous Improvement: [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Core Principles
- Customer-first: prioritize customer value and usability  
- Iterative delivery: deliver small, testable increments  
- Clear ownership: each project has a named PM and Product Lead  
- Data-informed: measure impact and iterate based on evidence  
- Psychological safety: encourage feedback and learning

## Core Roles (quick reference)
- Product Manager — defines outcomes, prioritizes backlog, measures success  
- Project Manager — coordinates delivery, manages schedule, risks, and communications  
- Developers — implement features and tests  
- QA/Testing — validates acceptance criteria and quality

## How to contribute or request updates
- Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to request new content or updates.  
- Keep the README as the central entry point and update the TOC when adding new process documents.

## Acceptance Criteria (for README)
- Provides a central, discoverable hub for all process docs.  
- Includes a brief overview of OctoAcme processes, TOC links, and quick role references.  
- Aligns with existing process documents.