## Summary

> Add your summary:



> Link to related issues, jira ticket, and/or related PR's:



> [!NOTE]
> If this is a UI change, please include some screenshots/animated gif

#### Documentation

Have you done something here that, if documented, would be beneficial to the team?

- [ ] Yes
- [ ] No

<details>
  <summary>If so, how have you added that documentation?</summary>
  
- [ ] README
- [ ] How-Tos <kbd>[link](https://covermymeds.atlassian.net/wiki/spaces/SPEC/pages/507130406/How+Tos)<kbd>
- [ ] LucidChart Links
- [ ] Other

> List Other:

</details>

#### Architecture Diagrams

If this PR alters any of the workflows, please update the mermaid diagrams in the docs folder

- [ ] Alters workflow with updated mermaid diagrams
- [ ] N/A

## Risks

### Overall Risks

- [ ] 🔴 High
- [ ] 🟠 Medium
- [ ] 🟡 Low
- [ ] 🟢 Minimal

> Summary of the risks:



### PHI Risks

- [ ] 🔴 High PHI Risk
- [ ] 🟠 Medium PHI Risk
- [ ] 🟡 Low PHI Risk
- [ ] 🟢 Minimal PHI Risk

> If so, what <b><i>risk</b></i> is brought on by this deployment, and what is the <b><i>mitigation plan</b></i>:




Are new UI elements containing PHI masked for Datadog?

- [ ] Yes
- [ ] N/A

### Security Risks

- [ ] 🔴 High Security Risk
- [ ] 🟠 Medium Security Risk
- [ ] 🟡 Low Security Risk
- [ ] 🟢 No Security Risk

> If so, what <b><i>risk</b></i> is brought on by this deployment, and what is the <b><i>mitigation plan</b></i>:



### Special Considerations
Does this change add functionality that requires special handling of test cases?

- [ ] Yes
- [ ] No

> If so, how does the code handle that?



## Testing

### Automated E2E Tests

> [!IMPORTANT]
> Run all automated E2E tests locally before submitting this PR. <kbd>[documentation](https://github.com/covermymeds/usp-springboard/wiki/Running-E2E-Tests-Locally)</kbd>

- [ ] All existing automated E2E tests pass locally

### Smoke Tests

> [!IMPORTANT]
> Smoke tests should be run in the staging environment after this PR is merged to `main`. <kbd>[documentation](https://covermymeds.atlassian.net/wiki/spaces/USP/pages/2086141993/USP+Smoke+Testing+-+Lower+Environments)<kbd>
- [ ] Smoke Tests Ran

### Playwright Workflows

> If Playwright workflows were modified or new workflows were added, update the corresponding <kbd>[documentation](https://covermymeds.atlassian.net/wiki/spaces/USP/pages/3602874409/USP+Springboard+Automated+E2E+Test+Workflows)<kbd>

- [ ] Changes made and documentation updated
- [ ] N/A

## Deployment, Post Deployment, and Rollbacks

> How will you verify your change works without regression in production?



> When will the code be deployed?



> If any issues arise, how will we rollback?



## Additional Approvals

> If needed, gather the appropriate approvals <kbd>[Approval guidelines](https://covermymeds.atlassian.net/wiki/spaces/USP/pages/1830617182/UX+and+Product+Sign-off+Guidelines)</kbd>

- [ ] Product
- [ ] UX
- [ ] N/A

## Manager Checklist

- [ ] All PR comments have been addressed
- [ ] All reviews have been completed
  - [ ] Peer
  - [ ] Risk Review
  - [ ] Product
  - [ ] UX
  - [ ] EM
- [ ] Confirm risk level is appropriate
- [ ] PR creator has filled out the ITGC testing comment to include appropriate testing evidence
- [ ] Rollback plan is in place
- [ ] Confirm that the change is desired to go to production
