# Day 08 – Hands-On Practice (Viewing History)

## Task 1: View Full History

Run:

git log

✔ Observe:
- Commit IDs
- Author
- Date
- Messages

---

## Task 2: Compact View

Run:

git log --oneline

✔ Observe:
- Short commit IDs
- One-line messages

---

## Task 3: Limit Commits

Run:

git log --oneline -2

✔ Observe:
- Only last 2 commits displayed

---

## Task 4: Graph View

Run:

git log --oneline --graph --all

✔ Observe:
- Visual representation of commits

---

## Task 5: Filter by Author

Run:

git log --author="your-name"

✔ Replace with your configured username

---

## Task 6: Filter by Time

Run:

git log --since="1 hour ago"

✔ Try different values:
- "1 day ago"
- "1 week ago"

---

## Task 7: Search Commits

Run:

git log --grep="Added"

✔ Observe matching commit messages

---

## Task 8: File History

Run:

git log file1.txt

✔ Observe:
- Only commits related to file1.txt

---

## Task 9: Show Commit Details

1. Copy a commit ID from:

git log --oneline

2. Run:

git show <commit-id>

✔ Observe:
- Commit details
- Changes (just observe, not focus yet)

---

## Outcome

After completing this hands-on, you should be able to:
- Explore Git history
- Filter commits
- Identify specific commits
- Understand project timeline