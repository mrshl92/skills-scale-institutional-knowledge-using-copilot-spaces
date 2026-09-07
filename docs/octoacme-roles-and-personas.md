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
- **Collaborate with Product Managers** on acceptance criteria and feature specifications
- **Work with Project Managers** on scheduling and dependency management
- **Partner with QA/Testing Lead** on test strategies and DoD validation
- **Consult with Technical Lead/Architect** on design decisions and technical risk mitigation
- **Engage with Security Officer** on security requirements and testing

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
- **Align with Project Managers** on timeline and resource planning
- **Work with Developers** on feasibility and technical trade-offs
- **Coordinate with Sponsors/Stakeholders** on business priorities and approvals
- **Report to Product Leads** on progress and roadmap execution
- **Consult with QA/Testing Lead** on quality expectations and test strategy

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
- **Coordinate with Developers** on capacity planning and delivery tracking
- **Align with Product Managers** on scope and priority changes
- **Escalate to Sponsors/Stakeholders** on critical blockers and decisions
- **Track risks with Technical Lead/Architect** and Security Officer
- **Report quality metrics from QA/Testing Lead** in status updates

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and acceptance validation. They ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define comprehensive test plans covering unit, integration, and end-to-end testing
- Execute and coordinate manual and automated testing activities
- Validate Definition of Done (DoD) compliance for each deliverable
- Identify quality risks and propose testing mitigations
- Coordinate with developers on test coverage and test-driven development practices
- Report quality metrics and test results in sprint reviews and release gates

### Goals
- Ensure features meet acceptance criteria before release
- Minimize production defects and regression issues
- Maintain high test coverage and reliable automated test suites
- Enable fast, confident deployments through comprehensive testing

### Typical Communication
- Test planning sessions during sprint planning
- Test reports and quality dashboards
- Release checklists and pre-deployment verification
- Sprint review and demo participation
- Risk register updates on quality-related risks

### Interactions with Other Roles
- **Work with Developers** on test strategy, test-driven development, and test coverage
- **Collaborate with Product Managers** on acceptance criteria clarity and edge cases
- **Consult with Technical Lead/Architect** on test approach for complex features
- **Coordinate with Project Managers** on testing timeline and resource needs
- **Engage with Security Officer** on security testing and vulnerability scanning
- **Support Release & Deployment** with smoke tests and post-deployment verification

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide technical decisions, design approaches, and architectural risk mitigation. They provide technical mentorship and ensure solutions are scalable, maintainable, and secure.

### Responsibilities
- Review technical design proposals and provide architectural guidance
- Identify architectural risks, dependencies, and integration points
- Mentor developers on coding standards and best practices
- Assess technical feasibility and complexity of proposed features
- Validate testability, security, and observability considerations in designs
- Participate in technology selection and technical debt management discussions
- Help identify performance bottlenecks and optimization opportunities

### Goals
- Reduce technical risk and prevent architectural debt accumulation
- Maintain code quality, maintainability, and long-term scalability
- Enable rapid, reliable feature delivery through sound technical decisions
- Foster a culture of technical excellence and continuous learning

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback on complex changes
- Planning meetings to assess technical feasibility
- Risk register updates on technical risks
- Technical documentation and design decision records

### Interactions with Other Roles
- **Guide Developers** on technical approach, design patterns, and best practices
- **Advise Product Managers** on technical trade-offs and feasibility constraints
- **Support Project Managers** in identifying technical dependencies and risks
- **Collaborate with QA/Testing Lead** on test strategy for complex features
- **Work with Security Officer** on security architecture and threat assessment
- **Support Sponsors/Stakeholders** by explaining technical implications of business decisions

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide business context, strategic alignment, and decision authority. They ensure projects deliver business value and resolve high-level escalations.

### Responsibilities
- Define business case, success metrics, and strategic alignment
- Approve project scope, timeline, and resource allocation
- Resolve escalations and remove high-level blockers
- Communicate project progress and outcomes to leadership
- Approve scope changes and trade-offs that impact business objectives
- Ensure alignment with organizational priorities and strategic initiatives

### Goals
- Ensure business value delivery aligned with organizational strategy
- Maintain stakeholder alignment and executive visibility
- Resolve blockers and provide executive support when needed
- Drive project success through clear authority and decision-making

### Typical Communication
- Milestone reviews and gate approvals
- Escalation path for critical decisions
- Monthly or quarterly stakeholder updates
- Project charter and business case discussions
- Post-project retrospective and impact assessment

### Interactions with Other Roles
- **Receive status from Project Managers** on schedule, risks, and blockers
- **Approve decisions from Product Managers** on scope and priority changes
- **Resolve escalations from Developers and Technical Lead/Architect** on resource or technical decisions
- **Review quality status from QA/Testing Lead** before production releases
- **Coordinate with Security Officer** on compliance and security incidents
- **Engage with Support/Operations** on production readiness and incident response

---

## Security Officer / Champion

### Role Summary
Security Officers integrate security requirements, manage security risks, and ensure compliance. They work across the team to embed security into the project lifecycle.

### Responsibilities
- Define security requirements and compliance obligations for projects
- Conduct threat assessment and security architecture reviews
- Validate security testing and vulnerability scanning
- Review designs for security risks and propose mitigations
- Coordinate incident response and post-incident reviews
- Track security metrics and compliance status in the risk register
- Educate team members on security best practices

### Goals
- Minimize security risk and compliance violations
- Ensure rapid incident response and remediation
- Embed security-by-design across project lifecycle
- Maintain compliance with organizational and regulatory requirements

### Typical Communication
- Security requirements in planning and design reviews
- Security scanning results and vulnerability reports
- Risk register updates on security risks
- Incident coordination and communication
- Security training and awareness updates

### Interactions with Other Roles
- **Advise Developers** on secure coding practices and dependency vulnerabilities
- **Collaborate with Product Managers** on security feature prioritization
- **Work with Technical Lead/Architect** on security architecture and threat modeling
- **Coordinate with QA/Testing Lead** on security testing and penetration testing
- **Support Project Managers** with security risk escalation and tracking
- **Report to Sponsors/Stakeholders** on security posture and compliance status
- **Partner with Support/Operations** on production incident response and monitoring

---

## Support / Operations

### Role Summary
Support and Operations teams manage production monitoring, issue triage, and customer communication. They ensure systems run reliably and respond quickly to production issues.

### Responsibilities
- Monitor production systems and alert on anomalies
- Triage and escalate production incidents
- Coordinate incident response and communication with stakeholders
- Manage deployment and rollback procedures
- Capture production metrics and observability data
- Support customer issue investigation and troubleshooting
- Provide feedback on operational aspects to developers

### Goals
- Ensure high system availability and performance
- Rapidly detect and respond to production issues
- Provide excellent customer support during incidents
- Capture operational insights to improve reliability

### Typical Communication
- Production monitoring dashboards and alerts
- Incident reports and post-incident reviews
- Release and deployment coordination
- Customer issue tracking and updates
- Operational feedback to development team

### Interactions with Other Roles
- **Work with Developers** on troubleshooting and root cause analysis
- **Coordinate with Project Managers** on deployment schedules and incidents
- **Report production metrics to Product Managers** for success measurement
- **Collaborate with QA/Testing Lead** on smoke tests and post-deployment verification
- **Escalate to Technical Lead/Architect** on complex technical issues
- **Alert Security Officer** on security-related incidents
- **Update Sponsors/Stakeholders** on major incidents and impact

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Interactions with Other Roles" sections to understand cross-functional dependencies and communication flows.
