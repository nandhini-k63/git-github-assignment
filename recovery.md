# Git Recovery Report

## Commands Used

Created a new branch:

git checkout -b experiment


Created a temporary file:

nano temporary.txt


Added and committed the file:

git add temporary.txt

git commit -m "Add temporary file for recovery test"


Undid the changes safely:

git revert HEAD


## Why This Approach Was Safe

I used git revert because it creates a new commit that reverses the changes.

The original commit is still available in Git history.

This approach keeps the complete repository history and does not permanently delete previous commits.
