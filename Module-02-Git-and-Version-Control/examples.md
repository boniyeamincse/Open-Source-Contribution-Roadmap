# Module 2 Examples: Git in Practice

Here are common scenarios you'll encounter while using Git in the real world of open source.

## 📝 Writing Good Commit Messages
A commit message tells your teammates (and your future self) why you made a change.

**❌ Bad Messages:**
- "Fixed it"
- "Update README"
- "Adding stuff"

**✅ Good Messages:**
- "docs: add installation steps for Linux"
- "fix: resolve navigation bar bug on mobile views"
- "feat: implement user login with GitHub OAuth"

## 🌲 Example Branching Workflow
1.  **Main Branch**: The code everyone sees.
2.  **Fixing a typo**: You create a branch called `fix-typo-readme`.
3.  **Adding a feature**: Someone else creates a branch called `add-dark-mode`.
4.  Both of you work independently, and eventually, the maintainer merges both into `main`.

## 🔄 The "Dirty" Working Directory
What happens if you're halfway through a feature but need to switch tasks?
- **`git stash`**: Temporarily "stashes" your uncommitted changes so you have a clean folder.
- **`git stash pop`**: Brings those changes back later.

---
[⬅️ Back to Module Index](./README.md) | [➡️ Next: Local Repo Lab](./lab.md)

---
Author: Boni Yeamin  
Email: [boniyeamin.cse@gmail.com](mailto:boniyeamin.cse@gmail.com)  
LinkedIn: [https://www.linkedin.com/in/boniyeamin1/](https://www.linkedin.com/in/boniyeamin1/)
