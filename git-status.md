# Definition: git status

'git status' is a git command that displays information about the current position of all files in a repository that differ from the latest pull from the remote repository. For example, 'git status' may show that file-A.txt is staged, but not yet committed, and that .gitignore is untracked.

This command if very useful for understanding which changes are untracked, staged, committed, and pushed (pushed changes will not appear in 'git-status' output).

If using the Jupyter Lab IDE instead of a terminal, a visual version of the 'git-status' output is shown in the Git tab on the left side of the screen. Drop down window panes show Staged, Changed, Untracked, and Stash