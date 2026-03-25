# Day 01 - Version Control Systems (VCS)

Welcome to **Day 01** of this learning series.  
In this session, we will understand what Version Control Systems are, why they are important, and explore different types of VCS.

---

## 🎥 Watch the Full Video

👉 **YouTube Link:**  
https://youtu.be/xbaHmTX6Bhg

---

## 📌 What is a Version Control System?

A **Version Control System (VCS)** is a tool that helps track changes to files over time. It allows:

- Maintaining history of changes
- Reverting to previous versions
- Collaborating with multiple users
- Managing different versions of files efficiently

VCS is widely used in:
- Software Development
- Document Management
- Team Collaboration Projects

---

## 📂 Types of Version Control Systems

There are three main types:

1. Local Version Control System (LVCS)
2. Centralized Version Control System (CVCS)
3. Distributed Version Control System (DVCS)

---

# 🖥️ 1. Local Version Control System (LVCS)

## 🔹 Overview
- Works only on a **local machine**
- No server or network required
- Best suited for **individual use**

## 🔹 How it Works
- Stores versions of files locally
- Maintains snapshots of file changes
- Example: Saving files like `file_v1`, `file_v2`, etc.

## 🔹 Examples
- RCS (Revision Control System)
- SCCS (Source Code Control System)

## 🔹 Features
- Maintains change history
- Allows reverting changes
- Tracks modifications
- Stores snapshots

## ✅ Advantages
- Simple and easy to use
- No server required
- Good for solo projects

## ❌ Limitations
- No collaboration support
- Risk of data loss (single machine)
- No remote access

## 📌 Use Cases
- Personal projects
- Experimentation and prototyping
- Non-collaborative work

---

# 🌐 2. Centralized Version Control System (CVCS)

## 🔹 Overview
- Uses a **central server**
- All project data stored in one place
- Users interact with central repository

## 🔹 Workflow

1. Check Out → Get files from server  
2. Modify → Work locally  
3. Commit → Save changes to server  
4. Update → Get latest changes  

## 🔹 Features
- Single central repository
- Access control & permissions
- Backup support
- Conflict handling (locking)

## ✅ Advantages
- Easy to manage
- Central control
- Single source of truth
- Easier backups

## ❌ Disadvantages
- Single point of failure
- Requires internet connection
- Limited scalability

## 🔹 Examples
- SVN (Subversion)
- CVS
- Perforce
- TFS

## 📌 Use Cases
- Small to medium teams
- Enterprise environments
- Teams in same location

---

# 🔁 3. Distributed Version Control System (DVCS)

## 🔹 Overview
- Every user has a **full copy of repository**
- No strict dependency on central server
- Supports **offline work**

## 🔹 How it Works

1. Clone → Get full repository  
2. Work Locally → Make commits  
3. Push/Pull → Sync with others  
4. Branch & Merge → Manage changes  

## 🔹 Features
- Full local repository
- Offline capabilities
- Advanced branching & merging
- Flexible collaboration models

## ✅ Advantages
- No single point of failure
- Faster operations (local)
- Better collaboration
- Efficient branching & merging

## ❌ Disadvantages
- Slightly complex to learn
- Requires more disk space

## 🔹 Examples
- Git
- Mercurial
- Bazaar
- Fossil

---

# 🔄 Common DVCS Workflows

## 1. Centralized Workflow
- Uses a central repo (like GitHub)
- Similar to CVCS but more flexible

## 2. Feature Branch Workflow
- Each feature is developed in a separate branch

## 3. Forking Workflow
- Used in open-source projects
- Contributors work on their own copy

## 4. Gitflow
- Uses branches like:
  - `main` (production)
  - `develop` (development)
  - feature/release/hotfix branches

---

# ⚖️ CVCS vs DVCS

| Feature | CVCS | DVCS |
|--------|------|------|
| Repository | Single server | Full copy for each user |
| Collaboration | Centralized | Peer-to-peer |
| Offline Work | Not possible | Fully supported |
| Failure Risk | High | Low |
| Performance | Slower | Faster |
| Branching | Difficult | Easy |

---

# 🧠 Key Takeaways

- VCS helps track and manage changes efficiently
- LVCS is simple but limited
- CVCS introduces collaboration but has risks
- DVCS (like Git) is the modern standard
- Git is widely used due to flexibility, speed, and reliability

---

# 🚀 What’s Next?

In upcoming sessions, we will:
- Understand **Git basics**
- Install Git
- Work with repositories
- Perform hands-on operations

Stay tuned!

---

