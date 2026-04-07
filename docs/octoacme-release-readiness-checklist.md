# OctoAcme — Release Readiness Checklist

## Purpose
Ensure that all required parties have completed their responsibilities before a production release is triggered. This checklist is owned by the **Release Manager** and must be reviewed and signed off in the release readiness meeting.

---

## 1. Scope & Requirements (PdM + Business Analyst)
- [ ] Release scope is finalized and communicated to all stakeholders
- [ ] All features in scope have accepted user stories with clear acceptance criteria
- [ ] Any scope changes since last release are documented and approved

## 2. Development Completion (Developers + PM)
- [ ] All in-scope PRs are merged to the release branch
- [ ] CI pipeline is green (tests, lint, security scans)
- [ ] No known critical or high-severity open defects without a documented waiver
- [ ] Deployment artifacts (containers, packages, configs) are built and versioned

## 3. QA Sign-off (QA Lead)
- [ ] Test strategy for this release has been executed (unit, integration, regression, smoke)
- [ ] All acceptance criteria for in-scope features have been verified
- [ ] Defect triage is complete; remaining open issues are risk-accepted and documented
- [ ] QA Lead has formally signed off on release readiness

## 4. Documentation (Technical Writer)
- [ ] User-facing documentation updated for all new or changed features
- [ ] Release notes drafted, reviewed, and approved
- [ ] Internal process docs updated if workflows have changed

## 5. Release Logistics (Release Manager)
- [ ] Deployment window confirmed and communicated
- [ ] Rollback plan documented and validated
- [ ] Staging deployment completed and smoke tests passed
- [ ] On-call schedule confirmed for the deployment window
- [ ] Stakeholder communication drafted and ready to send post-deploy

## 6. Go / No-Go Decision
| Role | Name | Decision | Date |
|------|------|----------|------|
| Release Manager | | ☐ Go / ☐ No-Go | |
| QA Lead | | ☐ Go / ☐ No-Go | |
| PM | | ☐ Go / ☐ No-Go | |
| PdM | | ☐ Go / ☐ No-Go | |

> All roles must indicate **Go** before the deployment is triggered. Any **No-Go** blocks the release until the issue is resolved and the checklist is re-reviewed.

---

## Post-Release Verification (Release Manager + Developers)
- [ ] Post-deploy smoke tests passed in production
- [ ] Key metrics and error rates are within normal range
- [ ] Stakeholder release announcement sent
- [ ] Retrospective action items captured (if any)

---

*See also: [Roles & Personas](octoacme-roles-and-personas.md) | [Release & Deployment Guide](octoacme-release-and-deployment.md) | [Risks & Communication](octoacme-risks-and-communication.md)*
