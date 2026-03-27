# 🧪 Day 02 - Hands-on Lab (Git Basics Setup)

In this hands-on session, we will:
- Install Git
- Verify installation
- Configure Git
- Understand basic Git configuration commands

---

## 🖥️ Task 1: Install Git on Windows

### Steps:

1. Go to the official Git website:  
   https://git-scm.com/install/windows

2. Download the installer

3. Run the setup and follow default options:
   - Click **Next → Next → Next**
   - Keep default settings

4. Click **Install**

---

## ✅ Task 2: Check Git Version

After installation, open:

- Command Prompt / PowerShell / Git Bash

Run:

```bash
git --version
```
### Expected Output:

```bash
git version 2.x.x.xxx
```

---

## ⚙️ Task 3: View Git Configuration

To view current Git configuration:

```bash
git config --list
```

---

## 🌍 Task 4: View Global Git Configuration

To check global configuration:

```bash
git config --global --list
```


---

## ✏️ Task 5: Configure Username and Email

Set your Git identity:

```bash
git config --global user.name 'Your Name'
git config --global user.email 'youremail@example.com'
```


---

## 🔍 Task 6: Verify Configuration

Check if updates are applied:

```bash
git config --list
```


---

## 🐧 Task 7: Install Git on Linux

### For RHEL/Amazon Linux / Fedora:
```bash
sudo yum update -y
sudo yum install git -y
```

### Verify Installation:
```bash
git --version
```


---

# 🎯 Summary

In this lab, you have learned:

- How to install Git (Windows & Linux)
- How to verify Git installation
- How to view Git configurations
- How to set username and email

---

Stay consistent and keep practicing! 💪

---

---

## 🤝 Connect with Me

If you have any questions, feedback, or need help, feel free to reach out:

- 📧 Email: Ponnam.phani@gmail.com  
- 💬 Telegram (Personal): @phani_ponnam  

📢 Join Telegram for more updates and content:  
https://t.me/thecloudlearn  

I’d be happy to connect and help you 😊
