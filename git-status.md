## Definition: git status  

This command gives you a status update of the git repository you are working in.  
When you run this command, the output includes:  
• The name of the branch you are currently in  
• Staged Changes: files that are ready to be committed  
• Unstaged Changes: files that are modified but not staged  
• Untracked Files: new files that are not tracked by git  
• Branch Status: whether the branch is ahead or behind the parent  
<br>  
You want to run git status before you commit your changed.  
*note you can also run git status in jupyterlab by opening the launcher ->terminal -> typing 'git status' there.   
<br>
### Example:   
(base): $ git status  
On branch fancy_readme  
Changes not staged for commit:  
  (use "git add/rm <file>..." to update what will be committed)  
  (use "git restore <file>..." to discard changes in working directory)  
	modified:   .OTTER_LOG  
	modified:   README.md  
	modified:   assignment_04.ipynb  
	deleted:    recipe.jpeg  

Untracked files:  
  (use "git add <file>..." to include in what will be committed)  
	assignment_05.ipynb  
	cake1.jpeg  
	cake2.jpeg  
