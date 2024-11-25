# **Definition: git status**

## What the git status command is useful for?
1. It shows the working tree status.
2. It displays the following.
    - Paths that have differences between the index file and the current HEAD commit
    - Paths that have differences between the working tree and the index file
    - Paths in the working tree that are not tracked by Git (and are not ignored by gitignore(5)).
    - **Note:** The first are what you would commit by running git commit; the second and third are what you could commit by running git add before running git commit.

## How can you access the same information provided by this command if you were using the JupyterLab IDE instead of the terminal?
1. Open the JupyterLab
2. Click the File Browser icone on the far left-hand side and choose the repository
3. Click Jupyter Git extension icon on the far left-hand side
4. It will display the following.
    - Current Repository
    - Current Branch
    - Changes
    - History