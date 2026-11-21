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

## Scrum Master / Delivery Lead

### Role Summary
The Scrum Master / Delivery Lead facilitates the delivery process, removes impediments, protects team focus and capacity, and helps the team improve how it plans and collaborates.

### Responsibilities
- Facilitate ceremonies such as standups, planning, reviews, and retrospectives
- Identify, escalate, and remove delivery impediments
- Help the team maintain sustainable capacity and iterative practices
- Coach the team on collaboration, transparency, and continuous improvement
- Track action items for process improvements

### Goals
- Improve team flow and predictability
- Reduce avoidable delays and recurring blockers
- Strengthen a psychologically safe, improvement-oriented delivery culture

### Interactions with Existing Roles
- Works with the Project Manager to surface risks, dependencies, and delivery constraints and to coordinate escalation.
- Partners with Product Managers to keep scope and priorities clear during planning and backlog refinement.
- Supports Developers and QA/Testing by improving team ceremonies and removing process barriers.
- Provides stakeholders with a clear view of team-level progress and impediments.

### Typical Communication
- Daily standups and delivery ceremonies
- Impediment logs and retrospective action items
- Planning and capacity discussions

---

## Business Analyst / Product Analyst

### Role Summary
The Business Analyst / Product Analyst connects stakeholder needs, business context, and delivery requirements. The role turns high-level outcomes into clear, validated requirements and acceptance criteria.

### Responsibilities
- Gather and analyze stakeholder and user needs
- Clarify requirements, assumptions, constraints, and dependencies
- Support backlog refinement and acceptance-criteria definition
- Map current and future workflows
- Coordinate requirement validation and traceability

### Goals
- Ensure work is based on understood needs
- Reduce ambiguity and rework
- Improve requirement traceability and solution validation

### Interactions with Existing Roles
- Works with Product Managers to refine outcomes and translate them into actionable backlog items.
- Partners with Developers and QA/Testing to clarify behavior, edge cases, acceptance criteria, and test scenarios.
- Coordinates with Project Managers on requirement dependencies and changes to scope or timelines.
- Engages stakeholders to validate needs and proposed solutions.

### Typical Communication
- Backlog refinement and requirement workshops
- Process and data-analysis artifacts
- Acceptance-criteria and traceability reviews

---

## UX/UI Designer

### Role Summary
The UX/UI Designer focuses on usability, accessibility, and consistent interaction design. The role researches user needs and translates them into feasible, validated experiences.

### Responsibilities
- Conduct or support user research and usability validation
- Create flows, wireframes, prototypes, and interface specifications
- Define interaction patterns and accessibility requirements
- Review implementations for design and usability quality
- Document reusable design decisions and patterns

### Goals
- Improve usability and accessibility
- Create consistent, understandable product experiences
- Reduce late-stage design rework

### Interactions with Existing Roles
- Collaborates with Product Managers to define user outcomes, information architecture, and prioritization.
- Works with Developers to ensure designs are feasible and implementable and participates in design reviews.
- Partners with QA/Testing to validate usability and accessibility acceptance criteria.
- Shares findings and design trade-offs with Project Managers and stakeholders.

### Typical Communication
- Design critiques and user research sessions
- Prototypes and implementation reviews
- Accessibility and acceptance-criteria discussions

---

## QA / Testing Lead

### Role Summary
The QA / Testing Lead owns the test strategy and quality gates across the project. The role coordinates coverage and confirms that accepted work meets the team's Definition of Done.

### Responsibilities
- Define test strategy, scope, and quality gates
- Coordinate automated, integration, end-to-end, and manual testing
- Identify quality risks and coverage gaps
- Establish release exit criteria and report readiness
- Lead defect triage and track recurring quality issues

### Goals
- Prevent defects from reaching production
- Provide early, actionable feedback on quality
- Maintain useful and sustainable test coverage

### Interactions with Existing Roles
- Works with Developers to build testability into features and expand automated coverage.
- Partners with Product Managers to validate acceptance criteria and user-critical flows.
- Reports readiness and quality risks to Project Managers and release stakeholders.
- Coordinates with Delivery Leads on impediments affecting testing and release confidence.

### Typical Communication
- Test plans and quality dashboards
- Defect triage and release-readiness reviews
- Sprint and release acceptance discussions

---

## Site Reliability / Platform Engineer

### Role Summary
The Site Reliability / Platform Engineer provides reliable, observable infrastructure and delivery capabilities. The role reduces operational risk and improves the team's ability to deploy and support services.

### Responsibilities
- Define reliability, availability, capacity, and observability expectations
- Build and maintain environments, automation, and platform capabilities
- Improve monitoring, alerting, logging, and incident tooling
- Participate in incident response and service reviews
- Establish operational readiness and runbook standards

### Goals
- Increase platform reliability and deployment confidence
- Reduce operational toil and recovery time
- Improve observability and actionable alerting

### Interactions with Existing Roles
- Supports Developers with deployment, infrastructure, and operational guidance.
- Coordinates with QA/Testing on environment and reliability test coverage.
- Works with Project Managers to identify infrastructure dependencies, risks, and delivery constraints.
- Advises Product Managers on reliability trade-offs and operational impact.

### Typical Communication
- Architecture and operational-readiness reviews
- On-call and incident postmortems
- Capacity, performance, and observability dashboards

---

## Security / Compliance Lead

### Role Summary
The Security / Compliance Lead ensures that project work follows security and compliance requirements and that risks are identified and managed throughout delivery.

### Responsibilities
- Translate security and compliance requirements into project controls
- Conduct or coordinate threat modeling and security reviews
- Review security findings, mitigations, and exceptions
- Confirm required scans, controls, evidence, and approvals before release
- Support incident and vulnerability response planning

### Goals
- Reduce security and compliance risk
- Make controls understandable and verifiable
- Prevent avoidable release and audit delays

### Interactions with Existing Roles
- Advises Developers on secure design and implementation and participates in technical risk reviews.
- Partners with QA/Testing on security test coverage and remediation validation.
- Works with Project Managers to maintain risks, exceptions, dependencies, and release gates.
- Provides Product Managers and stakeholders with clear security trade-offs and release status.

### Typical Communication
- Threat-model and risk reviews
- Compliance evidence and security findings
- Security gates and exception decisions

---

## Release / Deployment Lead

### Role Summary
The Release / Deployment Lead coordinates release readiness and execution. The role brings technical, quality, operational, and communication work together into a controlled deployment plan.

### Responsibilities
- Define deployment windows and release checklists
- Coordinate release approvals, backups, smoke tests, and rollback plans
- Verify post-deployment checks and release completion
- Coordinate release communications and known issues
- Capture release outcomes and follow-up actions

### Goals
- Deliver releases predictably and safely
- Reduce failed deployments and recovery time
- Improve stakeholder confidence and communication

### Interactions with Existing Roles
- Coordinates with Developers and Site Reliability / Platform Engineers on build, deployment, monitoring, and rollback execution.
- Works with QA/Testing to confirm test and smoke-test completion.
- Partners with Project Managers on release schedules, dependencies, stakeholder updates, and escalations.
- Notifies Product Managers and stakeholders of readiness, impact, known issues, and completion.

### Typical Communication
- Release plans and deployment checklists
- Go/no-go reviews and incident escalations
- Release announcements and post-release verification

---

## Data Analyst / Data Product Manager

### Role Summary
The Data Analyst / Data Product Manager defines and measures outcomes using reliable data. The role ensures that instrumentation, analysis, and evidence inform prioritization and validation.

### Responsibilities
- Define success metrics and measurement plans
- Specify instrumentation and data-quality requirements
- Analyze adoption, behavior, reliability, and experiment results
- Explain evidence and uncertainty to decision-makers
- Track outcomes after delivery

### Goals
- Improve decisions with accurate, relevant evidence
- Confirm whether delivered work achieves intended outcomes
- Reduce metric and instrumentation gaps

### Interactions with Existing Roles
- Works with Product Managers to define success metrics and interpret outcomes.
- Partners with Developers and Platform Engineers on instrumentation and data availability.
- Coordinates with QA/Testing on data correctness and telemetry validation.
- Provides Project Managers and stakeholders with concise progress and impact reporting.

### Typical Communication
- Measurement plans and dashboards
- Experiment and outcome reviews
- Data-quality and metric-definition discussions

---

## Change / Training Lead

### Role Summary
The Change / Training Lead prepares people, teams, and stakeholders for new capabilities. The role plans adoption, communications, documentation, and learning activities.

### Responsibilities
- Assess change impact and training needs
- Create or coordinate documentation and enablement materials
- Plan stakeholder and user communications
- Schedule training and feedback activities
- Track adoption and unresolved enablement gaps

### Goals
- Improve adoption and readiness
- Reduce disruption from process or product changes
- Close the feedback loop between users and delivery teams

### Interactions with Existing Roles
- Works with Product Managers to understand outcomes and user segments.
- Partners with Developers and UX/UI Designers to keep documentation, workflows, and training aligned with the solution.
- Coordinates rollout timing and stakeholder communications with Project Managers.
- Shares user feedback and adoption issues with delivery teams and stakeholders.

### Typical Communication
- Change-impact plans and training schedules
- Release-readiness and adoption updates
- User feedback and enablement retrospectives

---

## Customer Support / Success Representative

### Role Summary
The Customer Support / Success Representative represents customer experience after and before launch. The role raises recurring issues, supports users, and feeds real-world insights into planning and release decisions.

### Responsibilities
- Capture recurring product issues and customer feedback
- Provide technical or operational support and known-issue guidance
- Participate in release planning and communication readiness
- Escalate high-impact customer risks
- Confirm that feedback and resolutions reach the appropriate delivery owners

### Goals
- Improve customer experience and issue resolution
- Surface unmet needs and adoption barriers early
- Strengthen feedback loops between customers and delivery teams

### Interactions with Existing Roles
- Reports customer evidence and urgent risks to Product Managers for prioritization.
- Escalates release and operational concerns to Project Managers and Platform or Support leadership.
- Collaborates with Developers and QA/Testing on reproduction, fixes, validation, and known-issue communication.
- Coordinates enablement and customer messaging with the Change / Training Lead.

### Typical Communication
- Support trends and customer feedback summaries
- Incident and release updates
- Product backlog and resolution follow-up

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Role personas describe functions and accountabilities rather than fixed job titles. One person or team may cover multiple personas, and assignments should be made explicitly during planning.
