# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testing

### Role Summary
QA and testing roles validate that solutions meet functional, non-functional, and acceptance requirements before and after release.

### Responsibilities
- Define and execute test strategies and test plans
- Validate acceptance criteria and functional quality
- Identify defects and quality risks
- Participate in release readiness reviews
- Coordinate manual, automated, integration, and security testing as applicable

### Goals
- Prevent defects and provide reliable release evidence
- Improve testability and cycle quality
- Maintain traceability from requirements to verification

### Typical Communication
- Test plans and defect reports
- QA results in delivery syncs and release reviews
- Collaboration in backlog refinement and acceptance discussions

### Interactions with existing personas
- **Developers:** pair on testability and defect resolution.
- **Product Managers:** validate that acceptance criteria reflect intended outcomes.
- **Project Managers:** report quality status, dependencies, and release risks.
- **Stakeholders:** provide acceptance or usability evidence when requested.

---

## Stakeholders

### Role Summary
Stakeholders provide business context, domain knowledge, approvals, and feedback needed to shape and accept project outcomes.

### Responsibilities
- Clarify needs and constraints
- Review proposals, decisions, and major outcomes
- Provide timely feedback and approvals
- Validate that delivered solutions support intended business goals

### Goals
- Ensure outcomes address real needs
- Maintain awareness of scope, risk, and delivery decisions
- Provide clear, timely direction

### Typical Communication
- Milestone reviews and stakeholder updates
- Requirements workshops and decision sessions
- Formal approvals and feedback channels

### Interactions with existing personas
- **Product Managers:** align priorities, outcomes, and feedback.
- **Project Managers:** receive status and resolve decisions or escalations.
- **Developers and QA:** validate demonstrations and acceptance evidence when appropriate.

---

## Release Manager / Release Lead

### Role Summary
The Release Manager or Release Lead owns release readiness and coordinates a safe, observable deployment.

### Responsibilities
- Coordinate release calendars and deployment windows
- Maintain readiness checks, rollback plans, and post-release verification
- Confirm merge readiness and release scope
- Coordinate deployment, stakeholder notices, and handoff to operations

### Decision authority and boundaries
- Approves whether a scheduled release is ready to deploy based on agreed readiness criteria
- Escalates unresolved scope, quality, security, or rollback concerns instead of waiving them independently
- Does not change product scope or approve technical exceptions unless explicitly authorized

### Goals
- Deliver releases predictably with low operational risk
- Make deployment and rollback responsibilities clear
- Improve release evidence and observability

### Typical Communication
- Release checklists and go/no-go reviews
- Deployment schedules and status updates
- Incident, rollback, and post-release communication

### Interactions with existing personas
- **Developers:** confirm merge, version, configuration, and rollback readiness.
- **QA / Testing:** confirm test completion and acceptance evidence.
- **Product Managers:** confirm release scope, rollout intent, and customer-facing impact.
- **Project Managers:** track schedule, dependencies, stakeholder communications, and escalation paths.
- **Stakeholders:** provide clear release notices, timing, and impact summaries.
- **Support / Operations Lead:** coordinate cutover, monitoring, support readiness, and known issues.

---

## Business Analyst

### Role Summary
The Business Analyst translates stakeholder needs into validated requirements and testable acceptance criteria.

### Responsibilities
- Elicit and validate requirements and constraints
- Clarify dependencies and trace needs to delivery outcomes
- Refine acceptance criteria and maintain requirement traceability
- Identify ambiguities and unresolved decisions early

### Decision authority and boundaries
- Owns requirement clarity and traceability within the agreed scope
- Recommends requirement and dependency decisions for approval by the Product Manager or other designated owner
- Does not independently reprioritize the backlog or waive acceptance criteria

### Goals
- Reduce ambiguity and rework
- Connect stakeholder needs to measurable outcomes
- Ensure requirements are feasible and testable

### Typical Communication
- Requirements workshops and refinement sessions
- Acceptance criteria and traceability documentation
- Dependency and decision logs

### Interactions with existing personas
- **Product Managers:** clarify outcomes, validate requirements, and support backlog refinement and prioritization.
- **Developers:** assess feasibility and surface design or integration dependencies.
- **QA / Testing:** ensure requirements and acceptance criteria are verifiable.
- **Project Managers:** identify scope, schedule, and dependency impacts.
- **Stakeholders:** gather needs, validate interpretation, and obtain requirement decisions.

---

## Scrum Master / Delivery Lead

### Role Summary
The Scrum Master or Delivery Lead facilitates team flow, removes impediments, and promotes continuous improvement.

### Responsibilities
- Facilitate ceremonies and maintain healthy team practices
- Identify, track, and help remove delivery impediments
- Encourage a predictable, sustainable delivery cadence
- Facilitate retrospectives and follow-up on improvement actions

### Decision authority and boundaries
- Coaches the team on process and facilitation
- Does not own product prioritization or project scope
- Escalates unresolved cross-team impediments to the Project Manager or appropriate functional lead

### Goals
- Improve flow, predictability, and team effectiveness
- Increase transparency around impediments and cycle quality
- Sustain a culture of feedback and iterative improvement

### Typical Communication
- Standups, planning, reviews, and retrospectives
- Impediment and improvement action tracking
- Flow and delivery health updates

### Interactions with existing personas
- **Project Managers:** coordinate delivery plans, cross-team dependencies, and escalations.
- **Developers:** surface blockers and improve planning and review flow.
- **Product Managers:** reinforce backlog readiness and clarify process-level priorities.
- **QA / Testing:** improve cycle quality and align verification with delivery flow.
- **Stakeholders:** facilitate demonstrations or feedback when invited.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect provides technical direction, identifies architectural risks, and aligns implementation choices with project goals.

### Responsibilities
- Define technical direction and key implementation patterns
- Review architecture and integration dependencies
- Identify technical and security risks and proposed controls
- Support developers with design decisions and technical reviews

### Decision authority and boundaries
- Owns technical recommendations and design consistency within agreed constraints
- Escalates significant cost, schedule, security, or scope trade-offs to the Project and Product Managers
- Does not independently change committed scope or security policy

### Goals
- Deliver maintainable, scalable, and secure solutions
- Reduce architectural risk and integration surprises
- Improve engineering decision quality

### Typical Communication
- Architecture and design reviews
- Technical risk and dependency updates
- Implementation guidance and engineering forums

### Interactions with existing personas
- **Developers:** provide guidance and review designs and implementation approaches.
- **Project Managers:** identify technical dependencies, estimates, milestones, and escalation needs.
- **Product Managers:** explain feasibility and trade-offs that affect scope or outcomes.
- **QA / Testing:** align testability, observability, and quality controls.
- **Security Lead:** define and review architectural controls and risk mitigations.
- **Stakeholders:** communicate material technical constraints and decisions when needed.

---

## UX Designer / Researcher

### Role Summary
The UX Designer or Researcher represents customer and usability needs through research, interaction design, and validation.

### Responsibilities
- Translate user and stakeholder needs into usable interaction models
- Conduct or synthesize user research and usability validation
- Create prototypes or design specifications
- Recommend usability acceptance criteria and accessibility considerations

### Decision authority and boundaries
- Owns user experience recommendations and design deliverables
- Escalates decisions that materially change scope, priority, or committed outcomes
- Does not independently commit implementation scope or replace Product Manager prioritization

### Goals
- Improve usability, accessibility, and customer satisfaction
- Validate solutions against real user needs
- Reduce late-stage rework caused by unclear interaction expectations

### Typical Communication
- Research summaries and design critiques
- Prototypes and usability sessions
- Acceptance criteria and handoff documentation

### Interactions with existing personas
- **Product Managers:** collaborate on problem definition, priorities, and outcome validation.
- **Developers:** align interaction patterns with feasible implementations and technical constraints.
- **QA / Testing:** define usability and accessibility acceptance criteria and verification approaches.
- **Stakeholders:** obtain domain context and validate proposed solutions where appropriate.
- **Project Managers:** identify design dependencies and review impacts on milestones.

---

## Security Lead

### Role Summary
The Security Lead defines security expectations, identifies risk, and coordinates necessary reviews and remediations.

### Responsibilities
- Define relevant security requirements and controls
- Review risks, threats, vulnerabilities, and exceptions
- Coordinate security testing and remediation
- Provide security approval or escalation at release gates

### Decision authority and boundaries
- Owns security assessments and recommendations within established policy
- Can require escalation or withholding of release when defined security gates are unmet
- Does not override approved risk acceptance or policy without appropriate authority

### Goals
- Reduce security risk and time to remediation
- Make security requirements explicit and testable
- Improve readiness and confidence at release gates

### Typical Communication
- Threat and risk assessments
- Security findings and remediation plans
- Security reviews and incident escalations

### Interactions with existing personas
- **Developers:** provide remediation guidance and review security-sensitive implementation.
- **QA / Testing:** coordinate security test coverage and validation evidence.
- **Technical Lead / Architect:** align controls with architecture and implementation patterns.
- **Project Managers:** escalate schedule or scope impacts and track remediation commitments.
- **Release Manager / Release Lead:** confirm applicable security gates before deployment.
- **Stakeholders:** communicate material risk, exceptions, or incident impact when required.

---

## Support / Operations Lead

### Role Summary
The Support or Operations Lead represents operational readiness and the ability to operate and support the solution in production.

### Responsibilities
- Define operational readiness and support requirements
- Coordinate monitoring, runbooks, diagnostics, escalation, and on-call preparation
- Participate in cutover and post-release validation
- Provide known issues and support impact to stakeholders

### Decision authority and boundaries
- Owns operational readiness assessments and supportability recommendations
- Escalates unresolved production, staffing, monitoring, or rollback concerns
- Does not change product scope or waive release criteria independently

### Goals
- Improve production stability and supportability
- Reduce time to detect and resolve operational issues
- Ensure customers and support teams are prepared for release

### Typical Communication
- Readiness reviews and operational checklists
- Monitoring, incident, and runbook handoffs
- Support notices and known issue updates

### Interactions with existing personas
- **Release Manager / Release Lead:** coordinate cutover, monitoring, rollback, and release communications.
- **Developers:** provide diagnostics requirements and coordinate fixes or troubleshooting.
- **QA / Testing:** validate operational scenarios and support workflows.
- **Project Managers:** report service readiness and schedule stakeholder notices.
- **Product Managers:** align support impact and customer communications with rollout decisions.
- **Stakeholders:** provide operational status, known issues, and support guidance.

---

## Role Assignment Guidance

These personas describe responsibilities and handoffs; they do not require separate positions on every team. One person may hold multiple roles, and a role may be shared across team members. Assign accountability clearly for each project, avoid duplicating ownership, and document role assignments in the Project Charter or delivery plan. A role should be added to the working team only when it provides clear decision-making or risk coverage for the work at hand.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
