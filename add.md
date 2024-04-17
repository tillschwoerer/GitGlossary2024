# Git Commit

## Definition

A `commit` in the context of Git is an individual change to a file (or set of files). It's essentially a snapshot of your project at a certain point in time. Each commit in Git has a unique ID (a hash) that allows you to keep record of what changes were made, when, and by who. Commits usually contain a commit message which is a brief description of what changes were made.

## Example

When working on a software project, you might make changes to several files to add a new feature. Once you've tested your changes and are satisfied with them, you can commit those changes. This creates a new commit in your Git history that represents the state of your project at that point in time.

## Code Snippet

Here are some basic Git commands related to commits:

- `git commit -m "Your descriptive message here"`: This command creates a new commit with the changes you've staged using `git add`, and includes a descriptive message of your choice.


## Related Terms

- Git: A distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
- Repository: A directory where Git has been initialized to start version controlling your files.
- Branch: A parallel version of a repository. It is contained within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the master branch to publish your changes.
