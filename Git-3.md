# 🧭 Git Commands Guide

A complete list of commonly used Git commands for managing repositories.

---

## 🏁 1. Setup and Configuration

```bash
# Check Git version
git --version

# Set your username
git config --global user.name "Your Name"

# Set your email
git config --global user.email "you@example.com"

# List all configurations
git config --list

# Initialize a new Git repository
git init

# Clone an existing repository
git clone <repository-url>

# Clone into a specific directory
git clone <repository-url> <directory-name>


# Check the current status of the repo
git status

# Add a specific file
git add <file-name>

# Add all files
git add .

# Remove a file from staging area
git reset <file-name>

# Commit with a message
git commit -m "Your commit message"

# Amend the previous commit
git commit --amend




# List branches
git branch

# Create a new branch
git branch <branch-name>

# Switch to a branch
git checkout <branch-name>

# Create and switch to a new branch
git checkout -b <branch-name>

# Merge a branch into current branch
git merge <branch-name>

# Delete a branch
git branch -d <branch-name>

# Force delete a branch
git branch -D <branch-name>




# Show remote repositories
git remote -v

# Add a remote repository
git remote add origin <repository-url>

# Remove a remote
git remote remove <name>

# Rename a remote
git remote rename <old-name> <new-name>