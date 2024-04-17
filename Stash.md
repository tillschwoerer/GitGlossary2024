# Add definition for Stash

**Term**: `Stash`

**Definition**: It allows developers to temporarily save their ongoing code changes without committing them. This lets them switch tasks or branches without losing their work. They can then easily retrieve the stashed changes later when they're ready to resume working on them.. 

**Example**: 
1. Stash your changes: Use the git stash command. This saves your current uncommitted work (modified files and index state) in a temporary area managed by Git. Your working directory becomes clean, allowing you to focus on the bug fix.
2. Fix the bug: Work on the critical bug fix and commit those changes as usual.
3. Retrieve your stashed work: Once the bug is fixed, use git stash pop (or git stash apply) to reapply the previously stashed changes on top of your current committed bug fix.

**Code Snippet**: 

# ... hack hack hack ...
$ git switch -c my_wip
$ git commit -a -m "WIP"
$ git switch master
$ edit emergency fix
$ git commit -a -m "Fix in a hurry"
$ git switch my_wip
$ git reset --soft HEAD^
# ... continue hacking ...