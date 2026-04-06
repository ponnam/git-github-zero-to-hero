# 📘 Day 07 – Git Add & Commit

## Task 1: Check the status of the Repository

```bash
git status
```

## 📄 Task 2: Create a File

```bash
echo "Hello Git" > file1.txt
```

### Task 2.1: Check status again:

```bash
git status
```

👉 You should see:

* `file1.txt` under **Untracked files**

---

## 📥 Task 3: Add File to Staging

```bash
git add file.txt
```

### Task 3.1: Check status again:

```bash
git status
```

👉 Now file is in:

* **Staged changes**

---

## 💾 Task 4: Commit the File

```bash
git commit -m "First commit"
```

### Task 4.1: Check status

```bash
git status
```

👉 Working tree should be clean

---

## Task 5: Modify the file1.tx with some content

``` bash
echo "Modified the File by me" >> file1.txt
```

### Task 5.1: Check the status

```bash
git status
```

## Task 6: Commit the file without staging

```bash
git commit -a -m "Commiting the file without staging"
```

### Task 6.1: Check the status 
```bash
git status
```

---

## 🤝 Connect with Me

If you have any questions, feedback, or need help, feel free to reach out:

- 📧 Email: Ponnam.phani@gmail.com  
- 💬 Telegram : @phani_ponnam  

📢 Join Telegram for more updates and content:  
https://t.me/thecloudlearn  

I’d be happy to help you 😊