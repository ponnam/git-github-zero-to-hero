# Day 10: Git Rename & Remove - git rm & git mv

## 🎯 Learning Objectives
- Understand how to rename files in Git  
- Learn how to remove files from Git  
- Differentiate between working directory and Git tracking  
- Use `git mv` and `git rm` correctly  

---

### Introduction

In real-world projects, files are not permanent. You will:
- Rename files for better clarity
- Delete files that are no longer needed
- Remove sensitive or unnecessary files from Git

👉 Git provides built-in commands to handle these changes properly.


### 1. Renaming Files in Git

### 📌 Command
```bash
git mv <old_name> <new_name>
```

```bash
git mv file.txt prod.txt
```

#### What Happens?
- File is renamed
- Change is autmatically staged

#### Important note:

You can also rename manually, but then you must stage the renamed file manually and delete the old file from git using `git rm`

### 2. Removing files in Git

```bash
git rm <file_name>
```

When you run `git rm`:   

- File is deleted from your system (Working directory)
- File is removed from git tracking
- Change is automatically staged

#### We can remove the file ONLY from Git (Keep Locally)

```bash
git rm --cached file.txt
```

##### What happens?
- File remains in your system
- File is removed from git tracking

##### Usefull when:
- You accidentally committed a file

#### Force remove (if file is modified)

```bash
git rm -f file.txt
```
👉 Required when Git prevents deletion due to changes

### Key Takeaway:

- `git mv` helps rename files with tracking
- `git rm` helps remove files safely
- `git tm --cached` removes files only from Git

