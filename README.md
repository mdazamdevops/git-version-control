# GIT VERSION-CONTROLLED DEVOPS PROJECT

## Project Overview
This project demonstrates the use of Git for version control in a DevOps environment.  
It follows **branching strategies**, **proper commit practices**, and **pull request workflows** to ensure smooth collaboration.

The project is designed for:
- Learning Git best practices
- Practicing branching workflows
- Integrating DevOps version control in real projects

---

## 🛠 Tools & Technologies
- Git & GitHub
- Linux Bash
- DevOps Workflow

---

## Git Workflow

# 1. Clone the repository
git clone https://github.com/mdazamdevops/git-version-control.git
cd <repo-name>

# 2. Create branches
git checkout -b dev        # Development branch
git checkout -b feature/ui # Feature branch
git checkout -b main       # Main branch (production-ready)

# 3. Make changes
nano <file-name>           # Edit your file
git add <file-name>
git commit -m "Add new feature"

# 4. Push changes
git push origin <branch-name>

# 5. Pull Request
#   - Open PR from feature -> dev
#   - Review & approve changes
#   - Merge into dev, then main

---

## Branching Strategy
- **main** → Production-ready code
- **dev** → Staging / testing code
- **feature/*** → New features or bug fixes

---

## Commit Message Rules
- Use **present tense** → `"Add login page"`, not `"Added login page"`
- Keep commits **focused** on one change
- Avoid vague messages like `"update file"`

---

## Why Git in DevOps?

Git is essential in DevOps because it:
- Tracks changes to code
- Allows collaboration between team members
- Supports CI/CD workflows
- Enables rollback to previous stable versions
- Maintains project history

---

## Useful Git Commands

# Check status of repo
git status

# View branches
git branch

# Switch branch
git checkout <branch-name>

# Merge branch into current branch
git merge <branch-name>

# Pull latest changes
git pull origin <branch-name>

# Delete branch locally
git branch -d <branch-name>

# Delete branch remotely
git push origin --delete <branch-name>

---

## Author
Name: Mohd Azam Uddin  
Role: DevOps Intern & Developer  
GitHub: https://github.com/mdazamdevops  
