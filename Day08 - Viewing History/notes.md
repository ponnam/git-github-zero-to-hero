# Day 08 – Viewing History (git log)

## What is Git History?

Git history represents all the commits made in a repository over time.

Each commit contains:
- Commit ID (hash)
- Author
- Date
- Commit message

Git provides the `git log` command to explore this history.

---

## View All Commits

### Command:
git log

### Explanation:
- Displays full commit history
- Shows detailed information for each commit
- Opens in a scrollable view

### Tip:
Press `q` to exit the log view

---

## Compact View

### Command:
git log --oneline

### Explanation:
- Shows each commit in a single line
- Displays short commit ID + message
- Useful for quick overview

---

## Limit Number of Commits

### Command:
git log --oneline -5

### Explanation:
- Displays only the last 5 commits
- Helps focus on recent activity

---

## Graph View

### Command:
git log --graph

### Recommended:
git log --oneline --graph --all

### Explanation:
- Displays commit history in a visual graph format
- Shows branching and merging structure
- Useful for understanding project flow

---

## Filter by Author

### Command:
git log --author="username"

### Explanation:
- Shows commits made by a specific author
- Useful in team environments

---

## Filter by Time

### Commands:
git log --since="2 days ago"
git log --since="1 week ago" --oneline

### Explanation:
- Filters commits based on time
- Helps track recent work

---

## Search by Commit Message

### Command:
git log --grep="keyword"

### Explanation:
- Searches commits containing specific text
- Useful for finding features or bug fixes

---

## File-specific History

### Command:
git log filename

### Explanation:
- Shows history of a specific file
- Helps track file-level changes over time

---

## Show Commit Details

### Command:
git show <commit-id>

### Example:
git show a1b2c3

### Explanation:
- Displays detailed information about a commit
- Includes metadata and changes
- Focus here is on identifying commit details

---

## Summary

Key commands:

git log  
git log --oneline  
git log --oneline --graph --all  
git log --author="name"  
git log --since="2 days ago"  
git log --grep="keyword"  
git log filename  
git show <commit-id>