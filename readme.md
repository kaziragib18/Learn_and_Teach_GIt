# 🧾 Git Cheat Sheet

This is a quick reference guide for commonly used Git commands. Ideal for beginners and experienced developers who need a handy reminder.

---

## 📁 Repository Management

- `git init`  
  Initializes a new Git repository in the current directory.

- `git clone <repository_url>`  
  Copies a remote repository to your local machine.

---

## 📄 Working with Changes

- `git status`  
  Shows the current state of the working directory and staging area.

- `git add <file>`  
  Stages changes in a specific file for the next commit.

- `git add .`  
  Stages all changes in the current directory.

- `git commit -m "commit message"`  
  Saves staged changes with a descriptive message.

- `git diff`  
  Displays differences between files or commits.

- `git reset <file>`  
  Unstages a file from the staging area.

- `git reset --hard`  
  Resets the working directory and staging area to the last commit.

- `git rm <file>`  
  Removes a file from the working directory and staging area.

---

## 🔀 Branching & Merging

- `git branch`  
  Lists all local branches.

- `git branch <branch_name>`  
  Creates a new branch.

- `git checkout <branch_name>`  
  Switches to another branch.

- `git checkout -b <new_branch>`  
  Creates and switches to a new branch.

- `git merge <branch_name>`  
  Combines changes from another branch into the current branch.

---

## 🔄 Remote Repositories

- `git push`  
  Uploads local commits to a remote repository.

- `git pull`  
  Fetches and merges changes from a remote repository.

- `git fetch`  
  Downloads changes from a remote repository without merging.

- `git remote -v`  
  Lists remote repositories and their URLs.

- `git remote add <name> <url>`  
  Adds a new remote repository.

---

## 💾 Stashing

- `git stash`  
  Temporarily saves changes not yet committed.

- `git stash apply`  
  Restores stashed changes.

---

## 🕒 History & Logs

- `git log`  
  Shows the commit history.

- `git show <commit>`  
  Shows details about a specific commit.

- `git reflog`  
  Shows a log of all reference updates.

---

## 🔍 Inspection & Debugging

- `git cherry-pick <commit>`  
  Applies changes from a specific commit to the current branch.

- `git revert <commit>`  
  Creates a new commit that undoes changes from a previous commit.

- `git blame <file>`  
  Shows who last modified each line of a file.

---

## 🏷️ Tags

- `git tag`  
  Lists tags in the repository.

- `git tag <tag_name>`  
  Creates a new tag.

---

## 🛠️ File Management

- `git mv <old> <new>`  
  Renames or moves a file.

---

## ⚙️ Configuration

- `git config --global user.name "Your Name"`  
  Sets your global Git username.

- `git config --global user.email "your.email@example.com"`  
  Sets your global Git email.

---

**Tip:** Use `git help <command>` for detailed documentation on any Git command.

---
