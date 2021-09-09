# Contribution Guidelines

## Prerequisites

By contributing, you assert that:

* The contribution is your own original work.
* You have the right to assign the copyright for the work (it is not owned by your employer, or
  you have been given copyright assignment in writing).
* You [license](./LICENSE) the contribution under the terms applied to the rest of the project.
* You agree to follow the [code of conduct](./CODE_OF_CONDUCT.md).


## Contributing process
### find open issues or features

 
If something is on the issues list with the 'Up For Grabs' label or no one is asigned yet you can feel free to work on it. You should comment that you are signing up for it on the issue so someone else doesn't also sign up for the work.

### Set up your environment

For contributor:
 * You create, or update, a fork of the project under your GitHub account.

Team members and maintainers:
 + you can work in the project directly

Further on:
 * From there you create a branch based on the develop branch named with the following format: GH - ISSUE_NUMBER - SHORT_TITLE.
 * Please replace the ISSUE_NUMBER with the issue created for that pull request.
 * You can optionaly add a very short title for your issue so the git branches are a bit more easier to read.
 
 Example branch name:
 * GH-2-ContributionGuidelines
 * GH-2
 
Please do not change anything unrelated to that issue, if you think something unrelated should be changed open an issue for that thing in particular.
 

### Prepare commits

A commit is a small logical unit that represents a change.
Please dont create large commits, they should be easy to review and only do what they describe.

Please start you commit messages with "(GH-ISSUE_NUMBER) My awesome message"
Example git message: "(GH-2) Adds contribution guidelines"


### Submit pull request
Prerequisites:

 * You are making commits in a seperate branch.
 * All code should compile without errors or warnings.
 * All tests should be passing.

Submitting PR:

Create a pull request(PR) of you branch against the develop branch.
The PR should be ready to merge, otherwise mark it as a draft.
Creating draft PRs help understanding you progress and means feedback can be given sooner. Waiting until you are ready may mean more changes than you are
interested in if the changes are taking things in a direction the maintainers do not want to go.

Please fill out the PR template, more detail is better and helps reviewing you changes.

One of the team members, or one of the maintainers, will evaluate it within a
reasonable time period. We are human and we have active lives outside of open source. Just know that we will evaluate your pull request.

### Respond to feedback on pull request

We may have feedback for you to fix or change some things. We generally like to see that pushed against the same topic branch (it will automatically update the Pull Request).

If we have comments or questions when we do evaluate it and receive no response, it will probably lessen the chance of getting accepted. Eventually, this means it will be closed if it is not accepted.
Please know this doesn't mean we don't value your contribution, just that things go stale. If in the future you want to pick it back up, feel free to address our concerns/questions/feedback and reopen the issue/open a new PR (referencing old one).

Sometimes we may need you to rebase your commit against the latest code before we can review it further.


## Other general information
If you reformat code or hit core functionality without an approval,
it's likely that no matter how awesome it looks afterwards, it will probably not get accepted.
Reformatting code makes it harder for us to evaluate exactly what was changed.

If you do these things, it will be make evaluation and acceptance easy.
Now if you stray outside of the guidelines we have above, it doesn't mean we are going to ignore
your pull request. It will just make things harder for us.
Harder for us roughly translates to a longer SLA for your pull request.

## Unclear
If anything is unclear please checkout on how we did certain thing in the past or feel free to open an issue based on the question template.


## Acknowledgement

This contribution guide was taken from the [Cake project](https://github.com/cake-build/cake)
and was edited to be more open for a variety of project types.
