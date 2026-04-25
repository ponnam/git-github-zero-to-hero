#  Day 10:  Rename & Remove files (git rm & git mv)

## 🎯 Objective
By completing this lab, you will learn how to:
- Rename files using Git
- Remove files from Git
- Remove files only from Git tracking (keep locally)
- Understand how Git tracks file changes

---

### ⚙️ Prerequisites
- Git installed
- Basic knowledge of `git add`, `git commit`, `git status`



### 🚀 Task 1: Create a New Repository

Open your terminal and run:

```bash
mkdir git-day10
cd git-day10
git init
```
👉 This creates a new Git repository

### Task 2: Create Initial File
```bash
echo "Hello Git" > file.txt
git add file.txt
git commit -m "Initial Commit"
```

### Task 3: Verify Status

```bash
git status
```
👉 **Output should show:**

nothing to commit, working tree clean

## PART 1: Rename file using Git
### Task 4: Rename file
```bash
git mv file.txt app.txt
```
👉 This renames the file and stages the change automatically

### Task 5: Check the status
```bash
git status
```
👉 You will see:

**renamed: file.txt -> app.txt**

### Task 6: Commit Rename

```bash
git commit -m "Renamed file.txt to app.txt
```

## Part 2: Remove file from Git

### Task 7: Remove file
```bash
git rm app.txt
```
👉 This:

Deletes the file from your system  
Removes it from Git tracking  
Stages the change  

### Task 8: Check Status
```bash
git status
```
👉 You will see:

**deleted: app.txt**

### Task 9: Commit Removal

```bash
git commit -m " Removed app.txt
```

## Part 3: Remove file Only form Git (Keep Locally)

### Task 10: Create new file
```bash
echo "Temporary data" > temp.txt
git add temp.txt
git commit -m "Added temp file"
```
### Task 11: Remove from Git only
```bash
git rm --cached temp.txt
```

👉 This:

Removes file from Git tracking  
Keeps file in your local system  

### Task 12: Verify
```bash
git status
```
👉 **You will see:**

deleted: temp.txt

But file still exists locally.

### Task 13: Commit changes

```bash
git commit -m " Removed Temp.txt from Git Tracking"
```

## Part 4: Force Remove

### Task 14: Create and Modify file
```bash
echo "Test file" > test.txt
git add test.txt
git commit -m "Added test file"

echo "Modified content" >> test.txt
```
### Task 15: Try removing using `git rm`

```bash
git rm test.txt
```
👉 You may get an error because file is modified

### Task 16: Force Remove

```bash
git rm -f test.txt
git commit -m "Force removed test.txt"
```
## Pro Tip

**Always check `git status` before committing, this helps you avoid mistakes**

## Summary:
- `git mv` --> Rename files
- `git rm` --> delete files
- `git rm --cached` --> reove from Git only

👉 **Practice these commands multiple times to gain confidence**

