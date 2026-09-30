## first commands for init
```bash
 git init

 ```

#this is use in the folder where you want to init the git it will add the .git file in your folder and mostly this is hidden file 

```bash
git config --global user.name  #to check the username 

git config user.name "<name>"  #to change the username

git config --global user.email # to check the user eamil

git config user.email

```
```bash
git status # Check the status of your repo
git add <file> # Add a file to the staging area
git add . # Add all files to the staging area
git commit -m "<message>" # Commit changes with a message
git log # View commit history
git log --oneline # View commit history in compact format
git diff # Show changes between working directory and the last commit
git diff <branch1> <branch2> # Show changes between two branches
git show <commit> # Show changes made in a specific commit
git ls-files # List all files tracked by Git
git blame <file> # Show who changed what in a file
git bisect # Find the commit that introduced a bug
git reflog # Show a log of all local commits
git cat-file -p <commit> # Display the content of a commit object
git rev-parse <ref> # Get the SHA-1 hash of a reference
git fsck # Verify the integrity of the repository
git gc # Clean up unnecessary files and optimize the repository

```
## Remote Repositories

```bash 
git remote add origin <url> # Connect local repo to remote
git push -u origin <branch> # Push changes to remote branch
git pull # Pull changes from remote repo
git clone <url> # Clone a remote repository
git remote -v # List remote connections
git remote rm <remote> # Remove a remote connection
git fetch # Fetch updates from remote repo without merging
git remote show <remote> # Show details about a remote repository
git remote rename <old-name> <new-name> # Rename a remote repository
git push --tags # Push all tags to remote repository
git push --force # Force-push changes to the remote repository
git push origin --delete <branch> # Delete a remote branch
git pull --rebase # Pull and rebase the current branch
git fetch --all # Fetch updates from all remote repositories
git remote update # Update remote-tracking branches

```
## Branching & Merging
```bash
git checkout <branch>
git branch
git switch <branch>
git checkout -b <branch> # Create and switch to a new branch
git merge <branch> # Merge a branch into the current branch
git branch -d <branch> # Delete a branch
git branch -r # List remote branches
git branch -a # List local and remote branches
git branch -u <upstream-branch> # Set upstream branch for the current branch
git branch -m <old-name> <new-name> # Rename a branch
git branch --merged # List branches that have been merged into the current branch
git branch --no-merged # List branches that have not been merged into the current branch
git merge --abort # Abort an ongoing merge operation
git merge --squash <branch> # Squash the commits from a branch into a single commit
git merge --no-ff <branch> # Merge with a merge commit even if it's a fast-forward merge
git log --online featcher.


## Git Reset vs Revert & Branching Strategies

```bash
git reset --soft HEAD~1
git reset --mixed HEAD~1
git reset --hard HEAD~1

git log --oneline  # to get all commit id's and commits

git revert " commit ID"

git reflog  # undo or revert the mistakly happened reset


```
<<<<<<< HEAD
=======
## Advanced Git: Merge, Rebase, Stash & Cherry Pick
``` bash
git merge < branch name >

git switch main
git switch <branch name>

git rebase main

git log --oneline

git log --oneline --graph --all

git cherrpick < commit ID> ## eg. e4f5g6h

git stash apply

git stash pop

```




>>>>>>> 2899a133de2e05cc6f79efbcde136be971d440d3

