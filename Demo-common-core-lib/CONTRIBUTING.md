# Contributing Guide

* [New Contributor Guide](#contributing-guide)
    * [Ways to Contribute](#ways-to-contribute)
    * [Find an Issue](#find-an-issue)
    * [Ask for Help](#ask-for-help)
    * [Pull Request Lifecycle](#pull-request-lifecycle)
    * [Development Environment Setup](#development-environment-setup)
    * [Pull Request Checklist](#pull-request-checklist)

Welcome! We are glad that you want to contribute to our project! 💖

As you get started, you are in the best position to give us feedback on areas of
our project that we need help with including:

* Problems found during setting up a new developer environment
* Gaps in our Quickstart Guide or documentation
* Bugs in our automation scripts

If anything doesn't make sense, or doesn't work when you run it, please open a
bug report and let us know!

## Ways to Contribute

We welcome many different types of contributions including:

* New features
* Builds, CI/CD
* Bug fixes
* Documentation
* Issue Triage
* Answering questions on MS Teams/Mailing List
* Web design
* Communications / Social Media / Blog Posts
* Release management

Not everything happens through a Github pull request. Please come to our
[meetings](#come-to-meetings) or [contact us](https://teams.microsoft.com/l/team/19%3Av7P6X3pmiJA22-Nc81Xm0Ot9Aklb-qjLrZtvNZFi8n81%40thread.tacv2/conversations?groupId=7bad3453-684a-43e8-9095-b308352bea3c&tenantId=f01e930a-b52e-42b1-b70f-a8882b5d043b) and let's discuss how we can work
together.

### Come to Meetings

Absolutely everyone is welcome to come to any of our meetings. You never need an
invitation to join us. In fact, we want you to join us, even if you don’t have
anything you feel like you want to contribute. Just being there is enough!

You can find out more about our meetings by contacting us via our [MS Teams Channel](<link>) or our email "mqc.mqcnet" <mqc.mqc@gmail.com>. You don’t have to turn on
your video. The first time you come, introducing yourself is more than enough.
Over time, we hope that you feel comfortable voicing your opinions, giving
feedback on others’ ideas, and even sharing your own ideas, and experiences.

## Find an Issue

We have good first issues for new contributors and help wanted issues suitable
for any contributor. 
Sometimes there won’t be any issues with these labels. That’s ok! There is
likely still something for you to work on. If you want to contribute, but you
don’t know where to start or can't find a suitable issue, you can contact team:
- Dev team: "Cao Minh Quang" <mqc@gmail.com>.
- Test team: "Cao Minh Quang" <mqc@gmail.com>.

Once you see an issue that you'd like to work on, please post a comment saying
that you want to work on it. Something like "I want to work on this" is fine.

## Ask for Help

The best way to reach us with a question when contributing is to ask on:

* The original project issues: [CEP.COMMONCORE 2025 Issues](<Link>)
* Developer Mailing List: "CEP.COMMONCOREJAVA" <CEP.COMMONCOREJAVA@fpt.com>
* MS Teams Channel: [CEP.COMMONCORE 2025 Channel](https://teams.microsoft.com/l/team/19%3Av7P6X3pmiJA22-Nc81Xm0Ot9Aklb-qjLrZtvNZFi8n81%40thread.tacv2/conversations?groupId=7bad3453-684a-43e8-9095-b308352bea3c&tenantId=f01e930a-b52e-42b1-b70f-a8882b5d043b)

## Pull Request Lifecycle

Pull requests are the best way to propose changes to the codebase. We actively welcome your pull requests:

1. Fork the repo and create your branch from master.
	- Fork the repository to your own account.
	- Create a new branch from the master branch for your changes.
2. Add tests if you've added code that should be tested.
	- Write tests for any new code or features you have added.
    - Ensure that your tests cover all relevant scenarios.
3. Ensure the test suite passes.
	- Run the entire test suite locally to make sure all tests pass.
    - Fix any failing tests before proceeding. 
4. Update the documentation if you've changed APIs.
    - Update any relevant documentation to reflect changes in APIs or new features.
    - Ensure that the documentation is clear and comprehensive.
5. Make sure your code lints.
	- Run a linter to check for any style issues or code inconsistencies.
	- Fix any linting errors to adhere to the project's coding standards.
6. Push your changes to the snapshot branch.
	- Push your changes to a snapshot branch in your forked repository.
  	- This branch will be used to run the CI/CD pipeline.
7. Run CI/CD pipeline:
	- The pipeline will automatically run SonarQube, Coverity, and Black Duck checks.
    - It will also build the code and run all tests.
8. Review the generated reports:
	- Ensure that all checks pass and there are no critical issues.
9. Create a pull request:
	- If all checks pass, the pipeline will automatically create a pull request from the snapshot branch to the main branch. 
    - Include links to the analysis reports in the pull request description for reviewers to verify. 

## Development Environment Setup

Follow these instructions to set up and use the project, or refer to
the [detailed documentation folder]( /
for more information.

### Prerequisites

Ensure you have the following prerequisites installed:

- IntelliJ Community
- Spring Framework version 6.1.3 or higher
- Java Development Kit (JDK) 17
- Gradle

### Setup guide, usage & documentation

About the setup guide, detailed documentation and a few simple examples of how to use the project here. Refer to the
documentation on [COMMONCORE Guideline]( /
for more detailed instructions and examples.

### Build

```shell
./scripts/build.sh
```

### Test

```shell
./scripts/test.sh
```

## Pull Request Checklist

When you submit your pull request, or you push new commits to it, our automated
systems will run some checks on your new code. We require that your pull request
passes these checks, but we also have more criteria than just that before we can
accept and merge it. We recommend that you check the following things locally
before you submit your code:

1. Code Quality:
- Ensure your code adheres to the project's coding standards.
- Run a linter to check for any style issues.

2. Testing:
- Add tests for any new code or features.
- Ensure all existing and new tests pass.

3. Documentation:
- Update any relevant documentation if you've changed APIs or added new features.
- Ensure your code is well-commented where necessary.

4. Functionality:
- Verify that your changes work as expected.
- Test your changes in different environments if applicable.

5. Dependencies:
- Check for any new dependencies and ensure they are necessary.
- Update dependency documentation if required.

6. Commit Messages:
- Write clear and descriptive commit messages.
- Follow the project's commit message guidelines.

7. Merge Conflicts:
- Ensure your branch is up-to-date with the master branch.
- Resolve any merge conflicts before submitting.

8. Review:
- Self-review your code changes.
- Optionally, ask a peer to review your changes before submission.
