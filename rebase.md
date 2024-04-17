# Rebase

**Term**: `Rebase`

**Definition**: Rebase is a Git operation that integrates changes from one branch into another by moving the entire branch to the tip of a different one. It effectively rewrites the commit history by applying each commit in the working branch to the target branch individually. The official documentation can be found [here](https://git-scm.com/docs/git-rebase).

**Example**: Suppose you have a feature branch `feature-branch` and a main branch `main`. Instead of merging `feature-branch` into `main`, you decide to rebase `feature-branch` onto `main`. This action replays the commits from `feature-branch` onto the tip of `main`, resulting in a linear history without merge commits. An example:

```
          A---B---C topic
         /
    D---E---A'---F master

```
Will result in:
```
                   B'---C' topic
                  /
    D---E---A'---F master
```

**Code Snippet**: 

```bash
git checkout feature-branch
git rebase main
```
Interactive rebasing allows you to modify commit history interactively. Here's how to use it:

```bash
git rebase -i HEAD~3
```