# OctoAcme — Cross-Functional Collaboration Guide

## Purpose
Provide guidance on effective collaboration between different roles and personas in OctoAcme projects. Clear collaboration patterns reduce miscommunication, clarify responsibilities, and improve project outcomes.

## Core Collaboration Principles
- **Clear ownership**: Each activity or deliverable has a named owner
- **Shared context**: All participants understand the project goal and success metrics
- **Transparent communication**: Status, blockers, and decisions are communicated proactively
- **Psychological safety**: Team members can voice concerns and propose alternatives without fear
- **Mutual accountability**: Roles work together to deliver, not in silos

## Key Collaboration Touchpoints

### Project Initiation
**Participants**: Sponsor, Product Manager, Project Manager, Technical Lead
**Outcome**: Approved Project One-pager and resource plan
**Key Activities**:
- Sponsor and Product Manager align on business need and success metrics
- Project Manager and Technical Lead assess feasibility and resource needs
- Collectively decide go/no-go for planning

### Project Planning
**Participants**: Product Manager, Project Manager, Technical Lead, Developers, QA Lead
**Outcome**: Prioritized backlog, release plan, Definition of Done, risk register
**Key Activities**:
- Product Manager defines acceptance criteria
- Technical Lead and Developers estimate and identify technical risks
- QA Lead defines test strategy and quality gates
- Project Manager creates timeline and identifies dependencies

### Sprint Planning
**Participants**: Developers, Product Manager, QA Lead, Scrum Master, Technical Lead
**Outcome**: Sprint backlog with clear acceptance criteria and test plan
**Key Activities**:
- Product Manager prioritizes backlog items
- Developers ask clarifying questions and estimate effort
- QA Lead reviews acceptance criteria and test approach
- Scrum Master facilitates and manages time

### Daily Execution
**Participants**: Developers, QA Lead, Technical Lead, Project Manager, Scrum Master
**Cadence**: Daily standups (15 min)
**Key Activities**:
- Developers report progress and blockers
- QA Lead communicates test status and quality risks
- Technical Lead addresses technical questions
- Scrum Master removes impediments
- Project Manager escalates blockers as needed

### Code Review & Quality Gates
**Participants**: Developers, QA Lead, Technical Lead, Security Officer
**Outcome**: Merged PRs that meet Definition of Done
**Key Activities**:
- Developers submit PRs with clear description and test coverage
- Technical Lead reviews for architecture and design patterns
- Developers review for code quality and maintainability
- QA Lead validates acceptance criteria and test coverage
- Security Officer reviews for security risks (for sensitive code)
- Minimum one approval required before merge

### Release Planning
**Participants**: Product Manager, Project Manager, Technical Lead, QA Lead, Sponsor, Security Officer
**Outcome**: Release plan, release notes, rollback plan, go/no-go decision
**Key Activities**:
- Product Manager and Project Manager align on release scope and timing
- Technical Lead and QA Lead confirm readiness and risks
- Security Officer validates security scanning completion
- Sponsor approves release decision
- Project Manager coordinates deployment window

### Post-Release
**Participants**: Developers, QA Lead, Technical Lead, Project Manager, Security Officer
**Outcome**: Verified release, documented learnings, hotfix plan (if needed)
**Key Activities**:
- QA Lead runs smoke tests in production
- Technical Lead monitors for technical issues
- Security Officer watches for security incidents
- Project Manager tracks and communicates status
- Team documents any issues and hotfixes

### Retrospective
**Participants**: All project team members
**Cadence**: After each sprint or milestone
**Outcome**: Action items for process improvement
**Key Activities**:
- Scrum Master facilitates discussion of what went well and what to improve
- Team identifies 2–3 high-impact action items
- Project Manager tracks completion of action items
- Team celebrates wins and learnings

## Collaboration Patterns by Role Pair

### Developer ↔ QA Lead
- **When**: Throughout sprint, especially during code review and QA sign-off
- **Focus**: Test design, acceptance criteria validation, defect triage
- **Success**: Clear, actionable defect reports and early quality feedback

### Developer ↔ Technical Lead
- **When**: During design, code review, and technical blockers
- **Focus**: Architecture decisions, design patterns, code quality
- **Success**: Code that meets standards and can be maintained long-term

### Product Manager ↔ Project Manager
- **When**: Weekly syncs, sprint planning, release decisions
- **Focus**: Scope, priority, timeline, stakeholder alignment
- **Success**: Delivery of high-priority items on schedule

### Project Manager ↔ Scrum Master
- **When**: Daily standups, sprint ceremonies, risk management
- **Focus**: Schedule, blockers, process improvements
- **Success**: Predictable, efficient delivery with minimal process friction

### Technical Lead ↔ Security Officer
- **When**: Design reviews, pre-release verification
- **Focus**: Secure architecture, threat modeling, compliance
- **Success**: Secure, compliant solutions that meet standards

### Product Manager ↔ Sponsor
- **When**: Monthly updates, gate reviews, priority decisions
- **Focus**: Business outcomes, strategic alignment, resource needs
- **Success**: Projects deliver measurable business value

## Communication Templates

### Collaboration Request Template
**From**: [Role]
**To**: [Role]
**Need**: [Specific request or decision]
**Context**: [Background and relevant constraints]
**Timeline**: [When is this needed?]
**Acceptance**: [How will we know this is done?]

### Blocker Escalation Template
**Blocker**: [Specific issue]
**Impact**: [What is delayed or at risk?]
**Owner**: [Who is responsible for resolution?]
**Timeline**: [How urgent is this?]
**Proposed**: [Suggested mitigation or solution]

### Handoff Template
**From**: [Role]
**To**: [Role]
**What**: [Deliverable or activity being handed off]
**Status**: [Current state, what's complete, what's pending]
**Context**: [Decisions made, constraints, dependencies]
**Next Steps**: [What the receiving role should do next]

## Resolving Role Conflicts

### Scope vs. Schedule
**Participants**: Product Manager, Project Manager, Sponsor
**Process**: 
1. Identify the constraint (scope too large for timeline)
2. Present options: extend timeline, reduce scope, increase resources
3. Sponsor decides based on business priority
4. Document decision and update plan

### Technical Debt vs. Feature Delivery
**Participants**: Technical Lead, Product Manager, Project Manager
**Process**:
1. Technical Lead quantifies risk and impact of deferring debt
2. Product Manager and Project Manager assess business impact of delay
3. Collectively decide: pay now, pay later, or split the difference
4. Document decision and track technical debt

### Quality vs. Speed
**Participants**: QA Lead, Developers, Product Manager, Project Manager
**Process**:
1. QA Lead flags quality risks and their impact
2. Developers and Product Manager assess if risks are acceptable
3. Collectively decide: invest in quality, accept risk, or extend timeline
4. Document decision and add quality concerns to risk register

## Collaboration Checklist
- [ ] All participants understand the project goal and success metrics
- [ ] Roles and responsibilities are clearly defined and documented
- [ ] Communication cadence and channels are established
- [ ] Escalation paths are clear (when to involve whom)
- [ ] Decision-making authority is clear for each type of decision
- [ ] Retrospectives are scheduled and documented
- [ ] Process improvements from retros are tracked and completed
