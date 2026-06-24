# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles

Every project requires clear ownership and cross-functional collaboration. The following roles are fundamental:

- **Project Manager (PM)**: coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Developers**: implement features, collaborate on design and testability.
- **QA/Testing**: validate quality and acceptance criteria.

## Extended Roles

Depending on project scope and complexity, the following roles may also be engaged:

- **Technical Lead**: owns technical design, architecture, and code quality.
- **Engineering Manager**: handles capacity planning and people-level escalations.
- **Design Lead / UX Designer**: owns user experience and accessibility considerations.
- **Release Engineer / SRE**: manages deployment pipelines and operational readiness.
- **Data Analyst / Analytics Owner**: defines measurement and validates success metrics.
- **Security Reviewer / SME**: ensures security controls and compliance.
- **Support / On-call Representative**: provides customer perspective and incident coordination.
- **Accessibility Lead**: ensures accessibility standards are met.
- **Compliance / Legal Reviewer**: ensures regulatory and contractual compliance (as needed).

See **[OctoAcme Personas](octoacme-roles-and-personas.md)** for detailed responsibilities, goals, and interaction patterns for all roles.

## Stakeholders

**Stakeholders** are individuals or groups who have interest in, provide input to, or are affected by the project outcome. Common stakeholder types include:

- Executive sponsors (business leaders who approve and fund the project)
- Customer representatives (who validate that outcomes meet customer needs)
- Cross-functional partners (teams whose work depends on or affects this project)
- Subject matter experts (who provide domain knowledge or specialized input)

Stakeholder engagement is coordinated by the PM and PdM. See [Risk Management & Communication](octoacme-risks-and-communication.md) for engagement strategies.

## Key Artifacts

- **Project Charter / One-pager**: problem, goal, success metrics, timeline, team
- **Roadmap and Release Plan**: phased delivery schedule and major milestones
- **Sprint/Iteration Backlog**: prioritized work items with acceptance criteria
- **Acceptance Criteria & Definition of Done**: quality gates and completion standards
- **Risk Register**: identified risks with impact, likelihood, and mitigation plans
- **Retrospective notes and action items**: lessons learned and improvements

## Lifecycle (high-level)

1. **Initiation**: problem statement, stakeholders, high-level timeline.
2. **Planning**: scope, resources, milestones, dependencies.
3. **Execution**: build, test, review, iterate.
4. **Release**: deploy, verify, announce.
5. **Close & Retrospective**: capture learnings and next steps.

See [Project Initiation Guide](octoacme-project-initiation.md), [Project Planning](octoacme-project-planning.md), [Execution & Tracking](octoacme-execution-and-tracking.md), and [Release & Deployment Guide](octoacme-release-and-deployment.md) for detailed workflows for each phase.

## Communication Cadence

- **Weekly sync between PM + PdM**: align on priorities, risks, and stakeholder updates
- **Twice-weekly standups for delivery team** (or as agreed): sync on progress and blockers
- **Monthly stakeholder updates**: communicate progress, risks, and upcoming milestones
- **Ad-hoc escalations as needed**: address blockers and risks requiring immediate attention

## When to Engage Extended Roles

- **Technical Lead**: required for architecturally significant projects or high-risk technical decisions
- **Engineering Manager**: engaged for multi-team projects or significant resource constraints
- **Design Lead**: required for user-facing features or major UX changes
- **Release Engineer**: required for infrastructure changes, deployments, or reliability concerns
- **Data Analyst**: required to measure feature impact or customer outcomes
- **Security Reviewer**: required for projects handling sensitive data or implementing security features
- **Support / On-call Rep**: recommended for customer-facing features or operational changes
- **Accessibility Lead**: required for any user-facing feature; recommended for all releases
- **Compliance / Legal Reviewer**: required for regulated data handling or contractual obligations

## How to Use These Docs

- Keep the **Project Charter** updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- Refer to **[OctoAcme Personas](octoacme-roles-and-personas.md)** to clarify roles and responsibilities during kickoff.
- Use the **[Execution & Tracking guide](octoacme-execution-and-tracking.md)** for day-to-day workflow management.
- Consult **[Risk Management & Communication](octoacme-risks-and-communication.md)** for escalation and stakeholder communication strategies.
