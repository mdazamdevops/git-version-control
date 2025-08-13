# CONTRIBUTING GUIDELINES

Thank you for your interest in contributing to this project.  
Please follow the guidelines below to ensure smooth collaboration.

## 1. Setting Up the Project Locally

# Clone the repository
git clone https://github.com/mdazamdevops/git-version-control.git

# Navigate into the project directory
cd <repo-name>

# Create and switch to a new branch for your work
git checkout -b <your-feature-branch>

## 2. Branch Naming Convention

# Branch names should be descriptive:
# Examples:
#   feature/login-page
#   bugfix/header-alignment
#   docs/update-readme

## 3. Making Changes

# Stage your changes
git add <file-name>

# Commit with a meaningful message
git commit -m "Description of the change"

# Push your branch to GitHub
git push origin <your-feature-branch>

## 4. Submitting a Pull Request (PR)

# Go to the GitHub repository page
# Open a new Pull Request from your branch to the 'dev' branch
# Ensure your PR description explains:
# - The problem you solved
# - Changes made
# - Any dependencies or breaking changes

## 5. Code Review Process

# All changes must be reviewed before merging
# Maintain clean and readable code
# Follow the project's coding standards

## 6. Documentation

# Update README.md and other docs if you add new features
# Keep documentation clear and concise

## 7. Git Commit Guidelines

# Use present tense in commit messages (e.g., "Add new API route" not "Added...")
# Keep commits focused—avoid mixing unrelated changes

## 8. Git Commands Reference

# Clone repo
git clone <repo-url>

# Create branch
git checkout -b <branch-name>

# Switch branch
git checkout <branch-name>

# Stage changes
git add <file-name>

# Commit changes
git commit -m "message"

# Push branch
git push origin <branch-name>

# Pull latest changes
git pull origin <branch-name>

# Merge branch
git merge <branch-name>

# Delete branch locally
git branch -d <branch-name>

# Delete branch remotely
git push origin --delete <branch-name>
