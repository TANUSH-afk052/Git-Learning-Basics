
# 🟩 Git Learning – Day 3

## ✅ Topics Covered

### 🔹 1. Git Repository Initialization

- `git init`: Initializes a new local Git repository.

### 🔹 2. Staging and Committing

- `git add <file>`: Stages a file for commit.
- `git commit -m "message"`: Commits staged changes with a message.

### 🔹 3. Checking Status and Logs

- `git status`: Shows status of working directory and staging area.
- `git log`: Shows commit history.

### 🔹 4. Renaming & Removing Files

- `mv oldname newname`: Rename files/folders in terminal.
- `git rm <file>`: Remove file and stage for deletion.

### 🔹 5. Pushing to GitHub

- `git remote add origin <url>`: Link local repo to remote.
- `git branch -M main`: Rename branch to `main`.
- `git push -u origin main`: Push code to GitHub.

### 🔹 6. Fixing Common Errors

- Error: `fatal: not a git repository` → Run `git init`
- Error: `origin does not appear to be a git repository` → Use correct remote URL
- Username/password prompt → Use GitHub **personal access token**

---

## 💡 Key Notes

- Always `git add` before `git commit`
- Don't forget to `git push` to sync with GitHub
- Use `git status` frequently to avoid confusion

---

## ✅ Example Workflow

```bash
git init
git add README.md
git commit -m "Initial commit"
git remote add origin https://github.com/yourusername/yourrepo.git
git branch -M main
git push -u origin main
```

---

## 🔒 Personal Access Tokens

Since GitHub removed password login for Git operations, use a **token** instead:

1. Go to GitHub → Settings → Developer Settings → Tokens (classic)
2. Generate new token with `repo` access
3. Use it instead of password when prompted

---

## 📌 What's Next (Day 4)

- Working with branches
- Cloning repositories
- Pulling and merging
- GitHub Pages and collaborative workflow
