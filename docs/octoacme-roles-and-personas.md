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

## QA/Testing Lead

### Role Summary
QA and Testing leads ensure quality standards are met, validate acceptance criteria, and coordinate testing efforts across sprints and releases. They own the quality strategy and risk assessment for each project.

### Responsibilities
- Define and maintain test plans and acceptance criteria
- Coordinate unit, integration, and end-to-end testing efforts
- Conduct manual QA when needed and validate feature acceptance
- Identify quality risks and propose mitigation strategies
- Manage test automation and CI integration
- Report quality metrics and bottlenecks to the team

### Goals
- Ensure all deliverables meet acceptance criteria before release
- Reduce defects reaching production
- Build confidence in release readiness
- Maintain quality metrics and continuous improvement

### Typical Communication
- Sprint planning and QA estimation sessions
- Test result summaries and blocker escalation
- Quality metrics in weekly syncs
- Release readiness checklists and sign-offs

### Interaction with Existing Roles
- **Developers**: Collaborate on test design, automation approaches, and defect triage
- **Product Managers**: Validate acceptance criteria and scope quality trade-offs
- **Project Managers**: Report quality metrics and identify schedule impacts
- **Technical Lead**: Review test strategy and automation architecture

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide technical strategy, design decisions, and integration points. They balance technical feasibility with business requirements and mentor the development team.

### Responsibilities
- Lead technical design discussions and architecture reviews
- Identify technical risks and propose solutions
- Guide code quality standards and best practices
- Mentor developers and review technical decisions
- Coordinate cross-system integration and dependencies
- Ensure scalability and maintainability of solutions
- Document architectural decisions and trade-offs

### Goals
- Deliver technically sound solutions that scale and perform
- Reduce technical debt and maintenance burden
- Enable team growth and knowledge sharing
- Minimize integration risks and architectural rework

### Typical Communication
- Design review meetings and architecture discussions
- Technical risk assessments during planning
- Architecture Decision Records (ADRs) and design documentation
- Code review feedback and technical mentoring
- Integration planning with cross-team dependencies

### Interaction with Existing Roles
- **Developers**: Provide technical guidance, design reviews, and mentorship
- **Project Managers**: Assess technical feasibility and identify risks early
- **Product Managers**: Advise on technical trade-offs and feature complexity
- **QA/Testing Lead**: Review test strategy and automation approaches

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide executive alignment, approve project charters, and ensure business priorities are met. They escalate blockers and secure resources for project success.

### Responsibilities
- Approve project charters and major scope changes
- Ensure alignment with business strategy and priorities
- Escalate and resolve blockers at the executive level
- Provide budget and resource approval
- Monitor business metrics and ROI
- Communicate project status to leadership and boards as needed
- Champion the project within the organization

### Goals
- Ensure projects deliver business value and strategic alignment
- Remove organizational blockers
- Enable team success through resource allocation
- Secure stakeholder buy-in and executive support

### Typical Communication
- Monthly stakeholder updates and executive briefings
- Project charter approval and review gates
- Escalation path for critical blockers
- Post-release business impact reviews
- Budget and resource allocation decisions

### Interaction with Existing Roles
- **Project Managers**: Escalation point for blockers and resource constraints
- **Product Managers**: Align on business priorities and success metrics
- **Developers & Technical Lead**: Remove organizational barriers to delivery
- **QA/Testing Lead**: Approve release decisions based on quality metrics

---

## Security / Compliance Officer

### Role Summary
Security and Compliance roles ensure products meet regulatory, security, and privacy standards. They guide secure development practices and incident response.

### Responsibilities
- Define security requirements and compliance standards
- Review and approve security designs and threat models
- Coordinate security scanning and vulnerability assessments
- Manage security incident response and triage
- Ensure compliance with relevant regulations (GDPR, SOC2, etc.)
- Conduct security training and awareness
- Document security decisions and audit trails

### Goals
- Prevent security breaches and compliance violations
- Embed security into the development lifecycle
- Enable rapid, safe incident response
- Maintain regulatory compliance and audit readiness

### Typical Communication
- Security design review meetings
- Security scanning results and remediation plans
- Incident triage and post-incident reviews
- Compliance audit reports and risk assessments
- Security requirements in project planning

### Interaction with Existing Roles
- **Technical Lead**: Review security architecture and threat models
- **Developers**: Provide secure coding guidance and security requirements
- **Project Managers**: Assess security risks and compliance requirements
- **QA/Testing Lead**: Coordinate security testing and vulnerability validation

---

## Integration with Project Lifecycle

The following sections describe how these personas interact across the OctoAcme project lifecycle:

### Initiation
- **Technical Lead** and **Security Officer** review One-pager for technical feasibility and security/compliance risks
- **Sponsor** approves charter and business alignment
- **QA/Testing Lead** contributes quality strategy input

### Planning
- **QA Lead** and **Technical Lead** contribute estimates and risk identification
- **Security Officer** defines security and compliance requirements
- **Sponsor** approves resource allocation and timeline
- **Developers** collaborate on estimation and feasibility assessment

### Execution
- **QA Lead** defines acceptance criteria and test plans
- **Technical Lead** leads design reviews and resolves technical decisions
- **Security Officer** reviews security changes and approves security implementations
- **Project Manager** coordinates across all roles and tracks progress
- **Developers** implement features and collaborate with all roles

### Release
- **QA Lead** owns release readiness and quality validation
- **Security Officer** approves security scanning results and compliance checks
- **Technical Lead** validates architectural soundness
- **Sponsor** approves go-live decision
- **Project Manager** coordinates release activities

### Close & Retrospective
- **Technical Lead** captures technical learnings and architectural insights
- **QA Lead** reports quality metrics and testing effectiveness
- **Project Manager** facilitates retrospective and documents action items
- **All roles** contribute to continuous improvement discussion

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand the interactions between personas to anticipate communication needs and potential areas for alignment or conflict.
