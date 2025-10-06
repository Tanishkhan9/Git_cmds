# Commit staged changes with a descriptive message
git commit -m "Add user authentication feature"

# Add all tracked file changes and commit in one step
git commit -am "Fix login bug"

# Amend the most recent commit (change message or add forgotten files)
git commit --amend -m "New commit message"

# Show commit history with details
git log

# Show compact one-line per commit
git log --oneline

# Show visual branch structure
git log --graph --oneline --all

# Show last 3 commits
git log -3

# List all local branches (current branch highlighted with *)
git branch

# List remote branches
git branch -r

# List all branches (local and remote)
git branch -a

# Create a new branch
git branch feature-new-login

# Switch to an existing branch
git checkout main

# Create and switch to new branch in one command
git checkout -b feature-payment

# Modern way to switch branches (Git 2.23+)
git switch main
git switch -c feature-search  # Create and switch

# Safely delete a branch (only if merged)
git branch -d old-feature

# Force delete a branch (even if not merged)
git branch -D experimental-feature

# Delete a remote branch
git push origin --delete remote-branch-name

# Add a remote repository
git remote add origin https://github.com/user/repo.git

# View configured remote repositories
git remote -v

# Show more details about a remote
git remote show origin

# Push local commits to remote repository
git push origin main

# Push and set upstream tracking (for first push)
git push -u origin feature-branch

# Pull latest changes from remote
git pull origin main

# Download changes without merging
git fetch origin

# Pull with rebase instead of merge (cleaner history)
git pull --rebase origin main
