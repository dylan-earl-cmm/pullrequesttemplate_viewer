## Summary

> Link to related issues/jira ticket

> Add your summary

> If this is a UI change, please include some screenshots/animated gif

#### Related PRs

> List relevant pull requests: [if needed]

#### Documentation

> Have you done something here that, if documented, would be beneficial to the team? If so, have you
> added that documentation? (In the README, [How
> Tos](https://covermymeds.atlassian.net/wiki/spaces/SPEC/pages/507130406/How+Tos), LucidChart links, etc.?)

#### Architecture Diagrams

> If this PR alters any of the workflows, please update the mermaid diagrams in the docs folder

## Risk

### Overall risk level (High / Medium / Low / Minimal)

> Overall risk level: [High/Medium/Low/Minimal]
> Summary of the risk: [insert summary]

### PHI Risk

> Are there any PHI ramifications of this PR? If so, point out mitigation and what risk is brought on by this deployment.

##### Observability Safety

- [ ] New UI elements containing PHI have been explicitly masked for Datadog consumption
- [ ] N/A

### Security Risk

> Are there any security risks? If so, point out mitigation and what risk is brought on by this deployment.

### Special Considerations

> Does this change add functionality that requires special handling of test cases? If so, how does the code handle that?

## Additional Approvals

> If needed, gather the appropriate approvals.
> https://covermymeds.atlassian.net/wiki/spaces/USP/pages/1830617182/UX+and+Product+Sign-off+Guidelines

- [ ] Product
- [ ] UX
- [ ] N/A

## Testing

- [ ] All existing automated E2E tests pass locally
- [ ] E2E documentation updated (if test workflows were changed)
- [ ] Smoke tests will be completed in staging after merge using the documented smoke test cases

### Automated E2E Tests

> Run all automated E2E tests locally before submitting this PR.
>
> 1. Start the E2E stack: `just e2e-stack start`
> 2. Run the test suite: `just test e2e`

> Detailed instructions:  
> https://github.com/covermymeds/usp-springboard/wiki/Running-E2E-Tests-Locally

> If Playwright workflows were modified or new workflows were added, update the corresponding documentation:  
> https://covermymeds.atlassian.net/wiki/spaces/USP/pages/3602874409/USP+Springboard+Automated+E2E+Test+Workflows

### Smoke Tests

> Smoke tests should be run in the staging environment after this PR is merged to `main`.

> Smoke test case documentation:  
> https://covermymeds.atlassian.net/wiki/spaces/USP/pages/2086141993/USP+Smoke+Testing+-+Lower+Environments

## Post Deploy Testing Plan

> How will you verify your change works without regression in production?

## Deployment

> When will the code be deployed?

## Rollback Plan

> If any issues arise, how will we rollback?

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
