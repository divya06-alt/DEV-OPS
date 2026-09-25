# Git & GitHub Practice

## Overview

This practice helped me understand the basic Git workflow and how branches are used to manage different versions of a project.

## Commands Practiced

### 1. Clone a Repository

```bash
git clone <repository-url>
```

Used to copy a GitHub repository to the local computer.

### 2. Check Repository Status

```bash
git status
```

Used to check the current branch and the status of files.

### 3. Create a File

```bash
vi shar.txt
```

Created a new file inside the repository.

### 4. Stage a File

```bash
git add shar.txt
```

Moved the new file to the **staging area**.

### 5. Commit Changes

```bash
git commit -m "Add shar file"
```

Saved the staged changes into the local Git history.

### 6. Create a Branch

```bash
git branch master
```

Created a new `master` branch.

### 7. Switch Branches

```bash
git checkout master
```

Switched from `main` to `master`.

```bash
git checkout main
```

Switched back from `master` to `main`.

### 8. Create and Commit a File on Master

Created `master.txt` on the `master` branch:

```bash
git add master.txt
git commit -m "Add master file"
```

The file existed on `master` but was not present when switching back to `main`.

## Git Workflow Practiced

```text
GitHub Repository
       ↓
   git clone
       ↓
   Working Directory
       ↓
    git add
       ↓
   Staging Area
       ↓
   git commit
       ↓
   Local Repository
       ↓
    git push
       ↓
GitHub Repository
```

## Branch Practice

```text
main
  │
  ├── shar.txt
  │
  └── Create master
          │
          ↓
       master
          │
          └── master.txt
          
          ↓
     checkout main
          ↓
         main
```

## Key Learnings

* `git clone` → Copies a repository from GitHub to the computer.
* `git status` → Shows the current Git status.
* `git add` → Moves changes to staging.
* `git commit` → Saves staged changes to local Git history.
* `git branch` → Shows available branches.
* `git checkout` → Switches between branches.
* `git push` → Uploads local commits to GitHub.
* `git pull` → Gets the latest changes from GitHub.

### Conclusion

Through this practice, I learned the basic Git workflow, staging and committing files, creating branches, and switching between `main` and `master` branches.
