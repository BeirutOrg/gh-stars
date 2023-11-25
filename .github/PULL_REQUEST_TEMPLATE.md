<!--
Authors: Please fill out this form carefully and completely.
-->

### What are you changing and why?
<!-- Explain the changes you made -->

#### Which environments does this change target?
<!-- If it is a Production change and you have unselected any combination of dotcom, proxima or GHES
     Please leave a brief explanation of why and how this change does not apply to those environments.-->
- [x] Production
- [ ] Non-production
  - [ ] dev/test
  - [ ] docs

#### Risk Assessment
<!-- Please select from one of the following and detail why this level was chosen -->

- [ ] **No risk** changes are those that don’t affect production, including documentation and changes to tests.
- [ ] **Low risk** the change is fully under one or more Feature Flags OR the modifications are small, highly observable, and easily rolled back.
- [ ] **Medium risk** changes that are isolated, reduced in scope or could impact few users and not bring the site down.
- [ ] **High risk** changes are those that could impact our customers and SLOs, low or no test coverage, low observability, or slow to rollback. This includes changes that touch the **`GITHUB_TOKEN`** permissions.

### If something goes wrong, what are the mitigation and rollback strategies?
<!-- Common deployment risk mitigation strategies are listed below. -->

- [ ] **Experiment** - Change will be tested with an experiment, but will need to be rolled back if the experiment does not work.
- [ ] **Feature Flag** - Change can be disabled by feature flag, but will need to be rolled back if the feature flag does not work.
- [ ] **Staging Deploy** - This change will be tested in staging before being queued to deploy.
- [ ] **Rollback** - Change can only be disabled by rolling back the merge group, or by deploying a revert commit.

### Observability
<!--
  If you have observability resources for this change.
-->
