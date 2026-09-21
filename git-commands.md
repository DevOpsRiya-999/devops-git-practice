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


## branch commands 
```bash
git branch #to see all branch
git branch feature-1  # for creating another branch
git switch feature-1  # move to anothere branch
git switch -c feature-2 
git switch main
git branch -d feature-2

git remote -v
git remote add origin <url>

git push -u origin main
git push -u origin feature-1

git fetch
git pull

git clone <url>

git remote add upstream <url>
git fetch upstream
git merge upstream/main

```
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





