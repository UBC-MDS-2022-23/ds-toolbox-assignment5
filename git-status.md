# Definition: git status

git status shows the current state of your local repository. It tells you which branch you are on and whether anything has changed since your last commit.

When there are changes, it groups your files into three states: untracked files that git has never been told to manage, modified files that have changed but are not staged yet, and staged files that will go into your next commit. 

This makes it useful as a check before and after staging and before commmitting. You can confirm exactly what will go into your next commit, so nothing gets left out or included by accident.

In JupyterLab, the same information is in the Git panel, opened from the Git icon in the left sidebar. It shows the current branch at the top and lists files under Staged, Changed, and Untracked.