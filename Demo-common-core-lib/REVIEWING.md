# Reviewing Guide

This document covers who may review pull requests for this project, and provides guidance on how to perform code 
reviews that meet our community standards. All reviewers must read this document and agree to follow the project 
review guidelines. Reviewers who do not follow these guidelines may have their privileges revoked.

## The Reviewer Role

Only maintainers review pull requests. Maintainers are responsible for ensuring that all contributions meet the project's standards before they are merged. They play a crucial role in maintaining the quality and integrity of the project by reviewing code changes, providing constructive feedback, and making final decisions on whether to merge pull requests.
For a list of current maintainers, please refer to our [Maintainer Group](MAINTAINERS.md).

## Values

### Inclusion

Be welcoming and inclusive. As a maintainer, you should proactively ensure that the author is successful. 
While any particular pull request may not ultimately be merged, overall we want contributors to have a 
great experience and be willing to contribute again. Answer the questions they didn't know to ask or offer 
concrete help when they appear stuck.

### Sustainability

Avoid burnout by enforcing healthy boundaries. Here are some examples of how a maintainer is encouraged to act to take care of themselves:
* Authors should meet baseline expectations when submitting a pull request.
* If your availability changes, you can step down from a pull request and have someone else assigned.

### Trust

Be trustworthy. During a review, your actions both build and help maintain the trust that the community has placed in this project. Below are examples of ways that we build trust:

* **Transparency** - If a pull request won't be merged, clearly say why and close it. If a pull request won't be reviewed for a while, let the author know so they can set expectations and understand why it's blocked.
* **Integrity** - Put the project's best interests ahead of personal relationships or company affiliations when deciding if a change should be merged.
* **Stability** - Only merge when then change won't negatively impact project stability. It can be tempting to merge a pull request that doesn't meet our quality standards, for example when the review has been delayed, or because we are trying to deliver new features quickly, but regressions can significantly hurt trust in our project.

## Process

The review process for this project is as follows:

1. Initial Review: The maintainer checks if the pull request (PR) meets the basic requirements as outlined in the [Contributing Guide](CONTRIBUTING.md).
2. Code Review: The maintainer examines the code changes in detail, ensuring they meet the project's coding standards and do not introduce bugs.
3. Feedback: The maintainer provides constructive feedback, highlighting areas that need improvement and suggesting changes.
4. Approval: Once the PR meets all requirements, the maintainer approves it and merges it into the main branch.

## Checklist

Below are a set of common questions that apply to all pull requests:

- [ ] Is this PR targeting the correct branch?
- [ ] Does the commit message provide an adequate description of the change?
- [ ] Does the affected code have corresponding tests?
- [ ] Are the changes documented, not just with inline documentation, but also with conceptual documentation such as an overview of a new feature, or task-based documentation like a tutorial? Consider if this change should be announced on your project blog.
- [ ] Does this introduce breaking changes that would require an announcement or bumping the major version?
- [ ] Have you pushed your changes to the snapshot branch?
- [ ] Has the CI/CD pipeline run successfully, including SonarQube, Coverity, and Black Duck checks?
- [ ] Have you reviewed the generated reports and ensured there are no critical issues?
- [ ] Is the pull request description clear and does it include links to the analysis reports for reviewers to verify?

For a detailed checklist, please refer to the [Contributing Guide](CONTRIBUTING.md).
