# Term Name

**Term**: `git switch`  

**Definition**: Switch to a specified branch. The working tree and the index are updated to match the branch. All new commits will be added to the tip of this branch.  
The name of the branch is therefore needed.  
Optionally, a new branch could be created with either `-c`, `-C`, automatically from a remote branch of same name (see `--guess`), or detach the working tree from any branch with `--detach`, along with switching.  
Switching branches does not require a clean index and working tree (i.e. no differences compared to HEAD). The operation is aborted however if the operation leads to loss of local changes, unless told otherwise with `--discard-changes` or `--merge`.  

**Example**:

1. The following command switches to the "master" branch:  
`git switch master`  

2. After working in the wrong branch, switching to the correct branch would be done using:  
`git switch mytopic`  

3. You can give the -m flag to the command, which would try a three-way merge:  
```powershell
git switch -m mytopic
Auto-merging frotz
```

4. After this three-way merge, the local modifications are not registered in your index file, so `git diff` would show you what changes you made since the tip of the new branch.  
To switch back to the previous branch before we switched to mytopic (i.e. "master" branch):

`git switch -`

**Code Snippet**:

```powershell
git switch -c fixup HEAD~3
Switched to a new branch 'fixup'
```

You can grow a new branch from any commit.  
This code snippet creates a new branch "fixup" by switching with "HEAD~3", which means that it is working on commit that is 3 commits relative to the current HEAD.  