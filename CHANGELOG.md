
# CHANGELOG

## Phase 4: Git Command Usage Summary

### Step 4.1: Fetch & Pull
- Used `git fetch instructor` → 1 time  
- Used `git pull instructor main` → 1 time  
- Result: Repository up to date with instructor’s main branch  

### Step 4.2: Stash
- Created new branch `feature/new-feature`
- Stashed changes once (`git stash push -m "WIP: New feature development"`)
- Restored using `git stash pop`
- Used stash: **1 time**

### Step 4.3: Cherry-Pick
- Cherry-picked commit from `feature/new-feature` into `main`
- Used cherry-pick: **1 time**

### Step 4.4: Rebase
- Rebasing `feature/another-feature` onto `main`
- Used rebase: **1 time**

### Step 4.5: Reset & Revert
- Used `git reset` (soft, mixed, hard) → 3 times  
- Used `git revert HEAD` → 1 time  
- Used `git reflog` and `git cherry-pick` to recover commit  

### Step 4.6: Tag
- Created annotated tags:
  - `v1.0.0` → "Release 1.0.0: Resolved all conflicts"
  - `v1.1.0` → "Release 1.1.0: Added all features"
