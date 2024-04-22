# PUSH

**Term**: `push`

**Definition**: The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch, but whereas fetching imports commits to local branches, pushing exports commits to remote branches. Remote branches are configured using the git remote command. Pushing has the potential to overwrite changes, caution should be taken when pushing. 

**Example**: git push is most commonly used to publish an upload local changes to a central repository. After a local repository has been modified a push is executed to share the modifications with remote team members.

Using git push to publish changes


![Alt Text](https://media.geeksforgeeks.org/wp-content/uploads/20230512161942/git-push.webp)


The above diagram shows what happens when your local main has progressed past the central repository’s main and you publish changes by running git push origin main. Notice how git push is essentially the same as running git merge main from inside the remote repository.


**Code Snippet**: 

```bash
git push <remote-name> <branch-name>
```
