# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Personas

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Extended Personas

### Technical Lead

#### Role Summary
Technical Leads own the technical strategy, architecture decisions, and code quality for a project. They ensure technical excellence while managing technical risks and helping the team overcome blockers.

#### Responsibilities
- Define and review technical design and architecture
- Establish code quality standards and review practices
- Identify and mitigate technical risks early in planning
- Mentor developers and support skill development
- Collaborate with Product Manager on technical feasibility and trade-offs
- Escalate capacity or technical blocker issues to Engineering Manager

#### Goals
- Maintain high technical standards and system health
- Reduce technical debt and improve maintainability
- Enable efficient, scalable delivery of features

#### Primary Interactions
- **With Developers**: Reviews designs, conducts code reviews, mentors on technical decisions
- **With Product Manager**: Discusses technical feasibility, scope trade-offs, and architectural implications
- **With Release Engineer**: Coordinates deployment readiness and infrastructure needs
- **With Engineering Manager**: Escalates resource constraints and capacity issues

#### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments and design feedback
- Technical planning and feasibility assessments

---

### Engineering Manager

#### Role Summary
Engineering Managers provide leadership, career guidance, and capacity planning support to development teams. They handle people-level escalations and enable the team to execute effectively.

#### Responsibilities
- Plan and allocate team capacity across projects
- Conduct performance reviews and provide career guidance
- Support skill development and mentorship
- Handle people-level escalations and conflicts
- Coordinate resources across squads or teams
- Remove organizational blockers

#### Goals
- Build high-performing, sustainable teams
- Develop individual capabilities and career growth
- Ensure team capacity aligns with project demands

#### Primary Interactions
- **With Technical Lead**: Collaborates on capacity planning and removes structural blockers
- **With Project Manager**: Coordinates on resource allocation and people-level escalations
- **With Developers**: Provides coaching, feedback, and career support

#### Typical Communication
- 1:1 meetings with direct reports
- Cross-team resource allocation discussions
- Escalation resolution meetings

---

### Design Lead / UX Designer

#### Role Summary
Design Leads own the user experience, including usability research, design artifacts, accessibility considerations, and design-to-development handoff. They ensure products are intuitive and accessible.

#### Responsibilities
- Conduct user research and usability testing
- Create design specs, wireframes, and high-fidelity mockups
- Ensure accessibility standards are met (WCAG compliance)
- Review implementation for design fidelity
- Participate in acceptance criteria definition
- Collaborate with QA on design-based acceptance testing

#### Goals
- Deliver intuitive, accessible user experiences
- Reduce rework from design misalignment
- Advocate for user needs in trade-off discussions

#### Primary Interactions
- **With Product Manager**: Collaborates on acceptance criteria and user requirements
- **With Developers**: Provides design handoff and answers implementation questions
- **With QA Lead**: Coordinates on design-based acceptance testing
- **With Accessibility Lead**: Partners on accessibility requirements and validation

#### Typical Communication
- Design reviews and feedback sessions
- Design specs and handoff documentation
- Usability testing reports and findings

---

### QA Lead / Test Owner

#### Role Summary
QA Leads define testing strategy, coordinate test coverage across all levels (unit, integration, end-to-end), and sign off on quality readiness. They ensure acceptance criteria are validated and defects are tracked.

#### Responsibilities
- Define test strategy and test plan for the project
- Coordinate unit, integration, and end-to-end test coverage
- Create and maintain test cases aligned to acceptance criteria
- Sign off on acceptance criteria completion
- Track and triage defects
- Coordinate pre-release smoke testing with Release Engineer
- Conduct manual QA for feature acceptance when needed

#### Goals
- Ensure quality gates are met before release
- Reduce production defects through comprehensive testing
- Provide clear quality signals for go/no-go decisions

#### Primary Interactions
- **With Developers**: Collaborates on test strategy and reviews test coverage
- **With Technical Lead**: Coordinates on technical and integration test approach
- **With Design Lead**: Validates design-based acceptance criteria
- **With Release Engineer**: Coordinates pre-release testing and sign-off

#### Typical Communication
- Test plan and test case reviews
- Defect triage and status reports
- Quality readiness assessments

---

### Release Engineer / SRE

#### Role Summary
Release Engineers own deployment pipelines, rollback procedures, observability, and post-deployment verification. They ensure releases are safe, reliable, and observable.

#### Responsibilities
- Design and maintain deployment pipelines and automation
- Document rollback and mitigation procedures
- Prepare and execute deployment steps
- Verify post-deployment health and run smoke tests
- Coordinate with QA on pre-release testing
- Establish observability and alerting for new features
- Coordinate incident response and handover to Support

#### Goals
- Enable safe, frequent deployments with minimal risk
- Maintain system reliability and uptime
- Provide clear visibility into system health

#### Primary Interactions
- **With Developers**: Ensures code and infrastructure are deployment-ready
- **With QA Lead**: Coordinates pre-release testing and acceptance
- **With Technical Lead**: Discusses infrastructure and deployment architecture
- **With Support / On-call**: Hands over runbooks and receives incident alerts

#### Typical Communication
- Deployment readiness reviews
- Rollback and mitigation plan reviews
- Post-deploy verification reports

---

### Data Analyst / Analytics Owner

#### Role Summary
Data Analysts define how success is measured, instrument code to capture key events, validate success metrics, and produce dashboards for stakeholder visibility.

#### Responsibilities
- Define measurement and instrumentation plan aligned to success metrics
- Implement event tracking and analytics infrastructure
- Validate that metrics are correctly implemented and flowing
- Create dashboards and reporting for stakeholders
- Analyze results and communicate insights
- Identify data quality issues and gaps

#### Goals
- Enable data-driven decisions about product impact
- Measure outcomes and iterate based on evidence
- Reduce guesswork in prioritization and trade-offs

#### Primary Interactions
- **With Product Manager**: Aligns on success metrics and validates outcome measurement
- **With Developers**: Collaborates on event instrumentation and data collection
- **With Stakeholders**: Presents dashboards and communicates findings

#### Typical Communication
- Measurement plan documentation
- Dashboard reviews and metric reviews
- Data analysis and impact reports

---

### Security Reviewer / Security SME

#### Role Summary
Security Reviewers ensure that security controls are properly designed and implemented, threats are addressed, dependencies are scanned, and compliance requirements are met.

#### Responsibilities
- Conduct threat modeling and security design reviews
- Review code for security vulnerabilities
- Scan dependencies and manage vulnerability remediation
- Ensure compliance with security standards and policies
- Provide security signoff before release when required
- Maintain security incident runbooks and playbooks

#### Goals
- Prevent security incidents and data breaches
- Ensure compliance with regulatory and internal standards
- Build security culture and awareness

#### Primary Interactions
- **With Technical Lead**: Partners on architectural security and threat modeling
- **With Developers**: Reviews code for security issues and guides remediation
- **With Release Engineer**: Provides security signoff before production deployments
- **With Product Manager**: Advises on security implications of feature decisions

#### Typical Communication
- Security design reviews and threat modeling sessions
- Vulnerability reports and remediation guidance
- Security compliance checklists

---

### Support / On-call Representative

#### Role Summary
Support Representatives provide the customer perspective during project planning, own runbook accuracy, and coordinate incident triage and customer communications.

#### Responsibilities
- Participate in planning to identify support-relevant scenarios
- Review and maintain runbooks for new features
- Triage and route incidents to appropriate teams
- Coordinate customer communication during incidents
- Provide feedback on feature usability from support interactions
- Ensure post-incident retrospectives capture root causes

#### Goals
- Reduce MTTR (mean time to recovery) for incidents
- Improve customer experience and reduce support burden
- Create clear, actionable runbooks

#### Primary Interactions
- **With Release Engineer**: Receives runbook handover and incident alerts
- **With Product Manager**: Provides customer insights during planning
- **With Developers**: Coordinates on incident root cause analysis
- **With Project Manager**: Escalates support-impacting risks

#### Typical Communication
- Rollout briefings and runbook walkthroughs
- Incident triage and escalation reports
- Post-incident retrospectives

---

### Accessibility Lead

#### Role Summary
Accessibility Leads ensure products meet accessibility standards (WCAG, Section 508), conduct accessibility audits, and verify remediation of accessibility issues.

#### Responsibilities
- Define accessibility requirements and standards (e.g., WCAG 2.1 AA)
- Conduct accessibility audits and testing (automated and manual)
- Identify and track accessibility defects
- Review design and code for accessibility compliance
- Verify fixes for accessibility issues
- Provide guidance on accessible design and implementation patterns

#### Goals
- Ensure products are usable by people with disabilities
- Meet legal and regulatory accessibility requirements
- Build inclusive products that serve all users

#### Primary Interactions
- **With Design Lead**: Partners on accessible design patterns and requirements
- **With QA Lead**: Coordinates on accessibility testing and validation
- **With Developers**: Provides guidance on accessible implementation
- **With Product Manager**: Ensures accessibility is prioritized in acceptance criteria

#### Typical Communication
- Accessibility audit reports and findings
- Accessible design patterns and guidance
- Accessibility testing results and signoff

---

### Compliance / Legal Reviewer

#### Role Summary
Compliance and Legal Reviewers ensure projects adhere to legal, regulatory, and contractual requirements. They are engaged for projects involving regulated data, external obligations, or policy changes.

#### Responsibilities
- Review projects for legal and regulatory implications
- Ensure data handling complies with regulations (GDPR, CCPA, etc.)
- Review contractual obligations and licensing requirements
- Provide guidance on compliance-related design decisions
- Approve legal and compliance aspects before release

#### Goals
- Prevent legal and regulatory violations
- Protect the organization from compliance risk
- Ensure contractual obligations are met

#### Primary Interactions
- **With Product Manager**: Engaged early to flag compliance requirements
- **With Technical Lead**: Reviews data handling and architecture for compliance
- **With Release Engineer**: Provides compliance signoff before production release

#### Typical Communication
- Compliance requirement reviews
- Legal and regulatory guidance documents
- Compliance sign-off checklists

---

## Role Interaction Matrix

| Interaction | Primary Role | Secondary Role | Typical Activity |
|---|---|---|---|
| Planning & Kickoff | Product Manager | All | Define goals, scope, and success metrics |
| Design | Design Lead | Product Manager, Developers | Create specs, wireframes, and acceptance criteria |
| Implementation | Developers | Technical Lead, Design Lead | Build features, write tests, participate in code review |
| Quality Assurance | QA Lead | Developers, Design Lead, Release Engineer | Test coverage, defect triage, acceptance sign-off |
| Security Review | Security Reviewer | Technical Lead, Developers, Release Engineer | Threat modeling, code review, compliance check |
| Capacity Planning | Engineering Manager | Project Manager, Technical Lead | Allocate resources, identify blockers |
| Accessibility Check | Accessibility Lead | Design Lead, QA Lead, Developers | Audit, test, verify remediation |
| Deployment | Release Engineer | QA Lead, Developers, Support | Deploy, verify, hand over runbooks |
| Incident Response | Support, Release Engineer | All (escalation) | Triage, communicate, remediate, retrospect |
| Measurement | Data Analyst | Product Manager, Developers | Instrument, validate, analyze, report |

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning a project, confirm that all relevant personas are identified and have clear owners.
- Refer to the Interaction Matrix to understand which roles need to coordinate on specific activities.
- Use this document during onboarding to help new team members understand their role and key relationships.
