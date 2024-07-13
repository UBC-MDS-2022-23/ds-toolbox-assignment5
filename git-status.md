Definition: git status

git status, a command we run on the terminal, indicates the current status of the files in the current branch in a local repository, compared against the remote repository. If a file is newly introduced in the current working branch, git status will list this file under "Untracked files" because this new file is not in the remote repository yet. git status will also suggest a command to put this file in the staged area. Once this file is staged, git status will indicate this file can be committed.  On the other hand, git status will indicate a modified existing file as Modified.

On JupyterLab IDE, we can view the git status by clicking the Git side menu.  Under 'Changes' tab, we can see which files are Staged, Changed, Untracked.