Git
===

1.  Repository names should be lowercase and dasherized
    (i.e., `my-project-name`) unless there's an existing naming convention
    within the language, framework, etc. of the project.
2.  Branch names should be lowercase and dasherized
    (i.e., `my-feature-branch`). Use a thoughful name that explains the changes
    in the branch without being overly verbose or vague.

Workflow
--------

1.  Pull down the latest commits (`git pull`).
2.  Create a new branch off of the `dev` branch
    (`git checkout -b my-new-feature`).
3.  Commit your changes (`git commit -am 'Added some feature.'`).
4.  Push to the branch (`git push origin my-new-feature`).
5.  Create a new Pull Request against the `dev` branch when it's ready.
