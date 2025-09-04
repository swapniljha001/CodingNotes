# Git Study
This is not an exhaustive list of Git commands, this is an intro to the **Git Flow**. This is basic stuff. There are lots of lists of commands on the internet.

### Summary
These are the most commonly used commands.

```
# Clone the repo (default branch = main)
git clone repo_URL

# Go inside the repo
cd repo_folder

# Create and switch to your development branch
git checkout -b dev-branch

# Configure your Git identity (done once per repo, or globally with --global)
git config user.email "username@example.com"
git config user.name "Your Name"

* Make changes here *

# Stage all changes
git add .

# Commit with a message
git commit -m "Commit Message"

# Push your dev branch to GitHub
git push origin dev-branch
```
