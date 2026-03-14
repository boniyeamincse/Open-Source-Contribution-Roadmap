# Module 2 Lab: My First Local Repository

In this lab, you will practice using Git on your own machine. We will create a project, make some changes, and "time travel" through our commits.

## 🏗️ Objectives
1.  Initialize a Git repository.
2.  Make commits.
3.  Practice branching.

## 🛠️ Step-by-Step Instructions

### Step 1: Create a Project Folder
Open your terminal and run:
```bash
mkdir my-first-repo
cd my-first-repo
```

### Step 2: Initialize Git
```bash
git init
```
This creates a hidden `.git` folder that tracks your changes.

### Step 3: Create a File and Commit It
1.  Create a file: `echo "Hello Git" > hello.txt`
2.  Check status: `git status`
3.  Add it: `git add hello.txt`
4.  Commit it: `git commit -m "initial commit: add hello.txt"`

### Step 4: Create a Branch
```bash
git checkout -b feature-update
```

### Step 5: Make Changes on the Branch
1.  Modify the file: `echo "Updating the file..." >> hello.txt`
2.  Add and commit:
```bash
git add hello.txt
git commit -m "update: add some more text to hello.txt"
```

### Step 6: Verify History
Run `git log --oneline` to see your two snapshots!

---

## ✅ Deliverable
Take a screenshot of your terminal after running `git log --oneline` and share it with a friend!

---
[⬅️ Back to Module Index](./README.md) | [➡️ Next: Knowledge Check](./self-test.md)

---
Author: Boni Yeamin  
Email: [boniyeamin.cse@gmail.com](mailto:boniyeamin.cse@gmail.com)  
LinkedIn: [https://www.linkedin.com/in/boniyeamin1/](https://www.linkedin.com/in/boniyeamin1/)
