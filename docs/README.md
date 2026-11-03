# OctoAcme Project Management Docs

This directory contains OctoAcme’s core project management process documentation. Together, these guides describe how teams initiate, plan, deliver, release, and improve projects, providing a shared reference for contributors and stakeholders.

## Project Management Process Summary

OctoAcme uses an iterative project lifecycle: initiate work by defining the problem, goals, success measures, stakeholders, timeline, and initial risks; move approved initiatives into planning; then execute, release, and close with a retrospective. Planning turns goals into a prioritized backlog with acceptance criteria, estimates, owners, milestones, a Definition of Done, and an initial QA approach. During execution, teams track work on a project board and aim to deliver in small, reviewable increments.

Responsibilities are shared across clearly defined roles. The Project Manager coordinates delivery, schedules, risks, dependencies, and communications. The Product Manager sets outcomes, prioritizes work, and measures product impact. Developers build and test features, contribute to estimates and reviews, and identify technical risks. QA and testing validate acceptance criteria and quality, while stakeholders provide input and approvals.

Communication combines regular team coordination with stakeholder updates and escalation. Teams use standups, delivery or status reviews, demos, and milestone updates; risks and dependencies are recorded with owners and mitigations, reviewed regularly, and escalated as needed. The source guides describe different standup cadences, so teams should agree on the cadence that fits their needs.

Quality assurance is part of planning, development, and release. Teams define acceptance criteria and a Definition of Done, write unit tests for new logic, add integration tests where applicable, and run end-to-end smoke tests for critical flows. Pull requests should be small where possible, link to an issue and acceptance criteria, pass automated tests and linting, and receive the required review. Releases require passing CI and security scans, release notes, a rollback or mitigation plan, staging smoke tests, and post-deployment verification. Retrospectives turn lessons into owned, trackable improvements.

## Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
