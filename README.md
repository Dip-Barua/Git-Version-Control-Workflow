# 🚀 Git Foundation & Commands (Quick Reference)

## 📌 Overview

Git is a distributed version control system that helps developers track changes in code, collaborate with others, and manage multiple versions of a project. Git is widely used in software development, especially in combination with GitHub for remote collaboration.



## 🛠️ Initial Setup

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## 📁 Starting a Repo

```bash
git init                            # Initialize new repo
git clone <url>                     # Clone remote repo
```

## 📄 Basic Workflow

```bash
git status                          # Show changes
git add .                           # Stage all changes
git commit -m "message"             # Commit staged changes
```

## 🔄 Remote Repo

```bash
git remote add origin <url>         # Link to GitHub
git push -u origin main             # Push first time
git push                            # Push changes
git pull origin main                # Pull latest
```

## 🌿 Branching

```bash
git branch                          # List branches
git checkout -b dev                 # New branch + switch
git checkout main                   # Switch back to main
git merge dev                       # Merge 'dev' into current branch
```

## 🔧 Logs & Diffs

```bash
git log --oneline                   # Short commit log
git diff                            # Show unstaged changes
```

## 🧹 Cleanups

```bash
git reset <file>                    # Unstage a file
git rm <file>                       # Remove tracked file
git stash                           # Save work temporarily
```

## ✅ Best Practice Summary

- Commit often, write clear messages.
- Use branches for features/fixes.
- Pull before pushing.
- Always review before merging.

## 📚 Docs

- https://git-scm.com/docs
- https://docs.github.com
