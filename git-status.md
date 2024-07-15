# Definition: git status

## Explain what the git status command is useful for. 
The git status command is useful to see the status of your local git repository files and the differences between your local git and the remote GitHub repositories. 
It displays if there are commits ahead or behind between your branch and the origin (remote), so that you can pull or push changes. 
Also, git status shows the changes that are ready to be committed, changes that are not staged, and any untracked files.

## How can you access this information in JupyterLab IDE instead of the terminal?
You can also access the same information by opening the "Changes" section in the Git tab in JupyterLab IDE. The IDE displays the following:
<ol>
    <li>Untracked: shows the files that have not been added to the Staging area (and won't be commited) </li>
    <li>Changed: shows the files that have changes not staged for commit</li>
    <li>Staged: Shows the files that have changes ready to be committed</li>
    
</ol>