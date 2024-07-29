Definition: git status

the command "git status" is used to check the local status of the working directory for a git repository. Your current working directory must be  a directory which contains a .git folder.

Executing git status will give you which branch you are on. For example, right now the read out is:
On branch git-status

It will tell you the state of any files (untracked, staged, etc.)
Right now, it's telling me:
Untracked files:
  .ipynb_checkpoints
  git-status.md

It is also telling me I haven't added these to the commit yet:
nothing added to commit but untracked files present (use "git add" to track)

This info is the same info that would be provided by the "Changes" tab on the git tab on the Jupyter IDE. So over there I can see my untracked files (including that they are the checkpoints)