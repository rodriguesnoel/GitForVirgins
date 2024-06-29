# GitForVirgins
Git for the very first time!
This is an instruction on how to go about learning Git and GitHub.

Repository (repo):
git --version
git init
git config user.[your_GitHub_UserName] "title_of_repo"
git status
A collection of files and folders that git is used to track. The repository includes the entire history of changes made to the project by your team.


Stage:
git add [name_of_file]
git add --all or git add -A
When you first add files to an empty repository, they are all untracked. To get Git to track them, you need to stage them, or add them to the staging environment.


Commit:
git commit -m "Message of Your Commit."
git commit - a -m "Message of the Update Your Did."
A way of saving your work in git. When you commit to a repository, it’s like putting the current state of your files into a time capsule. Commits exist only on your local machine until they are pushed to a remote repository. Also, remember to include a message for clear instructions.


Help:
git --help (for the common Git commands)
git help -a or git help --all (everything plus the kitchen sink help)
git commit -help (help relating to commit commands)
git status -help (help relating to status commands)
q (after reading the help instructions)
If you've got goldfish memory, use the help command.


Branch:
git branch [name_of_new_branch]
git checkout [name_of_new_branch] (this changes the directory to the newly created branch, away from the main repository)
nano index.html (now make changes to whatever file, eg index.html, or add images)
git add --all (stage all changes including the branch)
git status (check status)
git commit -m "[Message of the branch]" (commit with a message)
ls (list all the files on the branch since you're still on the directory)
open index.html (open the file to see if the new changes took place)
git checkout - or git checkout main (go back to previous directory or to the main repository)
ls (list all the files on the main, so the new files won't be visible)
open index.html (open the file and you'll see the version before)
git checkout [name_of_branch] (to change directory to one of the branches)
git branch (to list all the branches if you're in main)
git checkout -b [name_of_new_branch] (shortcut to create and move to a new branch)

A separate instance of the code that branches off from the main codebase. You might create a branch to work on a specific feature or experiment without impacting the main code. Branches allow you to preserve the integrity of the software and revert to a previous version if necessary, as well as work on your task without disturbing others.


Merge:
git checkout main (first, go to main)
git merge [name_of_new_branch]
open index-html (open the file to check if the merge is successful)
git branch -d [name_of_new_branch] (delete the branch once the merge is successful)

The process of integrating two branches together. When a branch is ready to be incorporated into the primary codebase, it is merged into the master branch. This adds any new or updated code to the official codebase and makes it available to anyone who branches off from that point.

Merge Conflict:
git merge main
