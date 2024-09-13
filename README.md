# version_control
Jomacs Devops Training (July-December 2024)
# GitHub Basics

GitHub is a web-based platform that uses Git for version control. It allows developers to collaborate on projects, track changes, and manage code repositories. Here's a basic guide to get you started.

## Key Concepts

### Repository (Repo)
A repository is a storage location for your project. It contains all the project files and the history of changes.

### Branch
A branch is a parallel version of the repository. By default, GitHub creates a `main` branch, but you can create other branches to work on different features or fixes.

### Commit
A commit is a snapshot of your repository at a specific point in time. It records changes made to the files and includes a commit message describing those changes.

### Pull Request (PR)
A pull request is a request to merge changes from one branch into another. It's a way to review code and discuss modifications before integrating them into the main branch.

### Fork
A fork is a copy of a repository that allows you to freely experiment with changes without affecting the original project.

### Clone
Cloning a repository creates a local copy of the repository on your machine, allowing you to work on it offline.

## Basic Commands

Here are some basic Git commands commonly used with GitHub:

```sh
# Clone a repository
git clone https://github.com/username/repository.git

# Create a new branch
git branch new-branch-name

# Switch to a branch
git checkout branch-name

# Add changes to the staging area
git add file-name

# Commit changes with a message
git commit -m "Your commit message"

# Push changes to GitHub
git push origin branch-name

# Pull changes from GitHub
git pull origin branch-name

