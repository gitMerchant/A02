# How to Use GIT and Github  
### IS117 Tutorial

## Introduction

This guide explains how to use **GIT** and **Github** to manage and track changes in your projects. You’ll learn how to create a repository, clone it, commit changes, push updates, and work with branches.

---

## What is **GIT**?

**GIT** is a version control system that tracks changes in your files (Git, n.d.).

## What is **Github**?

**Github** is a website that hosts your **Repository** online so you can store and share your code (GitHub Docs, n.d.).

---

## Basic Workflow

### 1️⃣ Create a **Repository**
- Log into GitHub
- Click “New Repository”
- Name it and create it

Commit example:
Task: Create Repository

---

### 2️⃣ **Clone** the Repository

**Clone** means copying the project to your computer.

git clone https://github.com/username/repository-name.git

This connects your project to the **Remote** (the online version).

---

### 3️⃣ Make Changes and **Commit**

A **Commit** saves your changes.

git add .  
git commit -m "Feature: added workflow for using github"

Good commit message examples:
- Task: Create Repository  
- Feature: added workflow for using github  
- Fix: changed readme.md for definition of terms  

---

### 4️⃣ **Push** Your Work

**Push** uploads your commits to GitHub.

git push origin main

---

### 5️⃣ **Pull** or **Fetch** Updates

**Fetch** downloads updates without merging:
git fetch  

**Pull** downloads and merges updates:
git pull origin main  

---

### 6️⃣ Use a **Branch**

A **Branch** lets you work separately from the main version.

git checkout -b feature-branch  

To combine work, use **Merge**:

git checkout main  
git merge feature-branch  

If changes overlap, a **Merge Conflict** happens. A **Merge Conflict** means Git needs you to manually choose which changes to keep.

---

## Glossary

- **Branch** – A separate line of development.  
- **Clone** – Copying a repository to your computer.  
- **Commit** – A saved snapshot of changes.  
- **Fetch** – Downloads changes without merging.  
- **GIT** – A version control system.  
- **Github** – A platform that hosts Git repositories.  
- **Merge** – Combines changes from branches.  
- **Merge Conflict** – When Git can’t automatically merge changes.  
- **Push** – Uploads changes to GitHub.  
- **Pull** – Downloads and merges changes.  
- **Remote** – The online version of your repository.  
- **Repository** – A project folder with tracked files.

---

## References

Git. (n.d.). Git documentation. https://git-scm.com/docs  

GitHub Docs. (n.d.). About GitHub and Git. https://docs.github.com/en/get-started  
