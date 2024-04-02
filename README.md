# GitCollab_Masai

# Git Commands Reference

## Cloning the Repository for the First Time
```bash
git clone <repository_URL>
git init

# Making Changes to Files
# Add changes to the staging area
git add <file_name>

# Commit changes
git commit -m"Your commit message"

#Pushing Changes to Remote Repository
git push origin <branch_name> - main, master etc

# Create a new branch
git branch - this will show all the present branches
git branch <new_branch_name> - this will create new branch
git checkout -b <new_branch_name> - this will switch from current branch to the new branch

# Push new branch to remote repository
git push origin <new_branch_name>

# Switching Between Branches
git checkout <branch_name>


# Switch to the branch where you want to merge changes
git checkout <target_branch>

# Merge changes from another branch
git merge <source_branch>

# Resolving Merge Conflicts
# Identify conflicts in the affected files
# Resolve conflicts manually by editing the files

# Add the resolved files to staging area
git add <resolved_file_1> <resolved_file_2> ...

# Commit the changes
git commit -m "Merge conflict resolved"

# Pulling Changes from Remote Repository
git pull origin <branch_name>


# List all branches
git branch

# List remote branches
git branch -r

# Delete a local branch
git branch -d <branch_name>

# Delete a remote branch
git push origin --delete <branch_name>


# Fetching Remote Branches
git fetch
