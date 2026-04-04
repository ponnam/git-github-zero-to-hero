# 🧪 Day 06 – Hands-on: Git Repository & Internals

---

# 🎯 Objective

In this lab, you will:

* Create your first Git repository
* Initialize Git using `git init`
* Check repository status using `git status`
* Explore `.git` internal structure
* Understand objects, refs, and HEAD practically
* Create a `README.md` file

---

# 🛠️ Step 1: Create Project Directory

```bash
mkdir git-day06-lab
cd git-day06-lab
```

---
# 🛠️ Step 1.1: Check the Status of the Directory

```bash
git status
```

---


# ⚙️ Step 2: Initialize Git Repository

```bash
git init
```

👉 Observe output:

```bash
Initialized empty Git repository
```

---

# 🔍 Step 3: Verify `.git` Folder

```bash
ls -la
```

👉 You should see:

```bash
.git
```

---

# 📊 Step 4: Check Git Status

```bash
git status
```

👉 Observe:

* Current branch name
* No commits yet
* No tracked files

---


# 🧠 Step 5: Explore `.git` Folder

```bash
ls .git
```

👉 Observe important folders:

* objects
* refs
* HEAD

---

# 📦 Step 9: Inspect Objects

```bash
ls .git/objects
```

👉 You will see multiple folders (hash-based)

---


# 🌿 Step 10: Check Branch Reference

```bash
cat .git/refs/heads/main
```

👉 Shows latest commit hash

---

# 🧭 Step 11: Check HEAD

```bash
cat .git/HEAD
```

👉 Output:

```bash
ref: refs/heads/main
```

---


# 📄 Step 12: Create README.md

```bash
touch README.md
```

Add content:

```bash
echo "# Git Day 06 Lab" >> README.md
```

---

# 📥 Step 15: Commit README

```bash
git add README.md
git commit -m "Added README file"
```

---

# 🎯 Expected Outcome

By the end of this lab, you should:

* Understand how Git initializes a repository
* Know how to check repository status
* Explore `.git` internals
* Understand objects, refs, and HEAD
* Create and commit a README file

---

# 🚀 Bonus Practice

* Modify `file.txt` and check status
* Create another commit
* Explore new objects in `.git/objects`
* Use `git log` to track history

---

## 🤝 Connect with Me

If you have any questions, feedback, or need help, feel free to reach out:

- 📧 Email: Ponnam.phani@gmail.com  
- 💬 Telegram : @phani_ponnam  

📢 Join Telegram for more updates and content:  
https://t.me/thecloudlearn  

I’d be happy to connect and help you 😊
