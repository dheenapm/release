---
name: Application Release Record
about: Create a record for an application release
title: 'Release Record for [Application Name] - [Version]'
labels: ['release', 'management']
assignees: ''
---

### Application Name:
- _Enter the name of the application here_

### Release Version:
- _Enter the version number here_

### Branches Being Released:
- _Enter the branches being released, e.g., `release-1.0`, `feature-xyz`_

### Pre-release Steps:
- [ ] Build successfully created and verified
- [ ] Code reviewed and merged
- [ ] Code quality checks passed (e.g., Sonar)
- [ ] Dependency scan completed (e.g., Nexus)
- [ ] Security scan completed (e.g., Checkmarx)
- [ ] QA sign-off completed
- [ ] UAT sign-off completed
- [ ] SRE sign-off completed

### Approval:
- **App Owner Approval**: _Name of app owner to approve_
- **SRE Sign-off**: _Name of SRE team member to approve_

### Production Release Steps:
- [ ] Deploy to production
- [ ] Monitor production environment for issues
- [ ] Ensure rollback plan is ready in case of failure

### Post-release Validation:
- [ ] Validate production environment stability
- [ ] Confirm no critical issues are found after 24 hours
- [ ] Perform smoke testing in production

---

### Additional Notes:
- _Any special instructions, risk considerations, or context about this release can be added here._
