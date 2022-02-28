# Rebasing-with-Squashing
Lets make our history clean by creating a single commit for every feature branch.<br/><br/>
Can you squash and rebase?<br/>
YES! It's simple and called: The squash rebase workflow.
Before you merge a feature branch back into your main branch, your feature branch should be squashed down to a single buildable commit, and then rebased from the up-to-date main branch.
### First lets look at the difference between squash and rebase?
Squash does not touch your source branch, and creates a single commit where you want.<br/>
Rebase allows you to go on on the same source branch with a cleaner history.<br/>
As a general rule, when merging a pull request from a feature branch with a messy commit history, you should squash your commits. There are exceptions, but in most cases, squashing results in a cleaner Git history that's easier for the team to read.
### Why would you want to squash commits?
Commit squashing has the benefit of keeping your git history tidy and easier to digest than the alternative created by merge commits. When you run git merge, your HEAD branch will generate a new commit, preserving the ancestry of each commit history. squashing retains the changes but omits the individual commits from history.
### Why would you want to Rebase your history?
