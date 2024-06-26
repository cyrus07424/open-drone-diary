# How to contribute

## Getting Started

* Make sure you have a [GitHub account](https://github.com/signup/free)
* Submit a ticket for your issue, assuming one does not already exist.
  * Clearly describe the issue including steps to reproduce when it is a bug.
  * Make sure you fill in the earliest version that you know has the issue.
* Fork the repository on GitHub

## Making Changes

* Create a topic branch from where you want to base your work.
  * This is usually the main branch.
  * Only target release branches if you are certain your fix must be on that
    branch.
  * To quickly create a topic branch based on main; `git checkout -b
    fix/main/my_contribution main`. Please avoid working directly on the
    `main` branch.
* Make commits of logical units.
* Check for unnecessary whitespace with `git diff --check` before committing.
* Make sure your commit messages are in the proper format.

By contributing code, you grant its use under the [MIT License](https://opensource.org/license/mit).