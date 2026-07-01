# OctoAcme — Cross-Functional Collaboration

## Purpose
Define how cross-functional roles collaborate effectively, clarify decision-making authority, and establish communication patterns to reduce ambiguity and accelerate project delivery.

## Cross-Functional Collaboration Model

### Core Principle
Success requires clear role definition, explicit communication, and shared ownership of outcomes. Each persona brings unique expertise; effective collaboration means knowing when to consult, when to escalate, and when to decide.

## Decision-Making Framework

### Types of Decisions

#### 1. **Business & Strategic Decisions**
- **Owner**: Stakeholder/Sponsor, Product Manager
- **Consulted**: Project Manager
- **Informed**: Developers, QA Lead, UX/Design Lead
- **Examples**: Priority trade-offs, go/no-go release decisions, scope changes

#### 2. **Product & User Experience Decisions**
- **Owner**: Product Manager, UX/Design Lead
- **Consulted**: Developer, QA Lead, Technical Lead
- **Informed**: Project Manager, Stakeholder/Sponsor
- **Examples**: Feature scope, acceptance criteria, user workflows, accessibility requirements

#### 3. **Technical & Architecture Decisions**
- **Owner**: Technical Lead, Developer team
- **Consulted**: Product Manager, QA Lead
- **Informed**: Project Manager, Stakeholder/Sponsor
- **Examples**: Architecture design, technology choices, performance trade-offs, refactoring decisions

#### 4. **Quality & Testing Decisions**
- **Owner**: QA/Testing Lead
- **Consulted**: Developer, Product Manager, UX/Design Lead
- **Informed**: Project Manager, Stakeholder/Sponsor
- **Examples**: Test strategy, acceptance criteria validation, release readiness

#### 5. **Project & Execution Decisions**
- **Owner**: Project Manager
- **Consulted**: Product Manager, Technical Lead, QA Lead
- **Informed**: Developers, Stakeholder/Sponsor
- **Examples**: Schedule adjustments, resource allocation, risk mitigation, milestone planning

## Key Collaboration Points in Project Lifecycle

### Initiation
**Primary Contributors**: Stakeholder/Sponsor, Product Manager, Project Manager
- Define business need and success metrics
- Identify team composition (which roles needed?)
- Set initial timeline and resource requirements
- **Communication**: Kickoff meeting with all stakeholders

### Planning
**Primary Contributors**: Product Manager, Technical Lead, Project Manager, QA Lead
- Break work into shippable increments
- Define acceptance criteria (Product Manager + UX/Design Lead)
- Estimate technical effort (Developers + Technical Lead)
- Identify test strategy (QA Lead + Developers)
- **Communication**: Planning sessions, written acceptance criteria, risk register

### Execution
**Primary Contributors**: Developers, QA Lead, UX/Design Lead, Technical Lead
- Daily standups with full team participation
- Code reviews (peer-to-peer + Technical Lead for architecture decisions)
- Design reviews (UX/Design Lead with Developers)
- Test plan reviews (QA Lead with Developers)
- **Communication**: Standups, PR reviews, Slack updates, blockers logged to PM

### Quality & Testing
**Primary Contributors**: QA Lead, Developers, UX/Design Lead, Product Manager
- Execute test plans (QA Lead, with support from Developers for technical testing)
- Validate usability (UX/Design Lead, with QA support)
- Verify acceptance criteria met (Product Manager, QA Lead)
- **Communication**: Test reports, defect tracking, readiness assessments

### Release & Deployment
**Primary Contributors**: Project Manager, Technical Lead, QA Lead, Developers
- Pre-deployment verification (QA Lead, Technical Lead)
- Execute deployment (Developers, Technical Lead)
- Post-deployment monitoring (Technical Lead, Developers)
- **Communication**: Release notes, deployment checklists, incident response readiness

### Retrospective
**Primary Contributors**: Project Manager, all roles
- Capture learnings and improvement opportunities
- Identify action items and owners
- Celebrate wins and recognize contributions
- **Communication**: Anonymous feedback board, facilitated discussion, action item tracking

## Communication Cadence & Ownership

| Cadence | Meeting | Owner | Attendees | Purpose |
|---------|---------|-------|-----------|----------|
| Daily | Standup | Project Manager | All | Progress, blockers, dependencies |
| Weekly | PM/PdM Sync | Project Manager | PM, Product Manager | Status, risks, escalations |
| Weekly | Technical Sync | Technical Lead | Technical Lead, Developers, QA | Architecture, design, technical risks |
| Sprint/Milestone | Design Review | UX/Design Lead | UX/Design Lead, Developers, PM, QA | Design quality, usability, accessibility |
| Sprint/Milestone | Quality Review | QA Lead | QA Lead, Developers, Product Manager | Test coverage, defect trends, readiness |
| Sprint/Milestone | Release Planning | Project Manager | All | Timeline, dependencies, go/no-go criteria |
| Monthly | Stakeholder Update | Project Manager | Stakeholder/Sponsor, PM, PdM | Progress, metrics, business impact |
| Sprint/Milestone | Retrospective | Project Manager | All | Learnings, action items, improvements |

## Escalation & Conflict Resolution

### Escalation Path
1. **Level 1 (Team)**: Discuss in daily standup or sync; resolve among Developers, QA Lead, UX/Design Lead, Technical Lead
2. **Level 2 (Leadership)**: Escalate to Project Manager and Product Manager; may involve Stakeholder/Sponsor for strategic decisions
3. **Level 3 (Executive)**: If business impact is high, escalate to Stakeholder/Sponsor for executive decision

### Common Conflicts & Resolution

#### Scope vs. Timeline vs. Quality Trade-offs
- **Decision Owner**: Stakeholder/Sponsor (with Product Manager and Project Manager advice)
- **Resolution**: Use pre-defined trade-off framework; document decision and rationale

#### Technical Feasibility vs. Business Timeline
- **Decision Owner**: Product Manager + Technical Lead (escalate to Stakeholder/Sponsor if needed)
- **Resolution**: Explore alternatives, adjust scope, or timeline; document trade-offs

#### Testing Coverage vs. Release Pressure
- **Decision Owner**: QA Lead + Product Manager (Project Manager facilitates)
- **Resolution**: Risk-based testing strategy; known issues documented; mitigation plan in place

#### Design Excellence vs. Delivery Schedule
- **Decision Owner**: UX/Design Lead + Product Manager + Technical Lead
- **Resolution**: MVP design + phased improvements; user research to validate trade-offs

## Collaboration Checklist

### Before Kickoff
- [ ] All roles identified and resourced
- [ ] Decision-making authority clarified
- [ ] Communication cadence agreed
- [ ] Escalation paths documented

### During Planning
- [ ] Product Manager + UX/Design Lead define acceptance criteria
- [ ] Technical Lead + Developers estimate effort and identify technical risks
- [ ] QA Lead defines test strategy
- [ ] Project Manager aligns all inputs into project plan
- [ ] Stakeholder/Sponsor approves plan and resource allocation

### During Execution
- [ ] Daily standups include all roles (or representatives)
- [ ] Blockers surfaced immediately and escalated as needed
- [ ] Design reviews completed before development starts
- [ ] Code reviews include peer and Technical Lead feedback
- [ ] Test plans reviewed before QA execution
- [ ] Technical Lead monitors architecture decisions and risks

### Before Release
- [ ] QA Lead sign-off on testing completion and known issues
- [ ] Product Manager validates acceptance criteria met
- [ ] Technical Lead confirms deployment readiness
- [ ] Project Manager coordinates release communication
- [ ] Stakeholder/Sponsor approves release

### After Release
- [ ] Post-deployment verification executed
- [ ] Incident response team on standby
- [ ] Retrospective scheduled and facilitated
- [ ] Action items captured and tracked

## Tips for Effective Cross-Functional Collaboration

1. **Be Explicit About Roles**: Don't assume; clearly state who decides, who advises, and who's informed.
2. **Clarify Decision Authority**: Avoid delays by knowing upfront who has final say on different decisions.
3. **Document Trade-offs**: When prioritizing, explicitly document what was chosen and what was deferred.
4. **Over-Communicate Early**: Invest in clear, frequent communication during planning to reduce surprises during execution.
5. **Celebrate Wins Together**: Recognize contributions from all roles; acknowledge that success is a team effort.
6. **Blameless Retrospectives**: Focus on learnings, not blame; create psychological safety for honest feedback.
7. **Respect Expertise**: Trust the expertise of each role; collaborate rather than override.
8. **Use Shared Artifacts**: Single source of truth (project board, docs, risk register) reduces confusion.
9. **Build Relationships**: Invest time in getting to know teammates; strong relationships enable better collaboration.
10. **Iterate on Process**: Use retrospectives to improve collaboration patterns; adjust cadence and formats as needed.
