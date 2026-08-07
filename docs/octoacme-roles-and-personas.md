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

### Interactions with Other Roles
- **QA/Testing Lead**: Collaborate on test design and accept quality feedback
- **Technical Lead**: Receive guidance on architecture and best practices
- **Project Manager**: Report progress and blockers in standups
- **Product Manager**: Clarify acceptance criteria and feature requirements

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

### Interactions with Other Roles
- **Project Manager**: Align on scope, timeline, and dependencies
- **Developers**: Define acceptance criteria and validate solutions
- **QA/Testing Lead**: Define quality expectations and acceptance criteria
- **Technical Lead**: Discuss technical trade-offs and feasibility
- **Stakeholder/Sponsor**: Provide business outcomes and prioritization

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
- **Product Manager**: Align on scope, timeline, and dependencies
- **Developers**: Track progress and manage blockers
- **Technical Lead**: Escalate technical risks and dependencies
- **Scrum Master/Agile Coach**: Collaborate on process and sprint management
- **Stakeholder/Sponsor**: Report status and escalate decisions

---

## QA / Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and acceptance criteria validation. They collaborate with developers and product managers to ensure features meet quality standards before release.

### Responsibilities
- Create and maintain test plans and QA strategy for projects
- Define and execute unit, integration, and end-to-end tests
- Validate features against acceptance criteria
- Identify and document defects with clear reproduction steps
- Coordinate security scanning and compliance validation
- Participate in Definition of Done review
- Work with developers to improve testability and code quality

### Goals
- Minimize defects reaching production
- Provide early feedback to developers on testability
- Ensure confidence in release readiness
- Reduce cycle time for bug discovery and resolution

### Typical Communication
- Sprint planning and retrospectives
- Test plan reviews with developers
- QA sign-off on PRs before merge
- Defect triage in daily standups
- Pre-release smoke test coordination

### Interactions with Other Roles
- **Developers**: Collaborate on test design, accept feedback on testability
- **Product Managers**: Align on acceptance criteria and quality expectations
- **Project Managers**: Report blockers and quality risks
- **Technical Lead**: Collaborate on performance and security test requirements
- **Security Officer**: Coordinate on security test coverage and compliance validation

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide architectural decisions, design patterns, and technical strategy. They work with developers to ensure solutions are scalable, maintainable, and aligned with long-term technical vision.

### Responsibilities
- Review and approve technical designs and architecture decisions
- Identify technical risks and propose mitigation strategies
- Mentor developers on best practices and code quality
- Participate in code reviews for complex or high-risk changes
- Drive technical documentation and knowledge sharing
- Coordinate with other teams on integration points and dependencies

### Goals
- Ensure technical quality and consistency across projects
- Reduce technical debt and long-term maintenance burden
- Enable team scalability through clear patterns and documentation
- Anticipate and mitigate architectural risks early

### Typical Communication
- Design review sessions and architecture discussions
- Code review comments on architectural decisions
- Technical roadmap alignment with Product Managers
- Risk register updates on technical blockers

### Interactions with Other Roles
- **Developers**: Provide guidance, approve designs, mentor
- **Project Managers**: Escalate technical risks and dependencies
- **QA/Testing Lead**: Collaborate on testability and performance requirements
- **Security Officer**: Collaborate on security architecture and design
- **Product Manager**: Discuss technical trade-offs and feasibility

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors represent business priorities, provide budget and resource authorization, and ensure projects align with organizational strategy. They are the executive voice in project decisions.

### Responsibilities
- Approve project initiation and high-level scope
- Provide business context and strategic alignment
- Authorize resource allocation and budget
- Review and approve release decisions
- Resolve priority conflicts between competing projects
- Receive milestone and status updates
- Make go/no-go decisions at key gates

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with organizational strategy
- Minimize scope creep and resource overruns
- Enable quick decision-making on trade-offs

### Typical Communication
- Project kickoff and approval gate meetings
- Monthly or milestone-based status updates
- Release approval and go/no-go decisions
- Escalation when decisions require executive input

### Interactions with Other Roles
- **Project Managers**: Receive risk reports and ask for decisions
- **Product Managers**: Align on business outcomes and metrics
- **Technical Lead**: Briefed on major technical trade-offs
- **Developers**: Presented with solutions and trade-offs when needed

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team ceremonies, remove process blockers, and coach teams on agile practices. They focus on team effectiveness and continuous improvement.

### Responsibilities
- Facilitate daily standups, planning, and retrospectives
- Help teams define and adhere to Definition of Done
- Identify and escalate process blockers
- Coach team members on agile principles and practices
- Track team metrics (velocity, cycle time, burndown)
- Support retrospective action items and process improvements
- Remove obstacles to team productivity

### Goals
- Maximize team productivity and flow
- Reduce process friction and blocker resolution time
- Build a culture of continuous improvement
- Enable team autonomy and psychological safety

### Typical Communication
- Daily standup facilitation
- Sprint planning and retrospective leading
- One-on-ones with team members
- Metrics reviews and improvement tracking

### Interactions with Other Roles
- **Project Managers**: Collaborate on schedule and risk management
- **Developers**: Coach on agile practices and support blockers
- **Product Managers**: Coordinate on backlog refinement and prioritization
- **Technical Lead**: Support technical decision-making ceremonies

---

## Security Officer

### Role Summary
Security Officers ensure that projects meet security and compliance requirements. They review architectural decisions, oversee security scanning, and lead incident response for security issues.

### Responsibilities
- Review architecture and code for security risks
- Coordinate security scanning in CI/CD pipeline
- Validate compliance with security policies and standards
- Lead triage and response for security incidents
- Provide security guidance and best practices to developers
- Maintain security documentation and incident logs
- Participate in threat modeling and security design reviews

### Goals
- Minimize security vulnerabilities in production
- Ensure compliance with regulatory and organizational standards
- Enable rapid detection and response to security incidents
- Build security awareness across the organization

### Typical Communication
- Security design reviews and threat modeling sessions
- Security scanning reports and vulnerability triage
- Incident response coordination
- Security training and best practices sharing
- Compliance and audit reporting

### Interactions with Other Roles
- **Technical Lead**: Collaborate on security architecture and design
- **QA/Testing Lead**: Coordinate on security test coverage
- **Project Managers**: Escalate security risks and compliance gaps
- **Developers**: Provide guidance on secure coding practices
- **Stakeholder/Sponsor**: Report on security posture and compliance status

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference specific personas when defining responsibilities in project charters and planning documents.
