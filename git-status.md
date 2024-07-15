# Definition: git status

git status is a git command that displays the current state of the current git working directory and staging area. Information displayed can help show untracked, modified, staged, and committed files. This allows a user to better understand what changes have been made and what the developer may need to do in order to get local and remote repositories to the condition that is desired.

Information displayed shows what the current branch is, what files are not tracked, what changes have not been staged, what changes have yet to be committed, and if the current branch is ahead or behind the corresponding remote branch.

## Example output:

On branch git-status
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        git-status.md

nothing added to commit but untracked files present (use "git add" to track)

## Example Output:

On branch main
Your branch is behind 'origin/main' by 1 commit, and can be fast-forwarded.
  (use "git pull" to update your local branch)

nothing to commit, working tree clean

# N.B.

Jupyter Lab can access git status information using the Git extension. Status of git repos can be seen on the Git tab on the left sidebar (Git icon).