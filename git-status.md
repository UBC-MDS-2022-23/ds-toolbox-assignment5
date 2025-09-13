# Definition: git status

`git status` shows the current state of your working directory and staging area. It tells you:
- Which branch you are on and whether it tracks a remote branch (and if you are ahead/behind).
- Which files have changes **not staged** for commit.
- Which files are **staged** and will be included in the next commit.
- Which files are **untracked** (new files Git isn’t tracking yet).
- Helpful hints on how to stage/unstage or discard changes.

It does **not** show diffs; it only summarizes file states. Use `git status -s` for a concise (short) view.

## How to see the same info in JupyterLab
- Open the **Git** panel (left sidebar).  
- The panel lists:
  - **Changed/Unstaged** files (equivalent to “Changes not staged for commit”).
  - **Staged** files (equivalent to “Changes to be committed”).
  - The current **branch** at the top; JupyterLab may also show ahead/behind indicators.
- You can stage/unstage with the “+”/“-” icons and open diffs by clicking a file.
- For commit history, use the **History**/Log view in the Git panel.