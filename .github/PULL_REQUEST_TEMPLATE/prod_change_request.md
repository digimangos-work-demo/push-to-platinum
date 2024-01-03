<!-- Authors: Please fill out this form carefully and completely. See also:
- https://digimangos.com/articles/production-change-request/
- https://digimangos.com/articles/getting-your-pr-change-request-approved-first-time/ -->
_**Reviewers:** Your careful consideration is appreciated. By approving, you endorse the deployment and mitigation plans, along with the proposed code changes. If there are uncertainties or omissions, please request clarification_

#### Overview

<!--
This section establishes the background, outlining the purpose behind initiating this pull request.

Code modifications should address existing issues, and if none exist, a new one should be created within the respective repository. Link associated discussions, comments, pull requests, and feature releases (refer to [Digimangos Releases](https://digimangos.com/articles/releases#readme)).
-->

### Objectives

<!-- Feel free to adapt this segment from the Production Change Record template that corresponds to the PCR you are integrating. Consult the template: pcrs/TEMPLATE.md -->

#### Target Environments

- [ ] example-website.com
- [ ] alternative-example-website.com

#### Evaluation of Risk

<!--
Choose an appropriate risk level from the following options and provide rationale for the chosen level. Remove the others.

Refer to: [PR Risk and Rollout Review](https://digimangos.com/articles/pr-risk-and-rollout-review)
-->

- **Low risk:** This change is securely encapsulated under one or more Feature Flags, OR the modifications are minimal, highly visible, and easily reversible.
- **Medium risk:** The alterations are confined, have limited scope, and may affect a small subset of users without disrupting overall site functionality.
- **High risk:** These changes have the potential to impact customers and service-level objectives (SLOs), with either minimal or no test coverage, limited visibility, or a slow rollback process.
