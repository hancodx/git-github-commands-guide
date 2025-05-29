# 📘 Git & GitHub Commands Guide

This guide contains the most commonly used Git and GitHub commands to help you manage your development projects efficiently.

---

## 🔧 Initial Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

## 📁 Start a Git Project

```bash
git init                        # Initialize a Git repository
git clone REPO_URL             # Clone a remote repository
```


## 🔁 History and Changes

```bash
git log                        # Show commit history
git diff                       # View unstaged changes
git checkout filename          # Discard changes in a file
```

## 🌿 Branching

```bash
git branch                     # List branches
git branch branch_name         # Create a new branch
git checkout branch_name       # Switch to a branch
git checkout -b branch_name    # Create and switch to a branch
git merge branch_name          # Merge a branch
```

## 🚀 Push to GitHub

```bash
git remote add origin URL      # Link to a remote repository
git push -u origin main        # Push the main branch
git push                       # Push changes
git pull                       # Pull changes from the remote
```

##  🧼 Other Useful Commands
```bash
git stash                      # Temporarily save changes
git stash pop                  # Restore stashed changes
git reset --hard HEAD          # Undo all uncommitted changes
git rm filename                # Delete a tracked file
```
