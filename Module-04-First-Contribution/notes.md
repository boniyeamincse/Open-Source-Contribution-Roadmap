# Module 4 Notes: The First Contribution Workflow

Making a contribution is a sequence of technical steps. Follow this "Standard Workflow" used by developers around the world.

---

## 🛠️ Step 1: Fork and Clone
1.  **Fork**: Click the "Fork" button on the project's GitHub page. This creates a copy of the project in *your* GitHub account.
2.  **Clone**: Copy the URL of *your fork* and run:
    ```bash
    git clone https://github.com/your-username/project-name.git
    cd project-name
    ```

---

## 🏗️ Step 2: Set Up and Branch
1.  **Install dependencies**: Follow the instructions in `CONTRIBUTING.md`.
2.  **Create a branch**: Never work directly on `main`.
    ```bash
    git checkout -b fix/issue-description
    ```

---

## ✍️ Step 3: Code and Commit
1.  **Verify the issue**: Make sure you can reproduce the bug or understand the feature request.
2.  **Write the code**: Follow the project's style guide.
3.  **Test**: Ensure your changes don't break existing features.
4.  **Commit**:
    ```bash
    git add .
    git commit -m "fix: resolve typo in installation guide"
    ```

---

## 📤 Step 4: Push and Pull Request (PR)
1.  **Push**:
    ```bash
    git push origin fix/issue-description
    ```
2.  **Open PR**: Go to the original project's GitHub page. You'll see a big button: "Compare & pull request". Click it!
3.  **Describe your changes**: Explain *what* you did and *why*. Reference the issue number (e.g., "Fixes #42").

---

## 🤝 Step 5: Code Review and Merge
The maintainer will look at your code. They might ask for changes:
1.  Make the changes in your local branch.
2.  Commit and push again. The PR updates automatically.
3.  Once the maintainer is happy, they will **Merge** your PR.

---

## 💡 Summary
You did it! Your code is now part of a real project. Remember, the goal of a PR is to make the software better, not just to "get your points".

---

---
[⬅️ Back to Module Index](./README.md) | [➡️ Next: PR Examples](./examples.md)

---
Author: Boni Yeamin  
Email: [boniyeamin.cse@gmail.com](mailto:boniyeamin.cse@gmail.com)  
LinkedIn: [https://www.linkedin.com/in/boniyeamin1/](https://www.linkedin.com/in/boniyeamin1/)
