# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Assign roles according to the project's needs; a person may hold more than one role, but the responsibilities and decision owners should remain clear to the team.

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

### Interactions with Other Roles
- Work with the Product Manager and Business Analyst to clarify desired outcomes, requirements, and acceptance criteria.
- Coordinate with the Technical Lead / Architect on design decisions, technical risks, and implementation consistency.
- Work with QA / Testing on testability, defect investigation, and fixes.
- Coordinate with the Release / Operations Owner on deployment needs, monitoring, and operational handoff.
- Keep the Project Manager informed about estimates, progress, blockers, dependencies, and delivery risks.

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
- Weekly alignment with the Project Manager and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions with Other Roles
- Set product direction and priority; partner with the Project Manager, who coordinates delivery plans, schedules, and project communication.
- Consult stakeholders and the UX / Product Designer or Researcher to understand user needs and validate solutions.
- Work with the Business Analyst to turn product intent into clear, traceable requirements and acceptance criteria.
- Consult the Technical Lead / Architect and Developers on feasibility, effort, dependencies, and technical trade-offs.
- Agree with QA / Testing on how acceptance criteria and outcomes will be validated.

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

### Interactions with Other Roles
- Coordinate with the Product Manager to align delivery plans with product priorities and decisions; the Product Manager remains accountable for product outcomes and backlog priority.
- Work with the Technical Lead / Architect, Developers, QA / Testing, and Release / Operations Owner to track estimates, dependencies, readiness, and risks.
- Maintain clear owners and due dates for decisions, actions, and escalations without taking over the accountable role's decision.
- Keep stakeholders informed of progress, changes, risks, and decisions through the agreed communication cadence.

---

## QA / Testing

### Role Summary
QA / Testing plans and performs validation so the team can determine whether delivered work meets acceptance criteria and agreed quality expectations. The role may be filled by dedicated QA specialists, developers, or a combination, depending on the project.

### Responsibilities
- Review requirements and acceptance criteria for testability and identify gaps early
- Define and execute appropriate test coverage, including functional, regression, integration, and exploratory testing as relevant
- Record defects with reproducible details, coordinate triage, and verify fixes
- Report test results, quality risks, and release-blocking issues to the team
- Contribute to the Definition of Done and release-readiness evidence

### Goals
- Detect issues early and reduce the risk of defects reaching users
- Provide clear evidence of quality and known limitations
- Ensure important user and business workflows are covered

### Typical Communication
- Test plans, test cases, and execution results
- Defect reports and triage discussions
- Readiness updates with the delivery team

### Interactions with Other Roles
- Partner with the Product Manager and Business Analyst to clarify expected behavior and ensure acceptance criteria are verifiable.
- Coordinate with Developers on test data, testability, defect diagnosis, and retesting.
- Consult the UX / Product Designer or Researcher on usability and accessibility checks.
- Share quality status and blockers with the Project Manager, who coordinates their impact on schedule and communications.
- Provide test evidence and known risks to the Release / Operations Owner for the release decision and operational plan.

---

## Stakeholders

### Role Summary
Stakeholders are people or groups affected by, funding, sponsoring, governing, or providing expertise for the project. They supply context and feedback and make or contribute to decisions within their area of authority; they do not automatically own day-to-day delivery.

### Responsibilities
- Explain needs, constraints, and business context relevant to the project
- Provide timely feedback, subject-matter expertise, and decisions or approvals when requested
- Review milestones or outcomes and raise material changes in needs or constraints
- Help identify impacted groups and support appropriate communications or adoption

### Goals
- Ensure the project addresses relevant business and user needs
- Make informed decisions within their authority
- Understand impacts, progress, and outcomes

### Typical Communication
- Discovery and requirements workshops
- Milestone reviews, decision requests, and project updates
- Change, launch, or adoption communications as appropriate

### Interactions with Other Roles
- Work with the Product Manager to clarify needs, trade-offs, priorities, and success measures.
- Provide subject-matter input to the Business Analyst, who records and traces requirements and decisions.
- Receive coordinated project updates and decision requests from the Project Manager.
- Provide feedback at agreed checkpoints; Developers and QA / Testing use it through the Product Manager or agreed review process rather than treating informal feedback as a change in scope.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead / Architect guides technical design and engineering consistency, helping the team make sound decisions about quality attributes, system boundaries, and technical dependencies.

### Responsibilities
- Lead technical discovery and recommend designs that meet product needs and engineering standards
- Identify cross-component dependencies, technical risks, and quality attributes such as reliability, security, and performance
- Facilitate technical decisions and document significant trade-offs
- Support estimation and sequencing with Developers and the Project Manager
- Guide implementation and technical reviews without replacing the Product Manager's ownership of product priority

### Goals
- Deliver a coherent, secure, maintainable technical solution
- Surface technical constraints and risks early
- Enable Developers to make consistent implementation decisions

### Typical Communication
- Architecture or technical design notes
- Design reviews and engineering discussions
- Technical risk and dependency updates during planning and delivery

### Interactions with Other Roles
- Consult the Product Manager on product intent and explain technical options and trade-offs.
- Coordinate with the Project Manager on technical dependencies, estimates, sequencing, and risk escalation.
- Guide Developers through design decisions and review implementation for alignment with the agreed approach.
- Work with QA / Testing to account for technical risks and non-functional quality in validation.
- Align with the Release / Operations Owner on deployment architecture, observability, resilience, and rollback considerations.

---

## UX / Product Designer or Researcher

### Role Summary
The UX / Product Designer or Researcher helps the team understand user needs and shape workflows and interfaces that are usable, accessible, and consistent with product goals.

### Responsibilities
- Conduct or synthesize user research and identify user needs and pain points
- Create and validate user flows, prototypes, and design specifications
- Consider accessibility, usability, and consistency in design decisions
- Communicate design intent, edge cases, and interaction states to the delivery team

### Goals
- Improve user understanding, usability, and accessibility
- Validate important assumptions before or during implementation
- Help ensure delivered experiences support intended product outcomes

### Typical Communication
- Research findings and user feedback
- User flows, prototypes, and design reviews
- Design handoff and usability findings

### Interactions with Other Roles
- Partner with the Product Manager to connect user evidence and design options to product outcomes and priorities.
- Consult stakeholders and subject-matter experts to understand user contexts and constraints.
- Work with the Business Analyst to ensure user workflows and edge cases are reflected in requirements.
- Collaborate with Developers and the Technical Lead / Architect to assess feasibility and clarify design intent.
- Coordinate with QA / Testing on usability and accessibility validation.
- Keep the Project Manager informed of design dependencies or decisions that may affect delivery timing.

---

## Business Analyst

### Role Summary
The Business Analyst clarifies business processes and translates agreed needs into clear, traceable requirements that the team can implement and verify.

### Responsibilities
- Elicit and document business rules, process flows, assumptions, and requirements
- Define or refine acceptance criteria with the Product Manager and relevant stakeholders
- Maintain traceability between needs, requirements, decisions, and validation
- Identify ambiguity, exceptions, and process impacts before implementation
- Support change analysis when requirements or business constraints evolve

### Goals
- Reduce rework caused by unclear or incomplete requirements
- Ensure requirements reflect agreed business intent
- Make requirements understandable to both delivery and business participants

### Typical Communication
- Requirements and process documentation
- Workshops, decision records, and change-impact summaries
- Acceptance criteria reviews with Developers and QA / Testing

### Interactions with Other Roles
- Work with the Product Manager, who owns product direction and priority, to elaborate requirements without independently changing scope.
- Consult stakeholders for business rules and context, and confirm decisions with the appropriate decision owner.
- Coordinate with the UX / Product Designer or Researcher to capture user flows and exceptions.
- Clarify requirements and acceptance criteria with Developers and QA / Testing so they are implementable and verifiable.
- Share requirement changes and their impacts with the Project Manager for coordination across plans, dependencies, and communications.

---

## Release / Operations Owner

### Role Summary
The Release / Operations Owner coordinates operational readiness and the practical steps needed to deploy, monitor, and support a release. This role may be held by an operations specialist, release manager, or another assigned team member.

### Responsibilities
- Identify deployment, environment, access, support, and operational dependencies
- Coordinate release readiness checks, deployment steps, monitoring, and rollback or mitigation plans
- Confirm ownership for post-release verification and incident response
- Capture operational issues and feed them into the appropriate follow-up process

### Goals
- Make releases predictable and supportable
- Reduce deployment risk and shorten time to detect or mitigate issues
- Ensure operational ownership is clear before and after launch

### Typical Communication
- Release plans and readiness checklists
- Deployment coordination and operational handoff
- Monitoring and post-release verification updates

### Interactions with Other Roles
- Coordinate release dates, dependencies, and stakeholder communications with the Project Manager.
- Confirm scope and acceptance expectations with the Product Manager; this role coordinates readiness and does not independently approve product scope.
- Work with the Technical Lead / Architect and Developers on deployment design, configuration, observability, and rollback steps.
- Review validation results and unresolved quality risks with QA / Testing before release.
- Coordinate support and adoption handoffs with stakeholders and relevant operational teams.

---

## Role Assignment and Collaboration

- Assign only the roles needed for the project's size, risk, and context; a person may cover multiple roles when capacity and conflicts of responsibility allow.
- Make the accountable decision owner clear for product priorities, delivery coordination, technical design, requirements, quality evidence, and operational readiness.
- Consult the relevant roles before decisions that affect their areas, and record significant decisions, owners, and follow-up actions in the project's agreed artifacts.
- Raise unclear ownership, conflicting decisions, or changes in scope with the Project Manager for coordination and the appropriate accountable role for resolution.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
