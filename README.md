# saurinkumarghosh
any changes made in a git is called commit
If you want to change the currently working directory and want to change it and go to any other directory you have to write cd command

SOME IMPORTANT INFORMATIONS
1.UNTRACKED:new files that are yet to be tracked
2.MODIFIED:the files that are recently modified.
3.STAGED:Files that are ready to be commited.
4.UNMODIFIED:unchanged files.
-----------------------------------------------------------
To add the files in our github or more easily the changes that are made in the vs code if we want to push them into our github the following steps we have to follor:
1.add:adds new or unchanged files in our working directory to the Git staging area.
syntax: git add<-file name->
2.commit:it is the record of change.
git commit-m "some message"
---------------------------------------------------------------
To push the code from vscode to our github we have to follow certain steps
1.Push:upload the local repo content to remote repo.
syntax:git push origin main(This is helpfull for the first timers to login and authorize vscode from the github)
-----------------------------------------------------------------
 @if we create any local repository using mkdir command in our vscode initially it won't be a git repository.
 @to check weather a repository is a git repository or not we have to use "ls -a" command and this comman will show allthe @files(including hidden files) and if you don't see any git files that is not a git repo that's a local repo.
@ to make it a git repo we have to use "git init" command and this command will convert evry local repo to a git repo.