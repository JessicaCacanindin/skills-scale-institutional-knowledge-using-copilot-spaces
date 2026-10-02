# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

The supporting roles below clarify handoffs across discovery, delivery, quality, and release; they complement rather than replace the Project Manager's delivery coordination or the Product Manager's product decisions. One person may fill multiple roles on a smaller project.

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

## Business Analysts

### Role Summary
Business Analysts turn stakeholder needs into clear, testable requirements so the team can plan and deliver the intended outcomes.

### Responsibilities
- Elicit and document workflows, requirements, and acceptance criteria with stakeholders and the Product Manager
- Identify gaps, assumptions, and dependencies before work is estimated
- Clarify requirements with Developers and QA/Testing during implementation and validation

### Goals
- Reduce rework caused by ambiguous requirements
- Make backlog items ready for planning and testing

### Key Interactions and Escalations
- Bring scope or priority trade-offs to the Product Manager, who owns backlog decisions; flag impacts to the Project Manager for the plan and risk register
- Work with Developers and QA/Testing to resolve interpretation gaps before acceptance criteria are used to validate work

---

## Technical Leads / Engineering Leads

### Role Summary
Technical Leads guide implementation and engineering coordination while Developers remain responsible for building and testing the software.

### Responsibilities
- Guide technical design, estimates, integration points, and implementation sequencing with Developers
- Surface technical risks and dependencies to the Project Manager during planning and execution
- Review engineering readiness, including maintainability, testability, and operational concerns

### Goals
- Enable feasible delivery plans and reliable implementations
- Resolve technical blockers early

### Key Interactions and Escalations
- Recommend technical approaches with Developers and consult the Product Manager on scope or value trade-offs
- Escalate unresolved technical risks or cross-team dependencies to the Project Manager for coordination; flag quality concerns to the QA Lead

---

## QA Leads

### Role Summary
QA Leads coordinate the quality approach across QA/Testing and the delivery team, including release-readiness evidence.

### Responsibilities
- Define test strategy, coverage expectations, and validation of acceptance criteria with QA/Testing
- Coordinate testing with Developers and track defects and residual quality risks
- Report test results and readiness concerns before release

### Goals
- Find gaps early and give the team clear evidence of product quality
- Support informed release decisions

### Key Interactions and Escalations
- Align acceptance criteria with the Product Manager and Business Analyst; work with Developers on fixes and retesting
- Escalate blocking defects or unmet quality criteria to the Project Manager and Release Manager, with the Product Manager involved in scope or acceptance trade-offs

---

## Release Managers / Delivery Managers

### Role Summary
Release Managers coordinate the release plan and deployment handoffs so changes can be shipped and verified predictably.

### Responsibilities
- Coordinate release timing, dependencies, release notes, and deployment readiness with the Project Manager
- Check that testing, security scans, rollback plans, and post-deployment verification are prepared
- Organize release communications and handoff to Support / Operations

### Goals
- Reduce release risk and avoid missed handoffs
- Keep stakeholders informed about delivery timing and outcomes

### Key Interactions and Escalations
- Confirm technical and quality readiness with Developers, the Technical Lead, and QA Lead; align timing with the Project Manager and Product Manager
- Escalate unmet pre-release requirements or deployment blockers to the Project Manager and relevant leads before proceeding; coordinate incident response and rollback with Support / Operations if needed

---

## Support / Operations Leads

### Role Summary
Support / Operations Leads represent service operations and customer support needs throughout planning, release, and follow-up.

### Responsibilities
- Identify operational impacts, support needs, and observability or incident risks during planning
- Prepare on-call and support handoffs for releases and monitor post-release issues
- Feed recurring incidents and customer feedback into improvement work

### Goals
- Ensure the team can support changes after deployment
- Turn operational feedback into better future releases

### Key Interactions and Escalations
- Work with Developers and the Release Manager on runbooks, monitoring, verification, and rollback; share customer-impact insights with the Product Manager
- Escalate incidents through the on-call response and alert the Project Manager and stakeholders to delivery or customer impacts

---

## Design / UX Leads

### Role Summary
Design / UX Leads guide user-centered design so planned features are usable and accessible.

### Responsibilities
- Research user needs and translate them into designs and usability or accessibility criteria
- Review proposed workflows with stakeholders and the Product Manager before implementation
- Collaborate with Developers and QA/Testing to validate the intended experience

### Goals
- Catch usability and accessibility gaps before release
- Make user needs visible in planning and acceptance criteria

### Key Interactions and Escalations
- Advise the Product Manager on experience trade-offs and the Business Analyst on acceptance criteria; coordinate design handoffs with Developers and QA/Testing
- Escalate unresolved usability or accessibility risks to the Product Manager for scope decisions and the Project Manager for schedule impacts

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
