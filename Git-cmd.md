# Set your global username and email (required for commits)
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Set default branch name to 'main' (modern standard)
git config --global init.defaultBranch main

# View all configuration settings
git config --list

# View specific configuration
git config user.name


# Initialize a new Git repository in current directory
git init

# Clone an existing repository from a remote URL
git clone https://github.com/user/repo.git

# Clone a specific branch only
git clone -b develop https://github.com/user/repo.git

# Show the working tree status - what's staged, unstaged, and untracked
git status

# Compact status display
git status -s

# Stage a specific file
git add filename.txt

# Stage all changes in current directory and subdirectories
git add .

# Stage all changes including file deletions
git add -A

# Stage only modified and deleted files, not new files
git add -u

# Commit staged changes with a descriptive message
git commit -m "Add user authentication feature"

# Add all tracked file changes and commit in one step
git commit -am "Fix login bug"

# Amend the most recent commit (change message or add forgotten files)
git commit --amend -m "New commit message"
