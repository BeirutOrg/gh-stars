### What are you changing and why?
<!-- This additional context is important for the reviewers to understand the motivation for your change -->

### Anything you want to highlight for special attention from reviewers?
<!-- This is a great place to discuss solution caveats, what has been explored and the tradeoffs made -->

#### Which environments does this change target?
<!-- Please leave a brief explanation of why and how this change does not apply to those environments.-->
- [x] Production
- [ ] Non-production
  - [ ] dev/test
  - [ ] docs

#### Risk Assessment
- [ ] **No risk** changes are those that don’t affect production, including documentation and changes to tests.
- [ ] **Low risk** the change is fully under one or more Feature Flags OR the modifications are small, highly observable, and easily rolled back.
- [ ] **Medium risk** changes that are isolated, reduced in scope or could impact few users and not bring the site down.
- [ ] **High risk** changes are those that could impact our customers and SLOs, low or no test coverage, low observability, or slow to rollback. This includes changes that touch the **`GITHUB_TOKEN`** permissions.

### If something goes wrong, what are the mitigation and rollback strategies?
- [ ] **Experiment** - Change will be tested with an experiment, but will need to be rolled back if the experiment does not work. Please link to the relevant experiment below.
- [ ] **Feature Flag** - Change can be disabled by feature flag, but will need to be rolled back if the feature flag does not work. Please link to the relevant feature flags below.
- [ ] **Staging Deploy** - This change will be tested in staging before being queued to deploy.
- [ ] **Rollback** - Change can only be disabled by rolling back the merge group, or by deploying a revert commit.
