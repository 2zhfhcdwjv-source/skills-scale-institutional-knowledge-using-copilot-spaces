# OctoAcme Additional Personas

This document extends the core personas defined in [Roles & Personas](./octoacme-roles-and-personas.md) by describing additional roles involved in project and program delivery at OctoAcme. It captures responsibilities, goals, and collaboration points to improve accountability, communication, and delivery consistency.

---

## Engineering Manager

### Role Summary
Engineering Managers lead and grow engineering teams, ensuring individuals have clarity on their work, support for their development, and the resources needed to deliver effectively. They bridge people management and delivery execution.

### Responsibilities
- Hire, onboard, and develop engineers
- Set team expectations, run 1:1s, and manage performance
- Partner with Project and Product Managers on capacity, prioritization, and escalations
- Identify and resolve systemic blockers (tooling, process, staffing)
- Champion engineering quality standards and technical excellence

### Goals
- Build a high-performing, engaged engineering team
- Ensure team capacity aligns with project commitments
- Reduce attrition and increase engineering satisfaction

### Typical Communication
- Weekly 1:1s with direct reports
- Bi-weekly syncs with Project Managers and Product Managers
- Quarterly performance and growth conversations

### Interaction with Existing Roles
- **Developers**: Primary people manager; provides growth feedback, removes organizational blockers, and aligns workload across team members.
- **Product Managers**: Collaborates on roadmap feasibility and team capacity; escalates trade-offs between feature delivery and tech-debt reduction.
- **Project Managers**: Coordinates on resourcing, dependencies between teams, and escalation paths when delivery risks are people-related.

---

## Tech Lead

### Role Summary
Tech Leads provide technical direction for a feature or workstream, guiding design decisions and ensuring code quality. They operate as a senior individual contributor with shared leadership responsibility.

### Responsibilities
- Define technical approach and architecture for assigned work
- Lead design reviews and ensure implementation aligns with standards
- Assist in breaking down epics into actionable technical tasks
- Identify and communicate technical risks early
- Mentor developers and conduct thorough code reviews

### Goals
- Deliver technically sound, maintainable solutions
- Reduce rework by aligning on design before implementation begins
- Increase engineering team's shared understanding of the codebase

### Typical Communication
- Design documents and architecture decision records (ADRs)
- Code review comments and PR feedback
- Technical risk updates in sprint reviews and planning sessions

### Interaction with Existing Roles
- **Developers**: Direct collaborator; pairs on complex problems, reviews PRs, and unblocks technical questions.
- **Product Managers**: Provides technical feasibility assessments; flags scope implications of feature requests.
- **Project Managers**: Communicates technical risks and dependencies; supports effort estimation and milestone planning.

---

## UX Designer / Researcher

### Role Summary
UX Designers and Researchers ensure that product features are usable, accessible, and aligned with user needs. They translate user insights into interaction designs and validate solutions before and after delivery.

### Responsibilities
- Conduct user research (interviews, surveys, usability testing)
- Create wireframes, prototypes, and design specifications
- Define and document interaction patterns and accessibility standards
- Collaborate with developers on implementation fidelity
- Synthesize research findings into actionable recommendations

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user error and support burden through proactive design
- Ground product decisions in validated user research

### Typical Communication
- Design reviews with Product and Engineering teams
- Research reports and insight summaries
- Usability test sessions and feedback loops with stakeholders

### Interaction with Existing Roles
- **Developers**: Provides design specs, assets, and interaction guidance; partners on implementation review to ensure design fidelity.
- **Product Managers**: Partners on problem framing and user validation; feeds research findings into backlog prioritization.
- **Project Managers**: Flags design dependencies or research timelines that may affect delivery schedules.

---

## Scrum Master / Delivery Lead

### Role Summary
Scrum Masters and Delivery Leads facilitate agile ceremonies, remove team blockers, and coach teams on continuous improvement practices. They protect the team's ability to deliver sustainably.

### Responsibilities
- Facilitate standups, sprint planning, reviews, and retrospectives
- Track and surface blockers; escalate as needed
- Monitor team velocity and delivery health metrics
- Coach teams on agile principles and process improvement
- Maintain sprint boards, burndown charts, and delivery dashboards

### Goals
- Sustain a predictable, healthy delivery cadence
- Reduce impediments to team flow and focus
- Embed a culture of reflection and continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective action item tracking
- Delivery health summaries to stakeholders and management

### Interaction with Existing Roles
- **Developers**: Acts as a shield from interruptions; facilitates team ceremonies and coaches on agile practices.
- **Product Managers**: Collaborates on backlog refinement and sprint goal alignment; ensures user stories meet the Definition of Ready.
- **Project Managers**: Shares sprint-level delivery data to inform project-level planning; escalates persistent blockers that span sprints.

---

## Security / Compliance Engineer

### Role Summary
Security and Compliance Engineers identify, assess, and mitigate security risks across the software delivery lifecycle. They embed secure practices into development workflows and ensure regulatory compliance.

### Responsibilities
- Conduct threat modeling and security reviews at design time
- Define and enforce secure coding standards and review checklists
- Run vulnerability assessments and penetration tests
- Ensure compliance with relevant frameworks (e.g., SOC 2, GDPR, ISO 27001)
- Respond to and coordinate remediation of security incidents

### Goals
- Prevent security vulnerabilities from reaching production
- Maintain compliance posture with minimal disruption to delivery
- Build a security-first culture across engineering

### Typical Communication
- Security review sign-off during feature planning and release gates
- Vulnerability reports and remediation tracking
- Compliance status updates in stakeholder and leadership reviews

### Interaction with Existing Roles
- **Developers**: Provides secure coding guidance, reviews PRs for security concerns, and supports remediation of identified vulnerabilities.
- **Product Managers**: Raises compliance requirements that affect feature scope or timelines; helps define acceptance criteria for security features.
- **Project Managers**: Communicates security-related risks and dependencies; ensures security reviews are included in release checklists.

---

## DevOps / Site Reliability Engineer (SRE)

### Role Summary
DevOps and SRE engineers design and maintain the infrastructure, CI/CD pipelines, and reliability practices that enable teams to deliver and operate software safely at scale.

### Responsibilities
- Build and maintain CI/CD pipelines, deployment automation, and infrastructure-as-code
- Define and monitor service level objectives (SLOs) and reliability metrics
- Lead on-call processes and post-incident reviews
- Manage environment provisioning, secrets, and access controls
- Drive observability initiatives (logging, metrics, alerting)

### Goals
- Reduce deployment risk and time-to-production
- Maintain system reliability and minimize customer-impacting incidents
- Empower developers with self-service tooling and fast feedback loops

### Typical Communication
- Deployment readiness sign-off in release checklists
- Incident updates and post-incident review reports
- Infra capacity and reliability reviews with Engineering Managers

### Interaction with Existing Roles
- **Developers**: Partners on pipeline design, deployment configuration, and production debugging; provides tooling to improve developer experience.
- **Product Managers**: Communicates infrastructure constraints that may affect feature commitments or release dates.
- **Project Managers**: Coordinates deployment windows and environment readiness; flags infrastructure risks in release planning.

---

## Customer Support / Success Manager

### Role Summary
Customer Support and Success Managers act as the voice of the customer within OctoAcme. They surface product pain points, manage escalations, and partner with product and engineering teams to improve customer outcomes.

### Responsibilities
- Triage and resolve customer-reported issues
- Identify and escalate recurring problems to Product and Engineering
- Maintain support documentation, FAQs, and runbooks
- Track customer health metrics and churn risk
- Facilitate customer onboarding and adoption programs

### Goals
- Resolve customer issues quickly and with high satisfaction
- Reduce support ticket volume through proactive documentation and product improvements
- Increase customer retention and product adoption

### Typical Communication
- Support ticket triage and escalation channels
- Weekly customer health summaries to Product Managers
- Feature feedback aggregation for roadmap input

### Interaction with Existing Roles
- **Developers**: Reports confirmed bugs and helps reproduce issues; validates fixes before closing support tickets.
- **Product Managers**: Shares aggregated customer feedback and pain points to inform prioritization; collaborates on support-facing release notes.
- **Project Managers**: Flags customer-facing delivery risks; coordinates communication plans for known outages or feature delays.

---

## Data Analyst

### Role Summary
Data Analysts collect, analyze, and interpret product and operational data to support evidence-based decisions across OctoAcme teams.

### Responsibilities
- Define and maintain dashboards and reporting infrastructure
- Analyze usage patterns, funnel metrics, and feature adoption
- Partner with Product Managers on success metrics and experiment design
- Provide data-driven insights to support roadmap and prioritization decisions
- Ensure data quality, governance, and access controls

### Goals
- Make data accessible and actionable for all teams
- Enable confident, evidence-based product and delivery decisions
- Improve measurement coverage for key business outcomes

### Typical Communication
- Weekly or bi-weekly metrics reviews with Product and Project teams
- Ad-hoc analyses in response to strategic questions
- Dashboard documentation and data dictionary maintenance

### Interaction with Existing Roles
- **Developers**: Collaborates on instrumentation, event tracking, and data pipeline implementation; reviews data models for accuracy.
- **Product Managers**: Partners on defining success metrics, designing experiments, and interpreting results to inform feature decisions.
- **Project Managers**: Provides delivery metrics (velocity, cycle time, defect rates) to support project health reporting and retrospectives.

---

## How Expanded Personas Improve Accountability, Communication, and Delivery

Adding these roles to OctoAcme's documented personas produces concrete improvements across three dimensions:

### Accountability
Explicitly defining responsibilities for roles such as Engineering Manager, Tech Lead, and Security Engineer ensures that every area of project delivery has a named owner. This eliminates gaps where work might fall through the cracks and enables clearer escalation paths when issues arise.

### Communication
Documenting the typical communication patterns and collaboration points for each role reduces ambiguity about when and how to involve the right people. For example, knowing that a Scrum Master coordinates with Project Managers on sprint-level risks—and that Customer Support shares ticket trends with Product Managers—creates predictable, repeatable information flows across the organization.

### Delivery Consistency
When all team members understand how their role connects to others—across planning, execution, release, and support—delivery becomes more predictable. Roles like DevOps/SRE and Security Engineer are embedded into the delivery lifecycle from the start, reducing late-stage surprises. Data Analysts provide the measurement layer needed to evaluate outcomes and drive continuous improvement.

Together, these personas complement the core Developers, Product Managers, and Project Managers documented in [Roles & Personas](./octoacme-roles-and-personas.md), giving OctoAcme teams a complete, shared vocabulary for how cross-functional delivery works.

---

## How these personas are used in the exercise
- Use these persona definitions alongside the core personas to frame cross-functional scenarios in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance and collaboration context.
