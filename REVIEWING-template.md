# Reviewing Guide

Follow the instructions at [HowTo: Make a Reviewing Guide][howto] file to complete the following sections.

This document covers who may review pull requests for this project, and provides guidance on how to perform code reviews that meet our community standards. All reviewers must read this document and agree to follow the project review guidelines. Reviewers who do not follow these guidelines may have their privileges revoked.

[howto]: Link to your review guideline

## The Reviewer Role

[Instructions] 

⚠️ **Pick the statement that matches the reviewer role for your project**

Only maintainers review pull requests.

OR

The reviewer role is distinct from the maintainer role. Reviewers can approve a pull request but they cannot merge it. A maintainer handles final approval and merging the pull request.

## Values

### Inclusion

Be welcoming and inclusive. You should proactively ensure that the author is successful. While any particular pull request may not ultimately be merged, overall we want people to have a great experience and be willing to contribute again. Answer the questions they didn't know to ask or offer concrete help when they appear stuck.

### Sustainability

Avoid burnout by enforcing healthy boundaries. Here are some examples of how a reviewer is encouraged to act to take care of themselves:

* Authors should meet baseline expectations when submitting a pull request, such as writing tests.
* If your availability changes, you can step down from a pull request and have someone else assigned.

### Trust

Be trustworthy. During a review, your actions both build and help maintain the trust that the community has placed in this project. Below are examples of ways that we build trust:

* **Transparency** - If a pull request won't be merged, clearly say why and close it. If a pull request won't be reviewed for a while, let the author know so they can set expectations and understand why it's blocked.
* **Integrity** - Put the project's best interests ahead of personal relationships or company affiliations when deciding if a change should be merged.
* **Stability** - Only merge when then change won't negatively impact project stability. It can be tempting to merge a pull request that doesn't meet our quality standards, for example when the review has been delayed, or because we are trying to deliver new features quickly, but regressions can significantly hurt trust in our project.

## Process

[Instructions]

⚠️ **Define your project's review process**


## Checklist

[Instructions]

Below are a set of common questions that apply to all pull requests:

- [ ] Is this PR targeting the correct branch?
- [ ] Does the commit message provide an adequate description of the change?
- [ ] Does the affected code have corresponding tests?
- [ ] Are the changes documented, not just with inline documentation, but also with conceptual documentation such as an overview of a new feature, or task-based documentation like a tutorial? Consider if this change should be announced on your project blog.
- [ ] Does this introduce breaking changes that would require an announcement or bumping the major version?


## Reading List

Reviewers are encouraged to read the following articles for help with common reviewer tasks:

* [The Art of Closing: How to closing an unfinished or rejected pull request] Link to refer
* [Kindness and Code Reviews: Improving the Way We Give Feedback] Link to refer
* [Code Review Guidelines for Humans: Examples of good and back feedback] Link to refer
