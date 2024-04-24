# Term Name

**Term**: `log`		log

**Definition**: Shows the commit logs.

After you have created several commits, or if you have cloned a repository with an existing commit history, you'll probably want to look back to see what has happened. The most basic and powerful tool to do this is the `git log` command.

**Example**: 

By default, with no arguments, `git log` lists the commits made in that repository in reverse chronological order; that is, the most recent commits show up first.

**Code Snippet**: 

`git log -4`		# show only last four commits
`git log --online`	# concise log in one line per commit
`git log --graph`	# log visualization

1. Filter Commits By Author or Committer:

`git log --author <name> 
git log --committer <name>`

2. View All Diff of Changes for Each Commit:

`git log -p -2`	shows the difference (the *patch* output) introduced in each commit. You can also limit the number of log entries displayed, such as using `-2` to show only the last two entries.

3. Filter Commits by Date Range:

`git log --after <date> --before <date>`

4. View Summary of Changes for Each Commit:

`git log --stat`



---

---

---
