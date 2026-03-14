# Step 4: Essential Git Fundamentals

Git is your "Time Machine" for code. Here are the only commands you need to survive.

## 🚀 The Core Workflow
1.  **`git status`**: See what changed.
2.  **`git add .`**: Prepare all changes for a snapshot.
3.  **`git commit -m "Your Message"`**: Save the snapshot with a meaningful description.
4.  **`git push origin branch-name`**: Send the snapshot to GitHub.

## 🌿 The Rule of Branching
NEVER work directly on the `main` branch. Always create a new branch for your task:
```bash
git checkout -b fix-typo-in-readme
```

## 📝 Writing Good Commit Messages
Bad: `git commit -m "fixed stuff"`  
Good: `git commit -m "fix: correct spelling error in module intro"`

---
[⬅️ Previous Step: Setting Up Tools](./03_Setting_Up_Git_and_GitHub.md) | [➡️ Next Step: Navigating Open Source Projects](./05_Navigating_Open_Source_Projects.md)

---
Author: Boni Yeamin  
Email: [boniyeamin.cse@gmail.com](mailto:boniyeamin.cse@gmail.com)  
LinkedIn: [https://www.linkedin.com/in/boniyeamin1/](https://www.linkedin.com/in/boniyeamin1/)
