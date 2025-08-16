# DevOps Internship Task 4 – Build a Version-Controlled DevOps Project with Git

# Elevate Labs: Empowering the Future of DevOps
* This project is a testament to the high-quality, hands-on learning experience provided by Elevate Labs. Their internship program is dedicated to empowering the next generation of DevOps professionals by offering practical, real-world challenges that build foundational skills and a deep understanding of modern software development practices.
## Overview

* The objective of this task is to manage a DevOps project using Git best practices. This includes setting up a proper Git repository with a branching strategy, using pull requests for code reviews, and documenting the process in a well-structured README.md file. The goal is to learn version control workflows that are essential in collaborative development environments.

# Objective

* Manage a DevOps project using Git best practices.
* Utilize proper commits and branching.
* Document all tasks using Markdown.
---
## Tools & Technologies
* Git – The core version control system used for tracking changes in the project.

* GitHub – The web-based hosting service for Git repositories, enabling collaboration and project management.

 ## Step-by-Step Implementation

This section outlines the detailed steps followed to complete the task:
Repository Initialization:

* A new Git repository was initialized locally using git init.
* The project files were added and the first commit was made with a clear, descriptive message.

* The local repository was then pushed to a new remote repository on GitHub.

Branching Strategy:

* A main branch was designated for production-ready code.

* A dev branch was created from main to serve as the integration branch for all new features.

* A feature branch was created from dev for developing new features in isolation.

### Collaborative Workflow with Pull Requests:

All new features and changes were developed on the feature branch.
* Once a feature was complete, a pull request was opened from the feature branch to the dev branch.
* The pull request served as an opportunity for code review before the changes were merged.
### Configuration and Documentation:

* A .gitignore file was added to prevent unnecessary files (like node_modules or .DS_Store) from being committed to the repository.

* Git tags were used to mark specific points in the project history, such as release versions.
* All tasks and the project's setup were documented in a README.md file using Markdown.

Project Structure
```
.
├── .gitignore
├── .github/
│   └── pull_request_template.md  # Optional, but a good practice
├── README.md
├── [project_files_here]
└── [project_directories_here]
```
## Learning Outcomes
### By completing this task, you will:

* Understand fundamental Git commands and workflows.
* Learn how to implement a standard branching strategy (e.g., Git Flow or GitHub Flow).
* Gain experience using pull requests for code collaboration.
* Learn to use .gitignore and tags to maintain a clean and well-organized repository.

## Interview Questions to Practice

### 1.What is Git?

### 2. What is the difference between merge and rebase?

### 3.What is a pull request?

### 4. How do you resolve merge conflicts?

### 5. What are Git tags?

### 6. What is Git workflow?

### 7. Explain git stash.

### 8.What is the use of .gitignore?

## Creator
Name: Mohd Azam Uddin
Role: DevOps Intern

* Contribution: Managed a DevOps project using Git best practices, including a comprehensive branching strategy and proper documentation.
