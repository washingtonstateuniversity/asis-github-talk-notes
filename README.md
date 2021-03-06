GitHub Notes
============

These are my notes for a talk on GitHub to the ASIS team on 2/25/2015.

> GitHub is the largest code host on the planet with over **20 million** repositories. Large or small, every repository comes with the same powerful tools. These tools are open to the community for public projects and secure for private projects. &mdash; https://github.com/features

# GitHub Features

https://github.com/features

 * [You can use Markdown pretty much everywhere!](https://help.github.com/articles/github-flavored-markdown/)
 * There are a handful of [other really nice writing features](https://help.github.com/articles/writing-on-github/).

This stuff is all provided **per repository**.

## Code

### Search

 * [Can search within a repository](https://github.com/washingtonstateuniversity/WSU-spine/search?utf8=%E2%9C%93&q=scroll).
 * [Searches issues as well.](https://github.com/washingtonstateuniversity/WSU-spine/search?q=scroll&type=Issues&utf8=%E2%9C%93)

### Releases

 * Connected to [tags](http://git-scm.com/book/en/v2/Git-Basics-Tagging).
 * [Provides a place for release notes and binary distribution.](https://help.github.com/articles/about-releases/)

## Issues

https://guides.github.com/features/issues/

Neat feature: Issues can be closed from commit messages:

> Further streamline your workflow by closing issues right from your commit messages.

> The syntax is basic: if you want to close issue #35, put `closes` #35 somewhere in your commit message. Once the commit is in your default branch (usually master), the issue will be closed.

> Supported keywords: `close`, `closes`, `closed`, `fixes`, `fixed`

### Labels

 * [Name + color](https://help.github.com/articles/creating-and-editing-labels-for-issues-and-pull-requests/)
 * Can be used to express [almost anything about an issue](http://www.quora.com/What-is-the-best-way-to-name-GitHub-issue-labels), including its type, priority, category, and status.

### Milestone

 * [Plan work](https://help.github.com/articles/creating-and-editing-milestones-for-issues-and-pull-requests/) for longer-term goals, like epics, sprints, or releases.

### Assignee

 * [Assign an issue or pull request to someone.](https://help.github.com/articles/assigning-issues-and-pull-requests-to-other-github-users/)

## Pull Requests

 * https://help.github.com/articles/using-pull-requests/
 * http://readwrite.com/2014/07/02/github-pull-request-etiquette

## Wiki

Wiki-based documentation right there next to the code!

 * https://help.github.com/articles/about-github-wikis/
 * http://www.quora.com/What-are-some-examples-of-very-well-made-GitHub-wiki-pages-for-open-source-projects
 * The Spine has one: https://github.com/washingtonstateuniversity/WSU-spine/wiki

# Organizations and Permissions

 * https://help.github.com/categories/organizations/
 * https://help.github.com/articles/what-s-the-difference-between-user-and-organization-accounts/

Repositories can be **public** or **private**. Repositories under organizations have their access managed with *teams*:

> Once you create an organization, you manage the organization's repository access with teams. &mdash; https://help.github.com/articles/permission-levels-for-an-organization-repository/

When a repository is public, anyone on the internet can see the code, fork it, and submit and comment on issues and pull requests.

When a repository is private, only teams on the *collaborators* list can even see anything related to the repository. What they are allowed to do depends on the team's *access level*.

> [...] team members only have access to the team they are in and the repositories assigned to that team. &mdash; https://help.github.com/articles/what-are-the-different-access-permissions/

There is an *Owners* team, which has full access to the whole organization and its repositories, including things like the organization's billing details.

The standard access levels for a team are:

 * Admin
 * Read/Write
 * Read

See the [complete permission matrix](https://help.github.com/articles/permission-levels-for-an-organization-repository/) for more detail.
