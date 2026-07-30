# Advanced Git Commands

## 1. git stash

### Purpose

git stash temporarily saves changes that are not committed yet and gives a clean working directory.

### Syntax

git stash

### Example

git stash

git stash pop

### When to use it

Use git stash when you are working on a feature but need to switch to another branch quickly without committing incomplete changes.

---

## 2. git cherry-pick

### Purpose

git cherry-pick applies the changes from a specific commit to the current branch.

### Syntax

git cherry-pick <commit-id>

### Example

git cherry-pick 5d991aa

### When to use it

Use git cherry-pick when you need a particular commit from another branch without merging the entire branch.

---

## 3. git reflog

### Purpose

git reflog records the history of where HEAD and branch references have moved. It helps recover lost commits.

### Syntax

git reflog

### Example

git reflog

### When to use it

Use git reflog when you accidentally delete a branch, reset commits, or need to find previous states of your repository.
