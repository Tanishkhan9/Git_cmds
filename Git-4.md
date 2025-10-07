# Push changes to remote
git push origin <branch-name>

# Push all branches
git push --all origin

# Pull latest changes
git pull origin <branch-name>

# Fetch all updates (without merging)
git fetch origin


# View commit history
git log

# View history in one line per commit
git log --oneline

# View commits by a specific author
git log --author="Your Name"

# Show file changes between commits
git diff

# Show difference between working directory and last commit
git diff HEAD


# List all tags
git tag

# Create a tag
git tag <tag-name>

# Annotate a tag with a message
git tag -a <tag-name> -m "Tag message"

# Push all tags to remote
git push origin --tags


# Save current changes temporarily
git stash

# List all stashes
git stash list

# Apply latest stash
git stash apply

# Apply and remove stash
git stash pop

# Drop a specific stash
git stash drop <stash@{n}>


# Remove untracked files
git clean -f

# Remove untracked files and directories
git clean -fd



# Show current branch
git branch --show-current

# Show remote info
git remote show origin

# Show details of a commit
git show <commit-id>



# Add and commit in one command
git commit -am "message"

# Push to default remote branch
git push

# Pull and merge
git pull





# 1. Initialize repo
git init

# 2. Add remote
git remote add origin <url>

# 3. Add files
git add .

# 4. Commit changes
git commit -m "Initial commit"

# 5. Push to main branch
git push -u origin main