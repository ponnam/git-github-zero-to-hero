# 📘 Git Day 07 – Git Add & Commit (Detailed Notes)

## 📌 Overview

In this session, we learn how Git tracks changes and how to save them permanently using:

- `git add`
- `git commit`
- `git commit -a`

These are the **core commands** used in daily Git workflows.

---

## 🧠 Git Workflow (Big Picture)

Working Directory  →  Staging Area  →  Repository  
            (edit) → (git add) → (git commit)

---

## 📂 1. Working Directory

- Where you create and modify files
- Git does NOT automatically track changes
- Files here are:
  - Untracked
  - Modified

---

## 📦 2. Staging Area (Index)

- Intermediate area before commit
- You select what changes to include
- Controlled using `git add`

---

## 🗃️ 3. Repository (.git)

- Stores committed history
- Each commit = snapshot of your project

---

# 🚀 Git ADD Command

## 📌 Purpose

Moves changes from **Working Directory → Staging Area**

## 🔹 Syntax

    git add <file>

## 🔹 Examples

    git add file1.txt
    git add file2.txt

---

## 🔹 Add All Files

    git add .

✔ Adds:
- New files  
- Modified files  

---

## 🔹 Add Specific Types

    git add *.txt

---

## 🔍 Check Status

    git status

Shows:
- Untracked files  
- Staged files  
- Modified files  

---

## ⚠️ Important Notes

- `git add` does NOT save permanently  
- It only prepares changes for commit  
- You can stage partial changes  

---

# 💾 Git COMMIT Command

## 📌 Purpose

Saves staged changes into the repository permanently

---

## 🔹 Syntax

    git commit -m "your message"

---

## 🔹 Example

    git commit -m "Added login feature"

---

## 🧠 What Happens?

- Git creates a snapshot  
- Assigns a unique commit ID (hash)  
- Stores author, date, message  

---

## 📝 Commit Message Best Practices

✔ Good:

- Fix bug in payment module  
- Add user authentication  
- Update README documentation  
- TASK Number

❌ Bad:

- changes  
- update  
- done  


---

# ⚡ Git COMMIT -a

## 📌 Purpose

Shortcut to:
- Stage (ONLY tracked files)  
- Commit in one step  

---

## 🔹 Syntax

    git commit -a -m "message"

---

## 🔹 Example

    git commit -a -m "Updated existing files"

---

## ⚠️ Important Limitation

❌ Does NOT include:
- New (untracked) files  

✔ Only works for:
- Already tracked files  

---

## 🧠 Behind the Scenes

Equivalent to:

    git add <tracked-files>
    git commit -m "message"

---

# 🔥 Comparison Table

| Feature             | git add        | git commit      | git commit -a     |
|--------------------|---------------|----------------|------------------|
| Moves to staging   | ✅ Yes         | ❌ No           | ✅ Auto (tracked) |
| Saves permanently  | ❌ No          | ✅ Yes          | ✅ Yes            |
| Includes new files | ✅ Yes         | ❌ Only staged  | ❌ No             |
| Requires message   | ❌ No          | ✅ Yes          | ✅ Yes            |

---


# 🎯 Key Takeaways

- `git add` → Prepares changes  
- `git commit` → Saves changes  
- `git commit -a` → Shortcut (tracked files only)  

---

# ❓ Interview Questions

1. What is the difference between staging and committing?  
2. Why do we need `git add`?  
3. What happens if we skip staging?  
4. Difference between `git commit` and `git commit -a`?  
5. Can `git commit -a` add new files?  

---

# 📚 Summary

- Git works in 3 stages  
- Staging gives control over commits  
- Commit creates project history  
- `-a` is a shortcut but limited  


---

## 🤝 Connect with Me

If you have any questions, feedback, or need help, feel free to reach out:

- 📧 Email: Ponnam.phani@gmail.com  
- 💬 Telegram : @phani_ponnam  

📢 Join Telegram for more updates and content:  
https://t.me/thecloudlearn  

I’d be happy to help you 😊