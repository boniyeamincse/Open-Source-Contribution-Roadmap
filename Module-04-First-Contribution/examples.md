# Module 4 Examples: Anatomy of a Great PR

A Pull Request is not just code; it's a proposal. Here is an example of a "Perfect PR" that a maintainer would love to merge.

## 📝 Example PR Description
**Title**: `fix: resolve broken link in ABOUT.md`

**Description**:
> ### 📋 Purpose
> While reading the `ABOUT.md` file, I noticed that the link to the Contribution Guide was broken due to a typo in the path.
> 
> ### 🛠️ Changes
> - Fixed the relative path from `../contrib` to `./contribution-guide/CONTRIBUTING.md`.
> 
> ### ✅ Verification
> - Clicked the link locally in VS Code preview and it works.
> - Verified file path exists in the repository tree.
> 
> Fixes #12

---

## 💬 The Code Review Conversation
**Maintainer**: "Thanks for this! Could you also check if any other files in that directory have a similar broken link?"
**You**: "Sure! I checked `LEARNING_OBJECTIVES.md` and found one more. I've updated this PR with a second commit."
**Maintainer**: "Great, looks perfect now. Merging!"

## ❌ PR Mistakes to Avoid
- **The "Mystery" PR**: No title, no description. (Maintainers won't open it).
- **The "Kitchen Sink" PR**: Fixing 10 unrelated bugs in one PR. (Hard to review).
- **The "Unfavorable" PR**: Changing the code style of the whole project because you personally prefer it.

---
[⬅️ Back to Module Index](./README.md) | [➡️ Next: First Contribution Lab](./lab.md)

---
Author: Boni Yeamin  
Email: [boniyeamin.cse@gmail.com](mailto:boniyeamin.cse@gmail.com)  
LinkedIn: [https://www.linkedin.com/in/boniyeamin1/](https://www.linkedin.com/in/boniyeamin1/)
