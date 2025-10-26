# CHANGELOG

## Phase 4: Git Command Usage Summary

### Step 4.1: Fetch & Pull
- Used `git fetch instructor` → 1 time  
- Used `git pull instructor main` → 1 time  
- Result: Repository up to date with instructor’s main branch  

### Step 4.2: Stash
- Created branch `feature/new-feature`
- Stashed changes once (`git stash push -m "WIP: New feature development"`)
- Restored using `git stash pop`
- Used stash: **1 time**

### Step 4.3: Cherry-Pick
- Cherry-picked commit from `feature/new-feature` into `main`
- Used cherry-pick: **1 time**

### Step 4.4: Rebase
- Created branch `feature/another-feature` and rebased onto `main`
- Used rebase: **1 time**

### Step 4.5: Reset & Revert
- Used `git reset` (soft, mixed, hard) → 3 times  
- Used `git revert HEAD` → 1 time  
- Used `git reflog` and `git cherry-pick` to recover lost commit  

### Step 4.6: Tag
- Created annotated tags:
  - `v1.0.0` → "Release 1.0.0: Resolved all conflicts"
  - `v1.1.0` → "Release 1.1.0: Added all features"
- Pushed tags to remote using `git push origin --tags`





- 02cb2e6: docs: Add detailed CHANGELOG for Phase 4 (saivenkat-A7, 52 minutes ago)
- f957a23: add git reflog output (saivenkat-A7, 55 minutes ago)
- 266e28a: add checkpoint 4 (saivenkat-A7, 57 minutes ago)
- dac895f: docs: Add FAQ section (saivenkat-A7, 79 minutes ago)
- 733a68e: Add checkpoint 3 (saivenkat-A7, 17 hours ago)
- 17df982: Add chechpoint3 screenshot (saivenkat-A7, 17 hours ago)
- 32dcb96: merge: Resolve all conflicts between main and conflict-simulator branches (saivenkat-A7, 18 hours ago)
- 6838415: merge: Resolve all conflicts between main and dev branches (saivenkat-A7, 18 hours ago)
- 23206f3: Added Checkpoint 2 screenshot (saivenkat-A7, 18 hours ago)
- 150e618: Added Checkpoint 1 screenshot (saivenkat-A7, 18 hours ago)
- 6ddc297: merge: Resolve all conflicts between main and dev branches (saivenkat-A7, 18 hours ago)
- d3dd9b2: updating conflict-simulator (Hanu Gupta, 3 days ago)
- 02011a5: updating dev (Hanu Gupta, 3 days ago)
- 0312c6f: updating main (Hanu Gupta, 3 days ago)
- fadfd24: Revise README for DevOps Simulator project (Hanu Gupta, 3 days ago)
- ae630eb: Initial commit (Hanu Gupta, 3 days ago)