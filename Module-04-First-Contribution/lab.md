# Module 4 Lab: The "Hello World" Contribution

In this lab, you will perform a simulated first contribution. Since we are working on this book locally, we will simulate the contribution process by making a change to this book itself!

## 🏗️ Objectives
1.  Navigate the Roadmap structure.
2.  Follow the commit convention.
3.  Simulate a Pull Request by creating a branch.

## 🛠️ Step-by-Step Instructions

### Step 1: Create a Contribution Branch
Open your terminal in the root of the `Open-Source-Contribution-Roadmap` folder and run:
```bash
git checkout -b contrib/add-my-name
```

### Step 2: Edit a File
Open `Module-04-First-Contribution/notes.md`. Scroll to the bottom and add a comment section:
```markdown
<!-- Contributed by: [Your Name] -->
```

### Step 3: Commit Your Change
```bash
git add Module-04-First-Contribution/notes.md
git commit -m "docs: add contributor name to module 4 notes"
```

### Step 4: Verify Your Branch
Run `git branch` to ensure you are still on `contrib/add-my-name`.

### Step 5: (Optional) Push to Your Fork
If you were working on a real GitHub project, this is where you would run:
`git push origin contrib/add-my-name`

---

## ✅ Deliverable
Write a short Pull Request description for this change. Use the template from [examples.md](./examples.md).

---
[⬅️ Back to Module Index](./README.md) | [➡️ Next: Knowledge Check](./self-test.md)

---
Author: Boni Yeamin  
Email: [boniyeamin.cse@gmail.com](mailto:boniyeamin.cse@gmail.com)  
LinkedIn: [https://www.linkedin.com/in/boniyeamin1/](https://www.linkedin.com/in/boniyeamin1/)
