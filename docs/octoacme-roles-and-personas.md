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

## UX Designer

### Role Summary
Designs and refines user experiences, ensuring usability and accessibility across OctoAcme products.

### Responsibilities
- Create wireframes, prototypes, and user flows
- Conduct and synthesize user research
- Collaborate with Product Managers and Developers on requirements and solutions
- Participate in design reviews and usability testing
- Establish and maintain design systems and accessibility standards

### Goals
- Deliver intuitive, accessible user experiences
- Reduce usability friction and support adoption
- Ensure design consistency across product surfaces

### Typical Communication
- Design review sessions and prototype walkthroughs
- Usability test results shared with PM and Developers
- Design system updates and component documentation

### Interaction with Other Roles
- Works closely with **Product Managers** to translate user needs into actionable requirements
- Partners with **Developers** on implementation details, design QA, and feasibility trade-offs
- Feeds findings from user research back to **Project Managers** to inform priorities and timelines

---

## QA/Test Lead

### Role Summary
Ensures the quality of software releases through test planning, execution coordination, defect management, and process improvement.

### Responsibilities
- Define test strategies, plans, and quality standards
- Coordinate manual and automated testing efforts
- Track, triage, and communicate defects and quality metrics
- Provide release readiness assessments
- Champion continuous improvement of testing practices

### Goals
- Prevent regressions and ensure acceptance criteria are met before release
- Improve test coverage and reduce time-to-detect defects
- Maintain a clear quality signal for each release

### Typical Communication
- Test plan reviews with Developers and PM
- Defect reports and quality dashboards
- Release readiness sign-off communicated to PM and PdM

### Interaction with Other Roles
- Collaborates with **Developers** on bug resolution, test automation, and Definition of Done
- Updates **Project Managers** and **Product Managers** on release readiness and quality risks
- Works with **DevOps Engineers** on CI/CD pipeline test integration
- Escalates critical defects to **Project Managers** for prioritization

---

## DevOps Engineer

### Role Summary
Automates, monitors, and improves deployment pipelines and infrastructure to enable reliable, repeatable releases.

### Responsibilities
- Build and maintain CI/CD pipelines and infrastructure as code
- Monitor production systems for reliability, performance, and availability
- Collaborate on incident response, root cause analysis, and postmortems
- Manage environment provisioning and configuration management
- Drive automation to reduce manual deployment risk

### Goals
- Enable fast, safe, and repeatable deployments
- Maximize system reliability and minimize mean time to recovery
- Reduce toil through automation

### Typical Communication
- Deployment runbooks and pipeline documentation
- Incident and postmortem reports
- Release window coordination with PM and QA/Test Lead

### Interaction with Other Roles
- Partners with **Developers** on build, deployment, and environment issues
- Works with **Project Managers** to schedule and plan release windows
- Supports **QA/Test Lead** in integrating automated tests into CI/CD pipelines
- Coordinates with **Security Champions** on pipeline security controls and vulnerability scanning

---

## Support Lead

### Role Summary
Acts as the primary interface between users/customers and the product team on support issues, escalations, and feedback.

### Responsibilities
- Triage and escalate reported incidents and user-facing issues
- Communicate release impacts, maintenance windows, and resolutions to customers
- Surface user pain points, bug trends, and feedback to Product and Project Managers
- Maintain support documentation and known-issue lists
- Monitor support queues and SLA compliance

### Goals
- Minimize customer impact during incidents and releases
- Close the feedback loop between users and the product team
- Ensure customers receive timely, accurate communications

### Typical Communication
- Incident escalation notifications to PM/PdM
- Release communication drafts and customer-facing announcements
- Weekly support trend summaries to Product and Project teams

### Interaction with Other Roles
- Notifies **Project Managers** and **Product Managers** of high-impact or recurring issues
- Provides **Developers** with actionable, reproducible bug reports
- Coordinates with **DevOps Engineers** during production incidents and rollbacks
- Reviews release notes with **Project Managers** before customer-facing announcements

---

## Security Champion

### Role Summary
Advocates for security best practices across the team and supports risk identification, remediation, and awareness.

### Responsibilities
- Participate in design reviews and threat-modeling sessions to surface security risks
- Coordinate and track regular security assessments and vulnerability remediation
- Educate the team on evolving security threats and secure coding practices
- Review dependencies and infrastructure changes for security implications
- Escalate critical vulnerabilities to the appropriate stakeholders

### Goals
- Embed security considerations throughout the development lifecycle
- Reduce vulnerability exposure and time to remediation
- Build a security-aware team culture

### Typical Communication
- Security review findings shared in design and PR reviews
- Vulnerability reports and remediation tracking with PM and Sponsor
- Security awareness updates and training materials for the team

### Interaction with Other Roles
- Advises **Developers** on secure coding practices and dependency management
- Escalates critical vulnerabilities to **Project Managers** and the project Sponsor
- Partners with **DevOps Engineers** on pipeline security controls and infrastructure hardening
- Keeps **Product Managers** informed of security risks that may affect the roadmap

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Role Assignment & Review Checklist

Use this checklist at project kickoff and at each major milestone to ensure all necessary roles are assigned and responsibilities are clear.

### At Project Kickoff
- [ ] Project Manager identified and confirmed
- [ ] Product Manager identified and confirmed
- [ ] Developer(s) assigned with clear ownership areas
- [ ] UX Designer assigned (or explicitly noted if not applicable)
- [ ] QA/Test Lead assigned (or testing responsibilities delegated to a Developer)
- [ ] DevOps Engineer identified for deployment and pipeline support
- [ ] Support Lead notified and included in release communication planning
- [ ] Security Champion identified and included in design/architecture reviews

### At Planning
- [ ] All roles have reviewed and acknowledged the Definition of Done
- [ ] QA/Test Lead has drafted or reviewed the initial test plan
- [ ] UX Designer has shared relevant designs or prototypes with Developers
- [ ] DevOps Engineer has confirmed environment and pipeline readiness
- [ ] Security Champion has been included in backlog refinement for security-sensitive items

### At Release
- [ ] QA/Test Lead has signed off on release readiness
- [ ] DevOps Engineer has reviewed and approved the deployment plan
- [ ] Support Lead has reviewed release notes and customer communication
- [ ] Security Champion has confirmed no outstanding critical vulnerabilities

### Periodic Review (Quarterly or Post-Release)
- [ ] Role assignments are still accurate and up to date
- [ ] Each role owner has reviewed their section of this document for accuracy
- [ ] Any new roles or responsibilities identified in retrospectives have been incorporated

