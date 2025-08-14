# Full Stack DevOps Project – Git Version Control

## Overview
This project demonstrates **version control best practices** using Git and GitHub in a DevOps environment.  
It contains a **Backend** (Python Flask) and **Frontend** (Node.js), each containerized using Docker.  
The repository is structured to follow proper branching strategies, tagging, and documentation.

---

## 🛠 Tech Stack
- **Backend:** Python Flask, Docker, `requirements.txt`
- **Frontend:** Node.js, HTML, CSS, JavaScript, Docker
- **Version Control:** Git, GitHub
- **Documentation:** Markdown (`README.md`, `CONTRIBUTING.md`, `CHANGELOG.md`)

---

## Project Structure
\`\`\`
├── .gitignore
├── backend
│   ├── app.py
│   ├── Dockerfile
│   └── requirements.txt
├── CHANGELOG.md
├── CONTRIBUTING.md
├── docs
│   └── tasks.md
├── frontend
│   ├── Dockerfile
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   └── server.js
└── README.md
\`\`\`

---

## Setup Instructions

### Clone the Repository

git clone <your_repo_url>
cd <repo_name>
\`\`\`

### Backend Setup
\`\`\`bash
cd backend
pip install -r requirements.txt
python app.py
\`\`\`

### Frontend Setup

cd frontend
npm install
node server.js
\`\`\`

---

## Branching Strategy
- **main** → Stable production-ready code
- **dev** → Active development branch
- **feature/*** → Individual features in separate branches

Example:

git checkout -b dev
git push -u origin dev

git checkout -b feature/frontend-ui
git push -u origin feature/frontend-ui
\`\`\`

---

## Git Workflow Steps
1. **Initialize repo & push to GitHub**

git init
git branch -M main
git add .
git commit -m "Initial commit - project setup"
git remote add origin <your_repo_url>
git push -u origin main
\`\`\`
2. **Create branches for development**
3. **Work on features in \`feature/\` branches**
4. **Push changes & open Pull Requests**
5. **Merge dev into main when stable**
6. **Add tags for releases**

git tag -a v1.0 -m "First stable release"
git push origin v1.0
\`\`\`

---

## .gitignore Example
\`\`\`
# Python
__pycache__/
*.pyc

# Node
node_modules/

# General
.env
\`\`\`


## Documentation Files
- **README.md** → Project details & setup guide
- **docs/tasks.md** → Tracks all tasks completed
- **CHANGELOG.md** → Lists project changes
- **CONTRIBUTING.md** → Contribution rules

