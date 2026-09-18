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
