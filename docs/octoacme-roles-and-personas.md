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

## Release Manager

### Role Summary
The Release Manager owns the release schedule, coordinates cross-functional readiness, and ensures deployments happen safely and on time. They are the single accountable party for each release from code-freeze to post-deploy verification.

### Responsibilities
- Own and maintain the release calendar and deployment schedule
- Coordinate release readiness across PM, PdM, Developers, and QA Lead
- Confirm rollback plans are documented and tested before each deployment
- Drive the go/no-go decision for production releases
- Communicate release status and post-deploy outcomes to stakeholders

### Goals
- Deliver releases predictably with minimal production incidents
- Reduce unplanned rollbacks through thorough pre-release checks
- Increase team confidence in the release process

### Typical Communication
- Release readiness reviews with PM, QA Lead, and Developers
- Go/no-go sign-off notifications to stakeholders
- Post-release retrospectives and incident summaries

### Interactions with Existing Roles
- **PM**: Aligns release schedule with project milestones and communicates any slippage.
- **PdM**: Validates that release scope matches agreed-upon feature commitments.
- **Developers**: Confirms all code is merged, CI is green, and deployment artifacts are ready.
- **QA Lead**: Receives final QA sign-off before triggering a production deployment.

---

## QA Lead

### Role Summary
The QA Lead defines the test strategy for the project, coordinates test execution across the team, and ensures that quality gates are met before any release. They are the primary advocate for quality across all delivery stages.

### Responsibilities
- Define and maintain the overall test strategy (unit, integration, end-to-end, regression)
- Set and enforce quality gates and Definition of Done criteria
- Coordinate manual and automated test execution across the team
- Review and approve test results before release sign-off
- Track and report on defect trends and quality metrics

### Goals
- Prevent regressions and critical defects from reaching production
- Increase test coverage and reduce manual testing overhead over time
- Provide the team with fast, reliable quality feedback

### Typical Communication
- QA status updates in sprint reviews and daily standups
- Test reports and sign-off documentation shared with PM and Release Manager
- Defect triage sessions with Developers

### Interactions with Existing Roles
- **PM**: Reports on quality risks and blockers that may affect release timelines.
- **PdM**: Clarifies acceptance criteria to ensure test cases reflect intended behavior.
- **Developers**: Collaborates during feature development to review testability and review PR test coverage.
- **Release Manager**: Provides formal QA sign-off as a required gate before production deployment.

---

## Technical Writer

### Role Summary
The Technical Writer is responsible for maintaining and improving all user-facing and internal process documentation. They ensure that delivered features are accompanied by accurate, accessible documentation.

### Responsibilities
- Author and maintain user guides, API documentation, and process docs
- Collaborate with Developers and QA to capture feature behavior accurately
- Ensure all shipped features include corresponding documentation updates
- Establish and uphold documentation standards and templates across the project
- Review release notes for clarity and completeness before publication

### Goals
- Ensure all stakeholders can find and understand relevant documentation
- Reduce support burden through clear, self-service documentation
- Keep documentation in sync with the current state of the product

### Typical Communication
- Documentation reviews during sprint reviews and release readiness checks
- Async feedback via PRs and doc review comments
- Coordination with PdM on roadmap items to plan documentation ahead of release

### Interactions with Existing Roles
- **PM**: Coordinates documentation milestones within the project timeline.
- **PdM**: Receives feature context, user stories, and priority guidance for documentation efforts.
- **Developers**: Works with developers to validate technical accuracy and capture implementation details.
- **QA Lead**: Aligns on acceptance criteria to ensure documentation matches validated behavior.

---

## Business Analyst

### Role Summary
The Business Analyst bridges business stakeholders and the delivery team. They translate complex business goals into clear, actionable requirements and help ensure that acceptance criteria accurately reflect stakeholder intent.

### Responsibilities
- Elicit, analyze, and document business requirements and acceptance criteria
- Facilitate stakeholder workshops and requirements-gathering sessions
- Support backlog grooming by refining and prioritizing user stories
- Validate that delivered solutions meet the stated business objectives
- Identify process gaps and propose improvements to workflows

### Goals
- Ensure the team builds the right things based on validated business needs
- Reduce rework caused by unclear or changing requirements
- Improve stakeholder confidence through clear documentation of decisions and trade-offs

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story refinement sessions with PM and PdM
- Acceptance criteria reviews shared with Developers and QA Lead

### Interactions with Existing Roles
- **PM**: Provides requirements and process documentation that informs project planning and scope management.
- **PdM**: Collaborates on backlog grooming, user story definition, and stakeholder alignment.
- **Developers**: Clarifies acceptance criteria and answers questions during feature implementation.
- **QA Lead**: Ensures test cases are aligned with documented acceptance criteria and business intent.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

