# Git Setup

## i. What is Version Control?

Version control is a system that helps track changes to files over time. It allows multiple people to work on the same project, keeps a history of every change made, and enables reverting to previous versions if necessary.

## ii. Importance of Version Control

- **Collaboration**: Multiple developers can work on the same codebase without conflict.
- **History**: You can see who made what changes and when.
- **Backup**: It acts as a backup by keeping past versions.
- **Experimentation**: You can test new features safely without affecting the main code.

## iii. What is Git?

Git is a distributed version control system used to manage and track changes in source code. It is fast, efficient, and allows developers to work both offline and online.

## iv. What is GitHub?

GitHub is a cloud-based platform that hosts Git repositories. It provides tools for collaboration, issue tracking, pull requests, and code review.

## v. Difference Between Git and GitHub

| Git | GitHub |
|-----|--------|
| A version control tool installed locally. | An online platform for hosting and managing Git repositories. |
| Used via command line or GUI tools. | Used through a web interface or Git commands. |
| Does not require internet access. | Requires internet to interact with repositories online. |

## vi. Git and GitHub Setup for Beginners

1. **Install Git**  
   - Download from [https://git-scm.com](https://git-scm.com)  
   - Install and configure:
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "you@example.com"
     ```

2. **Create a GitHub Account**  
   - Visit [https://github.com](https://github.com) and sign up.

3. **Create a Local Repository**  
   ```bash
   mkdir git-setup
   cd git-setup
   git init
