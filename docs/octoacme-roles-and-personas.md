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

## UX Designers

### Role Summary
UX Designers create intuitive, user-centered product experiences. They conduct user research, design interfaces, and validate usability throughout the product lifecycle. They ensure features are discoverable and meet end-user needs.

### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Create wireframes, prototypes, and design specifications
- Collaborate with Product Managers to refine feature requirements and acceptance criteria
- Work with Developers to ensure design feasibility and fidelity during implementation
- Gather and synthesize user feedback to drive iterative improvements
- Maintain design systems and patterns for consistency

### Goals
- Deliver delightful, accessible user experiences
- Reduce user friction and support burden through better design
- Balance user needs with business constraints and technical feasibility
- Establish design as a core part of feature delivery

### Interactions with Other Roles
- **Product Managers**: Align on user research findings, feature prioritization, and success metrics
- **Developers**: Provide clear design specs and collaborate on implementation details
- **QA/Testing**: Coordinate on usability testing and acceptance criteria validation
- **Customer Support Lead**: Gather feedback on user pain points and support issues

### Typical Communication
- Design reviews and feedback sessions with Product and Engineering
- Usability testing reports and user research summaries
- Design documentation and specifications in PRs and feature briefs
- Weekly design syncs with Product and core stakeholders

---

## DevOps Engineers

### Role Summary
DevOps Engineers own the infrastructure, deployment pipelines, and operational reliability of the product. They enable teams to deploy confidently and scale reliably while maintaining security and performance standards.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Provision and manage cloud infrastructure and environments (dev, staging, production)
- Implement monitoring, logging, and alerting systems
- Manage deployment processes and automate release workflows
- Troubleshoot infrastructure and deployment issues
- Plan and execute disaster recovery, backup, and rollback strategies
- Ensure security best practices in infrastructure and access controls

### Goals
- Enable rapid, reliable, and safe deployments
- Maintain high system availability and performance
- Reduce deployment risk and recovery time
- Automate operational toil to free teams for innovation

### Interactions with Other Roles
- **Developers**: Support tooling needs, environment access, and deployment automation; collaborate on observability and debugging
- **Project Managers**: Coordinate deployment windows, rollback plans, and release readiness
- **QA/Testing**: Provide staging environments and support smoke testing before production release
- **Security**: Implement infrastructure security controls and support incident response

### Typical Communication
- Infrastructure and deployment documentation
- CI/CD pipeline configuration and status reports
- Release coordination and deployment runbooks
- On-call escalations and incident triage
- Weekly infrastructure and reliability reviews

---

## Business Analysts

### Role Summary
Business Analysts bridge stakeholder intent and product delivery. They conduct requirements discovery, document business processes, and define measurement strategies to ensure projects deliver measurable business value.

### Responsibilities
- Gather and document business requirements from stakeholders
- Analyze current processes and identify improvement opportunities
- Create detailed requirement specifications and acceptance criteria
- Define key metrics and measurement strategies for success
- Conduct stakeholder interviews and workshops
- Document assumptions, dependencies, and risk factors
- Support validation of solutions against business objectives

### Goals
- Ensure clear alignment between business needs and technical solutions
- Minimize misunderstandings and scope creep through thorough requirements
- Enable data-driven decision-making through well-defined metrics
- Reduce delivery rework by clarifying ambiguous requirements upfront

### Interactions with Other Roles
- **Product Managers**: Partner on requirement definition, prioritization, and success metric validation
- **Project Managers**: Provide detailed requirements and support risk/dependency identification
- **Developers**: Clarify ambiguous requirements and resolve technical feasibility questions
- **Stakeholders**: Conduct discovery, validate requirements, and report on business value delivery

### Typical Communication
- Requirements documents and specification reviews
- Stakeholder workshop notes and discovery summaries
- Business case and impact analysis documents
- Weekly alignment with Product and Project leads
- Metrics dashboards and post-release impact reports

---

## Customer Support Leads

### Role Summary
Customer Support Leads represent end-user needs and operational readiness in product delivery. They ensure products are designed for supportability, provide clear handoff documentation, and coordinate launch readiness from a customer success perspective.

### Responsibilities
- Identify support-related requirements and edge cases early in the process
- Review feature documentation and create support materials
- Conduct support readiness reviews before launch
- Escalate customer-impacting risks and support concerns
- Coordinate with the support team on knowledge transfer
- Monitor post-launch support metrics and customer feedback
- Recommend improvements based on support volume and customer sentiment

### Goals
- Reduce post-launch support burden through better design and documentation
- Ensure customer success and satisfaction with new features
- Identify product improvements driven by customer feedback
- Maintain operational stability and support team capacity

### Interactions with Other Roles
- **Product Managers**: Provide customer feedback and support-related requirements
- **UX Designers**: Review user experience for supportability and clarity
- **Developers**: Clarify support edge cases and ensure defensive code practices
- **Project Managers**: Advise on launch readiness, support capacity, and customer communication plans
- **QA/Testing**: Coordinate on real-world scenario testing and edge case coverage

### Typical Communication
- Support readiness reviews and launch checklists
- Customer feedback summaries and support metrics
- Feature documentation reviews and training materials
- Weekly syncs with Product and Project teams
- Post-launch retrospectives on support volume and customer issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional collaboration is essential; reference the "Interactions with Other Roles" section when planning handoffs and communication touchpoints.
