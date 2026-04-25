# Day 09 – Viewing Changes (git diff)

## What is git diff?

`git diff` is used to view changes between different states in Git.

It helps you understand:
- What lines were added
- What lines were removed
- What exactly changed in your code

---

### Types of Comparisons in Git

Git allows you to compare:

1. Working Directory vs Staging Area  
2. Staging Area vs Last Commit  
3. Between two commits  

---

### Compare Working Directory Changes

```git
git diff
```

#### Explanation:
- Shows changes between Working Directory and Staging Area
- Displays unstaged changes

#### Use Case:
- Check what you modified before staging


### Understanding git diff Output

`+` → Added lines  
`-` → Removed lines  

Example:
+ console.log("New line")
- console.log("Old line")

---

### Compare Staged Changes

```git
git diff --staged
git diff --cached
```

#### Explanation:
- Shows changes between Staging Area and Last Commit
- Displays staged changes ready to commit


### Compare Between Commits

```git
git diff <commit1> <commit2>
```

#### Example:
```git
git diff a1b2c3 d4e5f6
```

#### Explanation:
- Compares two commits
- Shows what changed between them


### Compare Specific File

```git
git diff filename
```

#### Explanation:
- Shows changes only for a specific file

---
### Real-Time Usage Flow

Typical developer workflow:

1. Modify file  
2. Check changes  
   → git diff  

3. Stage file  
   → git add  

4. Verify staged changes  
   → git diff --staged  

5. Commit changes  

---

### Important Notes

- `git diff` shows only unstaged changes  
- `git diff --staged` shows staged changes  
- Use commit IDs carefully when comparing commits  



### Summary

#### Key commands:

git diff  
git diff filename  
git diff --staged  
git diff --cached  
git diff <commit1> <commit2>