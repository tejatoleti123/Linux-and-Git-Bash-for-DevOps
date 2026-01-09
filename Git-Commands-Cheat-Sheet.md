# Git Commands Cheat Sheet

## Repository Setup

`git init`  
Initializes a new Git repository.

`git clone <repo-url>`  
Creates a local copy of a remote repository.

---

## File Status & Tracking

`git status`  
Shows modified, staged, and untracked files.

`git add file.txt`  
Stages a specific file.

`git add .`  
Stages all changes.

---

## Committing Changes

`git commit -m "message"`  
Creates a commit with a message.

`git commit -am "message"`  
Stages and commits tracked files only.

---

## Viewing History

`git log`  
Shows detailed commit history.

`git log --oneline`  
Shows compact commit history.

---

## Branching

`git branch`  
Lists branches.

`git branch feature-x`  
Creates a new branch.

`git switch feature-x`  
Switches to a branch.

`git switch -c feature-x`  
Creates and switches to a new branch.

---

## Merging

`git merge branch-name`  
Merges a branch into the current branch.

---

## Remote Operations

`git remote -v`  
Lists remote repositories.

`git fetch`  
Downloads changes without merging.

`git pull`  
Fetches and merges changes.

`git push`  
Uploads commits to remote repo.

---

## Undo & Fix

`git restore file.txt`  
Discards local changes to a file.

`git reset --soft HEAD~1`  
Undo last commit but keep changes staged.

`git reset --hard HEAD~1`  
Completely removes last commit (destructive).
