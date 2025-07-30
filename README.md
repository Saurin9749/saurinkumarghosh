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
--------------------------------
@ if you want to check in which branch you are working in your git repo you have to use "git branch" command and it will show the current branch you are working in.
@ if you want to create a new branch you have to use "git branch -b <branch name>" command and it will create a new branch with the given name.
@ if you want to switch to another branch you have to use "git checkout <branch name>" command and it will.
Init Command: git init
git remote add origin <remote repository URL>
git remote -v (to verify the remote repository)
git branch (to check the current branch)
git branch -M main (to renme the current branch to main)
git push origin main (to push the code to the remote repository)
$$$$MOST IMPORTANLY AS NOW A DAYS THE MASTER TERM IS DEPRECATED AND MAIN IS THE NEW TERM SO WE HAVE TO USE MAIN INSTEAD OF MASTER IN ALL THE COMMANDS.$$$
git push-u origin main (to set the upstream branch for the current branch)
git pull origin main (to pull the changes from the remote repository to the local repository)
git status (to check the status of the repository)
git log (to check the commit history)
git diff (to check the differences between the working directory and the staging area)
git reset (to unstage the files from the staging area)
git reset --hard (to unstage the files and discard the changes made in the working directory)
git checkout -- <file name> (to discard the changes made in the working directory for a specific file)
git rm <file name> (to remove a file from the working directory and the staging area)
git rm --cached <file name> (to remove a file from the staging area but keep it in the working directory)
git mv <old file name> <new file name> (to rename a file in the working directory and the staging area)
git stash (to temporarily save the changes made in the working directory and the staging area)
git stash pop (to apply the changes saved in the stash to the working directory and the staging area)
git stash list (to list all the stashes saved in the repository)
git stash drop (to delete a specific stash from the stash list)
git stash clear (to delete all the stashes from the stash list)
git tag <tag name> (to create a tag for a specific commit)
git tag -l (to list all the tags in the repository)
git show <tag name> (to show the details of a specific tag)
git push origin <tag name> (to push a specific tag to the remote repository)
git push --tags (to push all the tags to the remote repository)
git fetch (to fetch the changes from the remote repository without merging them)
git merge <branch name> (to merge the changes from a specific branch to the current branch)
git rebase <branch name> (to rebase the current branch with the changes from a specific branch)
git cherry-pick <commit hash> (to apply a specific commit to the current branch)
git revert <commit hash> (to create a new commit that undoes the changes made in a specific commit)
git bisect start (to start the bisecting process to find a specific commit that introduced a bug)
git bisect bad (to mark the current commit as bad)
git bisect good <commit hash> (to mark a specific commit as good)
git bisect reset (to reset the bisecting process)
git config --global user.name "Your Name" (to set the global username for git)
git config --global user.email "
--------------------------------------------
working in mustiple projects at the same time is not a good idea as it will create confusion and you may end up pushing the wrong code to the wrong repository but we can do that by using the following commands:
git config --global user.name "Your Name" (to set the global username for git)
git config --global user.email "your.email@example.com" (to set the global email for git).
workflow for working with Github:
1. Create a new repository on GitHub.
2. Clone the repository to your local machine using `git clone <repository URL>`.
3. Create a new branch for your feature or bug fix using `git checkout -b <branch name>`.
4. Make changes to the code and test them locally.
5. Stage the changes using `git add <file name>` or `git add .`
6. Commit the changes with a descriptive message using `git commit -m "Your commit message"`.
7. Push the changes to the remote repository using `git push origin <branch name>`.
8. Create a pull request on GitHub to merge your changes into the main branch.
9. Review the pull request and resolve any conflicts if necessary.
10. Once the pull request is approved, merge it into the main branch.
11. Delete the branch if it is no longer needed using `git branch -d <branch name>`.
12. Pull the latest changes from the main branch to keep your local repository up to date using `git pull origin main`.
13. Repeat the process for any new features or bug fixes
14. If you need to switch between branches, use `git checkout <branch name>` to switch to the desired branch.
15. If you want to see the commit history, use `git log` to view the commit history of the current branch.
16. If you want to see the differences between the working directory and the staging area, use `git diff` to view the changes made
17. If you want to unstage files, use `git reset <file name>` to unstage specific files or `git reset` to unstage all files.
18. If you want to discard changes made in the working directory, use `git checkout -- <file name>` to discard changes for a specific file or `git reset --hard` to discard all changes made in the working directory.
19. If you want to remove a file from the staging area but keep it in the working directory, use `git rm --cached <file name>`.
20. If you want to rename a file in the working directory and the staging area, use `git mv <old file name> <new file name>`.
21. If you want to temporarily save changes made in the working directory and the staging area, use `git stash` to save the changes and `git stash pop` to apply the changes later.
22. If you want to create a tag for a specific commit, use `git tag <tag name>` to create a tag and `git push origin <tag name>` to push the tag to the remote repository.
23. If you want to fetch changes from the remote repository without merging them, use `git fetch` to fetch the changes.
24. If you want to merge changes from a specific branch to the current branch, use `git merge <branch name>` to merge the changes.
25. If you want to rebase the current branch with changes from a specific branch, use `git rebase <branch name>` to rebase the current branch.
26. If you want to apply a specific commit to the current branch, use `git cherry-pick <commit hash>` to apply the commit.
27. If you want to create a new commit that undoes the changes made in a specific commit, use `git revert <commit hash>`
28. If you want to start the bisecting process to find a specific commit that introduced a bug, use `git bisect start` to start the process.
29. If you want to mark the current commit as bad during bisecting, use `git bisect bad` and if you want to mark a specific commit as good, use `git bisect good <commit hash>`.
30. If you want to reset the bisecting process, use `git bisect reset`.
git branches: (to list all the branches in the repository).
branch checkout: (to switch to a different branch).
git branch -d <branch name> (to delete a branch).
git branch -m <old branch name> <new branch name> (to rename a branch).
git branch -a (to list all the branches including remote branches).
git branch -r (to list all the remote branches).
git push origin --delete <branch name> (to delete a remote branch).
git fetch origin (to fetch the latest changes from the remote repository).
git pull origin <branch name> (to pull the latest changes from a specific branch).
git push origin <branch name> (to push the changes to a specific branch).
git push --set-upstream origin <branch name> (to set the upstream branch for the current branch).
Pull Request: (to create a pull request on GitHub).
Merge conflicts: (to resolve merge conflicts).
git merge --abort (to abort the merge process).
git rebase --abort (to abort the rebase process).
