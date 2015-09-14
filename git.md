Git
===

1.  Repository names should be lowercase and dasherized
    (i.e., `my-project-name`) unless there's an existing naming convention
    within the language, framework, etc. of the project.
2.  Branch names should be lowercase and dasherized
    (i.e., `my-feature-branch`). Use a thoughful name that explains the changes
    in the branch without being overly verbose or vague.
3.  Repositories should have a `dev` branch and a `master` branch.
    *   `dev` should contain the latest (sometimes unreleased) changes. It
        should always be deployable and ready to be merged into `master`. It
        should be the base for all feature branches.
    *   `master` should contain the latest release in production. `dev` should
        only be merged in once a release has been verified in staging.

Commits
-------

1.  Commits should be atomic. That is, a commit should be one (and just one)
    logical unit. A good indicator of a non-atomic commit is the need for an
    awkward, run-on commit message.
2.  We follow [the seven rules of a great commit message](http://chris.beams.io/posts/git-commit/):
    1.  Separate subject from body with a blank line.
    2.  Limit the subject line to 50 characters.
    3.  Capitalize the subject line.
    4.  Do not end the subject line with a period.
    5.  Use the imperative mood in the subject line.
    6.  Wrap the body at 72 characters.
    7.  Use the body to explain _what_ and _why_ vs. _how_.

Workflow
--------

We follow the [GitHub Flow](https://guides.github.com/introduction/flow/index.html),
with a few key differences and additions:

1.  Branches should be created off of `dev`, except for repositories that only
    have `master`.
2.  Branches to fix an existing Issue should be named with the Issue number at
    the beginning (i.e., `123-fix-for-some-issue`).
3.  Changes should be deployed and verified in staging before ever reaching
    production. This usually happens when the Pull Request is merged into `dev`.
4.  Pull Requests should only be merged once a second pair of eyes has reviewed
    and approved the changes. The creator of the Pull Request is responsible for
    actually merging the code once the reviewer has approved.
5.  Before a Pull Request is merged, the commits should be rebased against `dev`
    and fixed-up as necessary: `git rebase -i dev`. For most changes, this
    usually means fixing-up all commits into one; however, more is acceptable to
    remain atomic.
