# TASKS

This file lists all the tasks to be performed for building and managing the Version-Controlled DevOps Project using Git.

---

## 1. Initialize Git Repository

# Create a new local repository
git init

# Add remote origin
git remote add origin <repository_URL>

# Verify remote
git remote -v

# Create and switch to main branch
git checkout -b main

# Create development branch
git checkout -b dev

# Create a new feature branch
git checkout -b feature/<feature_name>

# Stage all changes
git add .

# Stage specific file
git add <filename>

# Commit changes with a message
git commit -m "Meaningful commit message"

# Switch to main branch
git checkout main

# Merge development branch into main
git merge dev

# Merge feature branch into dev
git merge feature/<feature_name>


# Pull latest changes from remote
git pull origin main

# Pull for development branch
git pull origin dev

# View detailed commit logs
git log

# View one-line commit summary
git log --oneline

# Delete local branch
git branch -d <branch_name>

# Delete remote branch
git push origin --delete <branch_name>

# View help for any command
git help <command>

# View help for any command
git help <command>