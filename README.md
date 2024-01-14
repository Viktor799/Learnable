## Explain version control
Version control is a system that records changes to a file or set of files over time, allowing you to track modifications and manage different versions of your project. It helps multiple people collaborate on a project, revert to previous states, and keep a history of changes. Popular version control systems include Git and SVN.

## Explain the difference between git and github
Git is a distributed version control system that helps manage and track changes in source code during software development. It works locally on your machine, allowing you to create branches, commit changes, and merge code.
GitHub, on the other hand, is a web-based platform that utilizes Git for version control. It provides additional features like hosting repositories remotely, facilitating collaboration among multiple developers, and offering tools for issue tracking, project management, and code review. GitHub acts as a centralized platform for hosting Git repositories and enhancing collaboration within development teams.

## List 3 github alternatives
1. **GitLab:** GitLab is a web-based Git repository manager that provides source code management, continuous integration, and more. It can be self-hosted or used as a cloud service.
2. **Bitbucket:** Bitbucket, owned by Atlassian, offers Git and Mercurial repository hosting. It provides features like code collaboration, continuous integration, and Jira integration. Bitbucket is commonly used for projects involving Atlassian's suite of development tools.
3. **SourceForge:** SourceForge is an older platform that hosts version control systems, including Git, SVN, and others. It offers a variety of features beyond version control, such as project management tools, forums, and bug tracking.

## Explain the difference between git fetch and git pull
`git fetch` and `git pull` are both Git commands, but they serve different purposes:

1. **`git fetch`:**
   - Retrieves changes from the remote repository to your local repository.
   - It updates your remote-tracking branches but does not automatically merge the changes into your working directory.
   - Useful for inspecting changes before merging and avoiding unintended conflicts.
2. **`git pull`:**
   - Retrieves changes from the remote repository and automatically merges them into your current branch.
   - It essentially performs a `git fetch` followed by a `git merge` in one step, bringing the changes directly into your working directory.
   - Quick and convenient but may lead to immediate merges, possibly causing conflicts if not managed carefully.

## Explain in simple terms, git rebase, and the command for it
Git rebase is a command used to change the base of your branch. It helps in combining or integrating changes from one branch to another by moving or reapplying your commits on top of a different branch.

```bash
git rebase <base-branch>
```
## Explain in simple terms, git cherry-pick, and the command for it
Git cherry-pick is a command that allows you to pick and apply specific commits from one branch to another. It's like choosing certain changes and copying them to a different branch.

```bash
git cherry-pick <commit-hash>
```