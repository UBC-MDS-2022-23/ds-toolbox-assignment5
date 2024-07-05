# Definition: git status

## How is the "git status" command in the terminal useful?

1. It can tell you which branch of the repository you are currently on. This is usually the first line output, for example, "On branch main".

2. It can tell you if the branch you are working on matches the version of the branch on the remote repository (GitHub). If the branch matches that one the remote it will say "Your branch is up to date with 'origin/main'." Otherwise, it will say something like "Your branch and 'origin/main' have diverged,
and have 1 and 2 different commits each, respectively."

3. It can be used in the terminal to check on the status of any files in a git repository. Files can fall into one of the following categories:
    - *Untracked*: this means that the file is not currently being kept track of in version control
    - *Changes not staged for commit*: this means that the file has been changed but the file has not yet been added to the staging area and changes have not been committed
    - *Changes to be committed*: this means that the file has been added to the staging area and the changes can be committed

Reference: <https://github.com/git-guides/git-status>

## How can you access the same information provided by this command via JupyterLab instead?

To access the same information provided by "git status" in JuptyerLab you can click on the Git extension icon. 

1. At the top "Current Repository" and "Current Branch" show you in which repository and branch within that repository you are currently working.

2. Under the "Changes" tab you can see the status (Staged, Changed, Untracked) of the files similar to with the git status command. 

3. Under the "History" tab you can see the history of commits in chronological order. It will also show you which branch on the local and remote repository is associated with the commit.


