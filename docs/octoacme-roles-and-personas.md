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

## Scrum Master

### Role Summary
Scrum Masters facilitate Agile processes, remove impediments, and ensure the team follows agreed-upon practices. They coach the team on self-organization and continuous improvement.

### Responsibilities
- Facilitate Scrum ceremonies (sprint planning, daily standups, retrospectives, reviews)
- Remove blockers and impediments to team progress
- Coach the team on Agile principles and practices
- Shield the team from external distractions and scope changes
- Track team velocity and support predictable delivery
- Foster a culture of continuous improvement and psychological safety

### Goals
- Maximize team productivity and flow
- Ensure consistent application of Agile practices
- Build a self-organizing, high-performing team
- Minimize waste and optimize delivery processes

### Typical Communication
- Daily standups and sprint ceremonies
- Coordination with Project Managers on timelines and risks
- Regular check-ins with team members on blockers
- Metrics sharing (velocity, burndown, cycle time)

### Interaction Points
- **Project Managers**: Align on timelines, dependencies, and escalations
- **Developers**: Remove blockers, facilitate collaboration
- **Product Managers**: Ensure backlog is refined and prioritized
- **DevOps Engineers**: Coordinate on delivery pipelines and automation

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions. They gather requirements, analyze processes, and ensure solutions meet stakeholder expectations and business objectives.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Translate business needs into functional specifications
- Create process flows, user stories, and acceptance criteria
- Validate that delivered solutions meet business requirements
- Facilitate workshops and requirement gathering sessions
- Maintain traceability between requirements and deliverables

### Goals
- Ensure solutions address genuine business needs
- Minimize rework through clear, validated requirements
- Maintain alignment between business and technical teams
- Support data-driven decision making

### Typical Communication
- Stakeholder interviews and workshops
- Requirements documents and user stories
- Weekly syncs with Product and Project Managers
- Solution validation sessions

### Interaction Points
- **Product Managers**: Collaborate on feature definition and prioritization
- **Developers**: Clarify requirements and acceptance criteria
- **UX Designers**: Ensure user needs align with business goals
- **Stakeholders**: Gather and validate requirements

---

## UX Designer

### Role Summary
UX Designers create intuitive, accessible user experiences. They conduct user research, design interfaces, and validate solutions through usability testing and feedback.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Ensure accessibility and usability standards are met
- Collaborate with developers on implementation feasibility
- Validate designs with real users and stakeholders
- Maintain design systems and component libraries

### Goals
- Deliver delightful, intuitive user experiences
- Ensure accessibility and inclusivity in all designs
- Reduce user friction and support task completion
- Balance user needs with business and technical constraints

### Typical Communication
- Design reviews and critique sessions
- User research findings and personas
- Prototypes and interactive mockups
- Collaboration tools (Figma, Sketch) with annotations

### Interaction Points
- **Product Managers**: Align on user needs and feature priorities
- **Developers**: Collaborate on implementation and feasibility
- **Business Analysts**: Validate user flows align with requirements
- **QA/Testing**: Partner on usability and accessibility testing

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, CI/CD pipelines, and automation that enable reliable, efficient software delivery. They focus on deployment, monitoring, and system reliability.

### Responsibilities
- Design and maintain CI/CD pipelines for automated builds and deployments
- Manage infrastructure as code and cloud resources
- Implement monitoring, logging, and alerting systems
- Ensure security scanning and compliance in pipelines
- Optimize deployment processes for speed and reliability
- Support incident response and system troubleshooting

### Goals
- Enable fast, safe, repeatable deployments
- Maximize system uptime and reliability
- Automate repetitive operational tasks
- Provide visibility into system health and performance

### Typical Communication
- Infrastructure changes and deployment schedules
- Incident reports and postmortems
- Pipeline status and automation updates
- Capacity planning and performance metrics

### Interaction Points
- **Developers**: Provide tooling and pipeline support
- **Release Managers**: Coordinate deployment schedules and rollback plans
- **Project Managers**: Report on deployment risks and infrastructure dependencies
- **Scrum Masters**: Remove tooling and infrastructure blockers

---

## Release Manager

### Role Summary
Release Managers orchestrate the release process, coordinating across teams to ensure safe, well-communicated deployments. They own the release schedule and rollback procedures.

### Responsibilities
- Plan and coordinate release schedules across teams
- Create and maintain release checklists and runbooks
- Coordinate release communication to stakeholders
- Manage release gates and approval processes
- Ensure rollback plans are tested and ready
- Track release metrics and post-release validation

### Goals
- Deliver reliable, low-risk releases on schedule
- Minimize production incidents and customer impact
- Ensure clear communication and coordination across teams
- Build confidence in the release process

### Typical Communication
- Release calendar and schedules
- Go/no-go decisions and release readiness reviews
- Release notes and stakeholder announcements
- Post-release reports and metrics

### Interaction Points
- **DevOps Engineers**: Coordinate deployment execution and monitoring
- **Project Managers**: Align release timelines with project milestones
- **Support Lead**: Ensure support readiness for releases
- **Developers**: Validate feature completeness and testing

---

## Support Lead

### Role Summary
Support Leads ensure the support team is prepared to assist customers with new features and issues. They gather customer feedback, triage escalations, and advocate for fixes and improvements.

### Responsibilities
- Prepare support team for new feature releases and changes
- Triage customer-reported issues and escalate to engineering
- Document known issues and workarounds
- Gather and communicate customer feedback to product and engineering
- Monitor support metrics (ticket volume, resolution time, satisfaction)
- Maintain support knowledge base and runbooks

### Goals
- Ensure excellent customer support experience
- Minimize time to resolution for customer issues
- Provide actionable customer feedback to improve the product
- Build support team readiness and confidence

### Typical Communication
- Support readiness sessions before releases
- Escalation reports and customer impact summaries
- Weekly metrics and trend analysis
- Customer feedback and feature requests

### Interaction Points
- **Release Managers**: Coordinate on release timing and support readiness
- **Product Managers**: Share customer feedback and pain points
- **Developers**: Escalate bugs and request fixes
- **UX Designers**: Provide usability feedback from customers

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

