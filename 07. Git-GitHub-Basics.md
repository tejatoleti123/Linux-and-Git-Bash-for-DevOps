# Git & GitHub Guide: Installation, Concepts & Basics

## Quick Overview

**Git** is a distributed version control system that tracks changes to files locally.  
It allows you to:
- Track file history
- Revert to previous versions
- Work safely with branches

**GitHub** is a cloud-based platform that hosts Git repositories.  
It enables:
- Remote backup of code
- Team collaboration
- Pull requests, reviews, and CI/CD integration

In simple terms:
- Git runs on your machine
- GitHub runs on the internet

---

## Git Workflow (Four Areas)

Working Directory → Staging Area → Local Repository → Remote Repository (GitHub)

### Working Directory
- Your project files on disk
- Files can be:
  - Untracked (new)
  - Modified (changed but not staged)

`git status`  
Shows the current state of files.

---

### Staging Area
- Temporary area where changes are prepared for commit
- Gives control over what goes into the next commit

`git add file.txt`  
Stages a specific file.

`git add .`  
Stages all changes.

---

### Local Repository
- Stored inside the hidden `.git` directory
- Contains commit history and metadata

`git commit -m "commit message"`  
Creates a snapshot of staged changes.

---

### Remote Repository (GitHub)
- Hosted on GitHub servers
- Used for collaboration and backup

`git push origin main`  
Uploads local commits to GitHub.

`git pull origin main`  
Fetches and merges remote changes.

---

## Installation

### Windows

1. Download Git from https://git-scm.com
2. Run the installer and keep default options
3. Verify installation:

`git --version`

---

### Linux (Ubuntu / Debian)

`sudo apt update`  
`sudo apt install git -y`

---

### macOS

`brew install git`

---

## Initial Configuration (Required)

Configure user identity (stored in commits):

`git config --global user.name "Your Name"`  
`git config --global user.email "you@example.com"`

Verify configuration:

`git config --list`

---

## Local vs Remote Repository

| Aspect | Local Repo | Remote Repo |
|------|-----------|-------------|
| Location | Your system | GitHub |
| Internet | Not required | Required |
| Purpose | Development | Collaboration |

---

## Summary

- Git tracks changes locally
- GitHub hosts repositories remotely
- Staging provides precise control
- Commits form permanent project history
