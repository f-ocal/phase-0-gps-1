# phase-0-gps-1

- pwd ; print out working directory
- cd ;
- ls ; list of the files
- git clone 'copied URL' ; clone the repository
- touch awesome.md ; create new file
- git add . ; the change is staged.
- git commit -m "added new file called awesome" ; changes are committed
- git push ; uploading to the branch repository
- git checkout -b add-comment-log ; creating new branch and checking out to the new branch.
- git reset HEAD . ; going back to the previous stage. This leaves all your changed files "Changes to be committed", as git status would put it.

Git Stages:

1. Working stage (git add .)
2. Staged (ready to commit) (git commit -m)
3. Committed (snapshot of the version taken) ---> git push (local repository to GitHub remote repository to upload the changes)
