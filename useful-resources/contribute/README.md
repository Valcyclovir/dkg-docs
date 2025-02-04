---
description: How to contribute to OriginTrail code repositories
---

# Contribution Guidelines

OriginTrail is an ecosystem dedicated to open source software and based on the principles of neutrality, inclusiveness and usability.&#x20;

All project repositories, such as OT node, DKG clients, Houston etc are available on our official Github

If your are new with OriginTrail development, there are guides in this documentation for getting your development environment set up. Please follow the below procedure to contribute new code or fixes:&#x20;

* Create a separate branch, by branching of the relevant branch (we generally follow [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow))
* Create a pull request to **develop** (except for v6 contributions, then use the **v6/develop**) branch containing a description of what your code does and how it can be tested
* Provide at least a minimum of unit tests
* Please include descriptive commit messages

### Rules

There are a few basic ground-rules for contributors:

1. **No `--force` pushes** or modifying the Git history in any way.
2. **Non-master branches** ought to be used for ongoing work.
3. **External API changes and significant modifications** ought to be subject to an **internal pull-request** to solicit feedback from other contributors.
4. Internal pull-requests to solicit feedback are _encouraged_ for any other non-trivial contribution but left to the discretion of the contributor.
5. Contributors should attempt to adhere to the prevailing code-style.

#### Merging pull requests once CI is successful

* Each pull request **must be reviewed and approved by at least two OriginTrail core developers**
* A pull request with no large change to logic that is an urgent fix may be merged after a non-author OriginTrail core developer has reviewed it well.
* All other PRs should sit for 48 hours in order to garner feedback.
* No PR should be merged until all reviews comments are addressed.

#### Reviewing pull requests

When reviewing a pull request, the end-goal is to suggest useful changes to the author. Reviews should finish with approval unless there are issues that would result in:

* Buggy behavior.
* Undue maintenance burden.
* Breaking with house coding style.
* Pessimization (i.e. reduction of speed as measured in the projects benchmarks).
* Feature reduction (i.e. it removes some aspect of functionality that a significant minority of users rely on).
* Uselessness (i.e. it does not strictly add a feature or fix a known issue).

### Releases

Declaring formal releases remains the prerogative of the project maintainer(s).

### Changes to this arrangement

This is an experiment and feedback is welcome! This document may also be subject to pull-requests or changes by contributors where you believe you have something valuable to add or change.

### Heritage

These contributing guidelines are compiled with inspiration from "OPEN Open Source Project" guidelines for the Level project: [https://github.com/Level/community/blob/master/CONTRIBUTING.md](https://github.com/Level/community/blob/master/CONTRIBUTING.md) and Polkadot: [https://github.com/paritytech/polkadot/blob/master/CONTRIBUTING.md](https://github.com/paritytech/polkadot/blob/master/CONTRIBUTING.md)

## Contributor Code of Conduct

As contributors and maintainers of the OriginTrail, we pledge to respect everyone who contributes by posting issues, updating documentation, submitting pull requests, providing feedback in comments, and any other activities.

Communication through any of our channels (GitHub, Discord, Twitter, etc.) must be constructive and never resort to personal attacks, trolling, public or private harassment, insults, or other unprofessional conduct.

We promise to extend courtesy and respect to everyone involved in this project regardless of gender, gender identity, sexual orientation, disability, age, race, ethnicity, religion, or level of experience. We expect anyone contributing to the project to do the same.

If any member of the community violates this code of conduct, the maintainers of the OT Node project may take action, removing issues, comments, and PRs or blocking accounts as deemed appropriate.

If you are subject to or witness unacceptable behavior, or have any other concerns, please email us.

## Questions, Bugs, Features

### Got a Question or Problem?

Do not open issues for general support questions as we want to keep GitHub issues for bug reports and feature requests. You’ve got much better chances of getting your question answered on [Discord](https://discordapp.com/invite/FCgYk2S).

### Found an Issue or Bug?

If you find a bug in the source code, you can help us by submitting an issue to the appropriate Github repo. Even better, you can submit a Pull Request with a fix. We often have bounty programs as well, you might be eligible for rewards!

### Want a Doc Fix?

These docs are available publicly on this [Github repo](https://github.com/OriginTrail/dkg-docs). Feel free to propose updates through Pull requests or open discussions through Github issues
