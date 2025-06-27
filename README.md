# Git Commands Test Repository

This repository was created and managed entirely using Git commands to demonstrate basic Git workflow operations.

## Repository Creation Process

This repository demonstrates the complete Git workflow from creation to remote push using only command-line operations:

1. **Repository initialized**
2. **Content added and staged**
3. **Changes committed**
4. **Status and history verified**
5. **Repository pushed to remote**

## Commands Used

### `git status`
Check the current state of the working directory and staging area
```bash
git status
```

### `git add`
Stage files for commit
```bash
git add .                  # Stage all files
git add filename.txt       # Stage specific file
```

### `git commit`
Create commits with different approaches

**With message flag:**
```bash
git commit -m "Your commit message"
```

**Without message flag (opens editor):**
```bash
git commit
```

### `git log`
View commit history
```bash
git log
git log --oneline         # Condensed view
```

### `git push`
Upload commits to remote repository
```bash
git push origin main
```

## Workflow Demonstrated

```bash
# 1. Initialize repository
git init

# 2. Add content to repository
# (files created/modified)

# 3. Check status
git status

# 4. Stage changes
git add .

# 5. Verify staging
git status

# 6. Commit changes
git commit -m "Initial commit"

# 7. Check commit history
git log

# 8. Push to remote
git push origin main

# 9. Final status check
git status
```

## Purpose

This repository serves as a practical example of:
- Basic Git command usage
- Standard development workflow
- Version control fundamentals
- Command-line Git operations

---

*Repository created and maintained using Git commands only - demonstrating essential version control workflow.*