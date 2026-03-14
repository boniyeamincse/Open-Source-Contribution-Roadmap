# Module 2 Notes: Git and Version Control

## 📁 What is Version Control?
Imagine you're writing a book. You save "Version 1". Then you edit it and save "Version 2". But then you realize "Version 1" was better. A **Version Control System (VCS)** manages these changes automatically, allowing you to go back in time, compare versions, and collaborate with others without overwriting their work.

**Git** is the most popular VCS in the world.

---

## 🛠️ The Core Git Commands
You only need a few commands to get started:

1.  **`git init`**: Start a new Git repository in your current folder.
2.  **`git status`**: Check which files Git is watching and if they have changes.
3.  **`git add <file>`**: Tell Git you want to include these changes in your next "snapshot" (staging).
4.  **`git commit -m "Your Message"`**: Take the snapshot and save it to the history with a description.
5.  **`git log`**: View the history of all the snapshots (commits) you've taken.

---

## 🌿 Branching: Working in Parallel
One of Git's best features is **Branches**.
-   The **main** branch is the official version of the code.
-   When you want to work on a new feature or fix a bug, you create a **feature branch**.
-   This allows you to work without breaking the "production" code.
-   Command: `git checkout -b feature-name`

---

## ☁️ Connecting to GitHub (Remote Repos)
GitHub is where the "Remote" version of your code lives.
-   **`git remote add origin <url>`**: Link your local folder to a GitHub repository.
-   **`git push origin <branch-name>`**: Send your local commits to the remote repository.
-   **`git pull`**: Download the latest changes from the remote repository to your local machine.

---

## 💡 Summary
Git tracks *what* changed, *when* it changed, and *why* it changed. Mastering these commands is like learning to use a hammer and nails for building software.

---

---
[⬅️ Back to Module Index](./README.md) | [➡️ Next: Git Examples](./examples.md)

---
Author: Boni Yeamin  
Email: [boniyeamin.cse@gmail.com](mailto:boniyeamin.cse@gmail.com)  
LinkedIn: [https://www.linkedin.com/in/boniyeamin1/](https://www.linkedin.com/in/boniyeamin1/)
