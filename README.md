## Feature 3 
Add Main Section to the code
 
# Git Workflow Overview
 
This repository demonstrates a complete Git workflow including branching, pull requests, rebasing, cherry-picking, squashing commits, and release tagging.
 
---
 
## Initial Setup
 
- Created `main` branch → added `.github/pull_request_template.md`
- Created `develop` branch from `main` → added `develop.txt`
- Created `commit-msg` file in .git/hooks for commit message hook.
 
---
 
## Feature 1 (f1)
 
- Created from `develop`
- Added: `feature1.txt`, `feature2.txt`, `feature3.txt`
- Pushed branch and raised PR
- Merged into `develop`
 
---
 
## Feature 2 (f2)
 
- Created from `develop`
- Added: `login.txt`
- Pulled latest changes from `develop`
- Raised PR → merged into `develop`
- `develop` now contains both **f1** and **f2** changes
 
---
 
## Release v1.0.0
 
- Raised PR from `develop` → merged into `main`
- Pulled latest changes locally
- Added tag on `main`:
 
  v1.0
 
---
 
## Feature 3
 
- Created from `develop`
- Added `README.md` file 
---
 
## Feature 4
 
- Created from `develop`
- Cherry-picked `README` commit from Feature 3
- Create new file profile.txt
- Added commits:
  - `Line 1 added`
  - `Line 2 added`
  - `Line 3 added`
- Removed last commit using git reset --hard HEAD~1
- Raised PR → merged into `develop`
 
---
 
## Final Merge
 
- Raised PR from `develop` → merged into `main`
- Pulled all latest changes locally for both `main` and `develop`
 
---
 
## Concepts Covered
 
- Branching strategy (`main`, `develop`, feature branches)
- Pull Requests (PR workflow)
- Merging branches
- Cherry-pick commits
- Interactive rebase (drop, squash)
- Release tagging (`v1.0.0`)
- Syncing local and remote branches
 
---
 
This project provides a clear example of structured Git workflow from feature development to production release.
Add Main Section to the code
