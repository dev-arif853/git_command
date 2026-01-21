````markdown
# 🧰 Common Git Commands for Daily Use

A simple, developer-friendly list of the most frequently used Git commands.  
Perfect for keeping in your project documentation or personal reference.

---

## 🟩 Initialize & Clone

```sh
git init                 # Start a new repository
git clone <repo-url>     # Clone an existing repository
````

---

## 🟦 Branch Management

```sh
git branch               # List branches
git branch <name>        # Create a branch
git checkout <branch>    # Switch branch
git checkout -b <name>   # Create + switch to branch
git merge <branch>       # Merge into current branch
git branch -d <branch>   # Delete local branch
git push origin --delete <branch>   # Delete remote branch
```

---

## 🟨 Remote Repositories

```sh
git remote -v            # Show remote URLs
git fetch                # Get latest info (no merge)
git pull                 # Fetch + merge into current branch
git push                 # Push commits to remote
git push origin <branch> # Push specific branch
```

---

## 🟧 Stage & Commit Changes

```sh
git status               # Check file status
git add .                # Stage all changes
git add <file>           # Stage specific file
git commit -m "message"  # Commit changes
git commit --amend       # Edit last commit message
```

---

## 🟥 View Differences & History

```sh
git diff                 # See unstaged changes
git diff --staged        # See staged changes
git log                  # Full commit history
git log --oneline        # Compact commit history
```

---

## 🟫 Undo & Reset

```sh
git restore <file>                 # Undo local file changes
git restore --staged <file>        # Unstage file
git reset HEAD~1                   # Undo last commit (keep changes)
git reset --hard HEAD~1            # Remove last commit + changes
```

---

## 🟪 Tags

```sh
git tag                  # List tags
git tag <tagname>        # Create a tag
git push origin <tag>    # Push one tag
git push --tags          # Push all tags
```

---

## 🟦 Rebase (Advanced)

```sh
git rebase <branch>      # Move commits on top of another branch
git rebase --abort       # Cancel rebase
git rebase --continue    # Continue after fixing conflicts
```

---

## 🟫 Working With Remote Branches

```sh
git checkout -b <branch> origin/<branch>   # Create local branch from remote
git push origin <local>:<remote>            # Push to a differently named remote branch
```

---

## ⭐ Daily Workflow Example

```sh
git checkout feature/my-feature
git pull origin develop
git add .
git commit -m "Updated feature"
git push origin feature/my-feature
```

---

## 📌 Tip

Use `.gitignore` to prevent unnecessary files from being tracked.

---

Happy coding! 🚀

```
