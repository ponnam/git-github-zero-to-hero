# Day 09 – Hands-On Practice (Viewing Changes)

### Setup

1. Create a project folder and initialize Git
```git
git init
```

2. Create initial file

```git 
echo "Hello World" > file.txt
git add .
git commit -m "Initial commit"
```

---

### Task 1: Modify File (Unstaged Changes)

Edit file: add a new line 

echo "New line added" >> file.txt

Run:

```git
git diff
```

#### Observe:
- Added lines (+)
- Differences from last staged version



### Task 2: Compare Specific File

Run:
```git
git diff file.txt
```

#### Observe:
- Changes only for file.txt



### Task 3: Stage Changes

Run:

git add file.txt

Now check:
```git
git diff
```

#### Observe:
- No output (because changes are staged)



### Task 4: View Staged Changes

Run:
```git
git diff --staged

or

git diff --cached
```

#### Observe:
- Changes ready to commit



### Task 5: Commit Changes

Run:
```git
git commit -m "Updated file.txt"
```


### Task 6: Make More Changes

echo "Another line" >> file.txt

git add file.txt
git commit -m "Second update"



### Task 7: Compare Commits

1. Get commit IDs:
```git
git log --oneline
```
2. Copy two commit IDs

3. Run:
```git
git diff <commit1> <commit2>
```
#### Observe:
- Differences between commits


### Task 8: Multiple Changes Practice

1. Modify file again:

echo "Final change" >> file.txt

2. Run:
```git
git diff
```
3. Stage:
```git
git add file.txt
```
4. Run:
```git
git diff --staged
```
#### Understand difference clearly


---
### Challenge Task

Try this flow:

1. Make changes  
2. Run git diff  
3. Stage changes  
4. Run git diff --staged  

#### Explain the difference in your own words


